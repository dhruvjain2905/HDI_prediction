# HDI Estimation Using Satellite Imagery and Convolution Neural Networks

Researched Published here: 
[https://nhsjs.com/2023/estimating-global-subnational-hdi-using-satellite-imagery-and-convolutional-neural-networks/](url)

The Human Development Index (HDI) is a multidimensional index used to measure the amount of development and overall human well-being in a specific country or subnational division of the world. 
The idea here is to develop a system to estimate HDI using data that is easier to collect. Here, I combine nighttime satellite imagery with population data. The idea simple, an area with relatively high luminosity but low population should more developed. An area with low luminosity but high population should be less developed. 


● Developed a multimodal convolutional neural network to estimate Subnational Human Development Index around the world using TensorFlow and Keras
● Designed architecture, trained model using NASA Black Marble’s nighttime satellite imagery and NASA SEDAC gridded population data
● Developed method in Python to compile and process data from multiple sources using Pandas, Pillow, NumPy
● Mean Absolute Error of 0.0945 points
