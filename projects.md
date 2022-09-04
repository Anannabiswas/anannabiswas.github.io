---
layout: default
title: "Projects"
---



<div class="row gx-5 mb-5">
   
   <h3 class="fw-bold border-bottom pb-3 mb-5">Project: Deepmice</h3>
           <h5> Activity in V1 predicts spontaneous running behaviour in the absence of visual stimuli in mice </h5>
   
        <p>  
           <b>Goal: </b> Our aim was to predict mice spontaneous behavior (e.g. running speed)based on the activity of the visual cortex and find out the
           relation between neurons of each layer and running speed.
           
        </p>   
   
    <div class="col-sm mt-3 mt-md-0">
       <img src="{{ site.github.url }}/assets/img/aim.PNG" width="250" height="310" class="img-fluid rounded z-depth-1">
     
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img src="{{ site.github.url }}/assets/img/layer.PNG" width="250" height="310" class="img-fluid rounded z-depth-1"> 
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img src="{{ site.github.url }}/assets/img/corr.png" width="250" height="310" class="img-fluid rounded z-depth-1">
     <p>
    
       Fig1: Predicting running speed from visual cortex (V1) &nbsp; &nbsp; Fig2: 9 layers of neurons  &nbsp; &nbsp; Fig3: Correlation between 9 layers and running
       speed.
    </p>  
      <p>
         <b>Method and Results: </b> To understand the relation between mouse visual cortex and running behavior (when mice are not receiving visual inputs), we 
         utilized the Stringer data set, which consists of calcium imaging neural activity data of neurons in mouse primary visual cortex, as well as running speed
         when the mouse is kept in darkness. Principle Component Analysis (PCA) was applied to reduce the dimension of our neuron activity data of 11983 excitatory
         neurons into 2000 principal components that contain 88.82% of the cumulative explained variance. Following this, we modeled the relationship between neural 
         activity data and running speed data using a linear regression model and were able to achieve an RMSE of 1.86 and 4.21 cm/s on the training and testing 
         dataset respectivly. Furthermore, we applied pearson correlation for determine the relationship of running speed with specific layer of neurons and found out
         that there is higher correlation between 6th layer and running behavior. 
      </p>
      <p>
         Mentors: Dr Mari Sosa, Dr Kiah Hardcastle, Rei Masuda, Deepika Gupta  <br>
         Team Members:Cristian Lazo Quispe, <b>Ananna Biswas </b> , Bhavika Gopalini, Rouhong Wang, Asutosh Routa, Abraham George, Jongwon Yun
      </p> 
      
   </div>
   
</div>

