# *Slider images*
A module that will allow you to add an image slider to your web application.
The slider has buttons for control, an indicator of the current slide and the total number of slides.
## To initialize the module in your project, you need to pass some variables in object format when calling the slider function:
1. container - div wrapper selector for all slider elements;
2. slide - selectors from div in which only slider pictures are placed;
3. nextArrow, prevArrow - selectors from forward/back switches;
4. totalCounter, currentCounter - selectors from span in which the number of the current slide and the number of slides in the slider will be displayed.
5. wrapper, field - wrapper selectors only for pictures.
## Example of writing HTML layout for a slider
```Html
<div class="offer__slider"> <!--container-->
  <div class="offer__slider-counter">
      <div class="offer__slider-prev"> <!--prevArrow-->
          <img src="icons/left.svg" alt="prev">
      </div>
      <span id="current">03</span> <!--currentCounter-->
      /
      <span id="total">04</span> <!--totalCounter-->
      <div class="offer__slider-next"> <!--nextArrow-->
          <img src="icons/right.svg" alt="next">
      </div>
  </div>
  <div class="offer__slider-wrapper"> <!--wrapper-->
      <div class="offer__slider-inner"> <!--field-->
          <div class="offer__slide"> <!--slide-->
              <img src="img/slider/pepper.jpg" alt="pepper">
          </div>
          <div class="offer__slide"> <!--slide-->
              <img src="img/slider/food-12.jpg" alt="food">
          </div>
          <div class="offer__slide"> <!--slide-->
              <img src="img/slider/olive-oil.jpg" alt="oil">
          </div>
          <div class="offer__slide"> <!--slide-->
              <img src="img/slider/paprika.jpg" alt="paprika">
          </div>
      </div>
  </div>
</div>
```
## View of the slider on the web page
![image](https://user-images.githubusercontent.com/100083448/181718792-4811fb3b-db54-48e2-9962-c321003a7774.png)

