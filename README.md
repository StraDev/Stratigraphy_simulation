# Stratigraphy Simulation

## Introduction
This is a program that can simulate stratigraphcial process through 3D interactive models. Users can interact with the model through different geological processes and defining their own parameters in the process. 



## Example
### 1. Deposition     
  thickness of units = [3, 2, 2, 2, 1, 3, 2]   
 
  `deposition_thickness = [3, 2, 2, 2, 1, 3, 2]`   
   `for thickness in deposition_thickness:`   
      `deposition.coordinates(thickness=thickness)`
    `plot.plot()`   

<img width="393" alt="image" src="https://user-images.githubusercontent.com/99826605/164347200-1e6995c4-c643-4c0a-a9c6-f9dff9c8e9c7.png">

### 2. Uplift    
  dip = 180, dip angle = 40    
   
  `ulangle, ulbearing = 40, 180`   
  `uplift.coordinates(ulangle, ulbearing)`       
  `plot.plot()`   

<img width="393" alt="image" src="https://user-images.githubusercontent.com/99826605/164352569-b6aa3304-eaea-4fc9-9fc4-0017d6d8fe24.png">

### 3. Folding:
  compression direction=EW, type of fold = anticline, wavelength = 6   

  `fdir, cline, flength = 'x', 'a', 6`   
  `folding.coordinates(fdir, cline, flength)`    
  `plot.plot()`   

<img width="393" alt="image" src='https://user-images.githubusercontent.com/99826605/164355558-63b3ceb3-483d-4dca-a8fb-a5a6bed56222.png'>

### 4. Erosion:    
  surface height = 4   

  `uplim = 4`   
  `erosion.coordinates(uplim)`   
  `plot.plot()`   

<img width="393" alt="image" src='https://user-images.githubusercontent.com/99826605/164356684-2b9e1f75-0795-403d-b6a0-9c81554e362b.png'>

### 5. Deposition:    
  thickness of units = [1, 3, 1, 2, 1]     

  `deposition_thickness = [1, 3, 1, 2, 1]`   
  `for thickness in deposition_thickness:`   
     `deposition.coordinates(thickness)`   
   `plot.plot()`   

<img width="393" alt="image" src='https://user-images.githubusercontent.com/99826605/164356811-1f55c536-c4fc-485f-bc24-d0687b732405.png'>

### 6. Uplift:   
  dip = 292, dip angle = 40    

  `ulangle, ulbearing = 40, 292`   
  `uplift.coordinates(ulangle, ulbearing)`    
  `plot.plot()`   

<img width="393" alt="image" src='https://user-images.githubusercontent.com/99826605/164356997-9f122be2-0b36-487a-9ae2-f6a01088b15f.png'>

### 7. Erosion:   
  surface height = 4    

  `uplim = 4`   
  `erosion.coordinates(uplim)`    
  `plot.plot()`   

<img width="393" alt="image" src='https://user-images.githubusercontent.com/99826605/164357072-c005f21f-f69f-4ff3-8f69-13c02610d854.png'>

### 8. Faulting:   
  strike = 90, dip = 30, displacement = 2.8   

  `strike, dip, disp = 99, 30, 2.8`   
  `faulting.coordinates()`   
  `plot.plot()`   
  
<img width="393" alt="image" src='https://user-images.githubusercontent.com/99826605/164357139-c9998b86-f47a-46b7-99a0-40f440c98ed4.png'>

### 9. Erosion:    
  surface height = 4   

  `uplim = 4`   
  `erosion.coordinates(uplim)`    
  `plot.plot()`  

<img width="393" alt="image" src='https://user-images.githubusercontent.com/99826605/164357187-bf39b22f-fa64-4442-acde-0da389a4593f.png'>
