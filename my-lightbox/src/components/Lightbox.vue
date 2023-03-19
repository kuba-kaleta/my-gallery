<template>
 
  <div>
    <ul >
      
       
          <li style="float: left; margin: 5px;">
       
            <a href="https://therichpost.com/wp-content/uploads/2021/05/bootstrap5-carousel-slider-img2.jpg" class="glightbox">
              
              <img style="height: 105px;" src="https://therichpost.com/wp-content/uploads/2021/05/bootstrap5-carousel-slider-img2.jpg" alt="image" />
           
            </a>
            
          
            </li>
  
            
          
  
            
            <li style="float: left; margin: 5px;">
       
            <a href="https://therichpost.com/wp-content/uploads/2021/05/bootstrap5-carousel-slider-img1.jpg" class="glightbox">
             
              <img style="height: 105px;" src="https://therichpost.com/wp-content/uploads/2021/05/bootstrap5-carousel-slider-img1.jpg" alt="image" />
           
            
            </a>
            
          
            </li>
  
               
            <li style="float: left; margin: 5px;">
       
            <a href="https://therichpost.com/wp-content/uploads/2021/05/bootstrap5-carousel-slider-img3.jpg" class="glightbox">
             
              <img style="height: 105px;" src="https://therichpost.com/wp-content/uploads/2021/05/bootstrap5-carousel-slider-img3.jpg" alt="image" />
           
            </a>
         
          
            </li>
      </ul>
      </div>
      
  </template>
  
  <script>
  import  "glightbox/dist/css/glightbox.css";
  import  "glightbox/dist/js/glightbox.js";
  import GLightbox from 'glightbox';
  export default {
         
    mounted(){ 
  
            //lightbox settings
               this.lightbox = GLightbox({ 
                selector: ".glightbox"
               });
        
      }
  }
  </script>