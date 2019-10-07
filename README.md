# bootstrap-ordering-property
Bootstrap’s order property can be used to alternate text/image views so that your layout can aesthetically flow.

## Tutorial
For detailed instruction's, view Solodev's [Establish a Flow with your Layout with Bootstrap’s Ordering Property](https://www.solodev.com/blog/web-design/establish-a-flow-with-your-layout-with-bootstraps-ordering-property.stml) article.

## Demo
  		  
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/p6zs457y/).

## HTML

The tutorial contains the following basic HTML markup.

```
<div class="container mt-md-6 mt-5">
        <div class="row">
          <div class="mt-md-5 mt-4 text-center col-md-10 col-lg-7 mx-auto">
                <h1>Explore Our Ships</h1>
            <img class="img-fluid" alt="Our Ships" src="https://raw.githubusercontent.com/solodev/bootstrap-ordering-property/master/images/ships.png">
          </div>
          <div class="col-lg-10 col-xl-7 mx-auto text-center">
            <p class="lead">From the dawn of the modern space age, exploring the moon has been the dream of every human being. Now, that dream has become a reality with LunarXP and our permanent XP-1 Colony.
            </p>
          </div>
        </div>
        <div class="row align-items-center mt-6">
            <div class="col-md-10 col-lg-6 mx-auto"> 
              <img class="img-fluid" alt="Valkyrie-1 series" src="https://raw.githubusercontent.com/solodev/bootstrap-ordering-property/master/images/valkyrie-big.jpg"> 
            </div>
            <div class="col-xl-5 col-lg-6 ml-auto mt-lg-0 mt-5 text-lg-left text-center">
              <h2>From Surface to Space in Minutes</h2>
              <p>As the lean, mean “muscle” of the LunarXP fleet, the Valkyrie-1 series makes safe transportation from surface to orbit a reality. A medium-sized liftoff and reentry vehicle designed for escape velocity, the Valkyrie-1 docks seamlessly with the Lunar XPlorer transport and can be utilized to move crew and supplies from surface to space in just minutes.</p>
            </div>
          </div>
          <div class="row align-items-center mt-lg-6 mt-4">
            <div class="col-md-10 col-lg-6 ml-auto order-lg-2 order-1"> 
              <img class="img-fluid mx-auto w-600p mt-4" alt="Talon-2 series" src="https://raw.githubusercontent.com/solodev/bootstrap-ordering-property/master/images/talon-big.jpg">
            </div>
            <div class="col-xl-5 col-lg-6 mr-auto mt-lg-0 mt-5 order-lg-1 order-2 text-lg-left text-center">
              <h2>Crossing the Colony</h2>
              <p>As the LunarXP-1 settlements expands, it’s critical to move people and resources across greater distances. The newest member of our fleet, the Talon-2 series is the primary vehicle for crossing the colony and delivering both personnel and goods to habitats – from agriculture to engineering equipment.
                 Capable of traveling from the Sea of Tranquility living hub to the Reiner Gamma labs in less than one hour, the Talon vehicles are fast, light, and highly maneuverable on the lunar surface.</p>
            </div>
          </div>
          <div class="row align-items-center mt-6">
            <div class="col-md-10 col-lg-6 mx-auto"> 
              <img class="img-fluid" alt="Lunar XPlorer" src="https://raw.githubusercontent.com/solodev/bootstrap-ordering-property/master/images/Lunar_XPlorer-big.jpg"> 
            </div>
            <div class="col-xl-5 col-lg-6 ml-auto mt-lg-0 mt-5 text-lg-left text-center">
              <h2>Bringing the Moon Closer Than Ever</h2>
              <p>Often referred to as a “container ship in space,” the Lunar XPlorer is the flagship of the LunarXP fleet and the primary mode of transportation for people, equipment, and supplies to the moon. It is also the ferry for returning mined minerals, precious and refined metals, energy products and other resources to earth.</p>
            </div>
          </div>
    </div>
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
```
