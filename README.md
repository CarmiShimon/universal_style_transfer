# universal_style_transfer
Deep Learning Project implementing "Universal Style Transfer via Feature Transforms" in Pytorch and adds new functionalities such as boosting and new merging techniques.

### Implementing:
Eyal Waserman & Carmi Shimon

## Results

### Transfer
Content                    |  Style                   | Result
:-------------------------:|:------------------------:|:------------:
![alt text](https://github.com/eyalw711/universal_style_transfer/blob/master/Report/Figures/nyc_sq.jpg "nyc")  |  ![alt text](https://github.com/eyalw711/universal_style_transfer/blob/master/Report/Figures/graffiti_sq.jpg "graffiti")  |  ![alt text](https://github.com/eyalw711/universal_style_transfer/blob/master/Report/Figures/transfer_examples/transfer_nyc_graffiti_08_ref.jpg "result")  
![alt text](https://github.com/eyalw711/universal_style_transfer/blob/master/Report/Figures/room_sq.jpg "room")  |  ![alt text](https://github.com/eyalw711/universal_style_transfer/blob/master/Report/Figures/st2_sq.jpg "paint")  |  ![alt text](https://github.com/eyalw711/universal_style_transfer/blob/master/Report/Figures/transfer_examples/transfer_room_paint_08_ref.jpg "result")  

### Boost
Content                    |  Style                   | No Boost    | Boost
:-------------------------:|:------------------------:|:-----------:|:--------:
![alt text](https://github.com/eyalw711/universal_style_transfer/blob/master/Report/Figures/car_sq.jpg "car")  |  ![alt text](https://github.com/eyalw711/universal_style_transfer/blob/master/Report/Figures/st2_sq.jpg "paint")  |  ![alt text](https://github.com/eyalw711/universal_style_transfer/blob/master/Report/Figures/boost/boost_in2_st2_05_no.jpg "No Boost")  | ![alt text](https://github.com/eyalw711/universal_style_transfer/blob/master/Report/Figures/boost/boost_in2_st2_05.jpg "Boost")  
![alt text](https://github.com/eyalw711/universal_style_transfer/blob/master/Report/Figures/room_sq.jpg "room")  |  ![alt text](https://github.com/eyalw711/universal_style_transfer/blob/master/Report/Figures/giraffe_sq.jpg "giraffe")  |  ![alt text](https://github.com/eyalw711/universal_style_transfer/blob/master/Report/Figures/boost/boost_room_giraffe_05_no.jpg "No Boost")  | ![alt text](https://github.com/eyalw711/universal_style_transfer/blob/master/Report/Figures/boost/boost_room_giraffe_05.jpg "Boost")  
