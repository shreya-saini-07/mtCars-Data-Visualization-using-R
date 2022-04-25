# mtCars-Data-Visualization-using-R

Dataset: https://drive.google.com/drive/folders/1t1TBvhgcH3SoCkUyH-AyDVLVvlEnGEx3?usp=sharing

Data visualization is a technique used for the graphical representation of data. By using elements like scatter plots, charts, graphs, histograms, maps, etc., we make our data more understandable. Data visualization makes it easy to recognize patterns, trends, and exceptions in our data. It enables us to convey information and results in a quick and visual way.
It is easier for a human brain to understand and retain information when it is represented in a pictorial form. Therefore, Data Visualization helps us interpret data quickly, examine different variables to see their effects on the patterns, and derive insights from our data.

# Discussion of mtcars variables
<img width="696" alt="Screenshot 2022-04-14 at 11 35 03 AM" src="https://user-images.githubusercontent.com/80120667/163323806-f23c33a6-209e-481b-bed6-9b13364f89a4.png">

# Analysing Plots using R

1. To plot mpg(Miles per Gallon) vs Number of cars
plot(mtcars$mpg, xlab = "Number of cars", ylab = "Miles per Gallon", col = "red")

2. To find relation between hp (Horse Power) and mpg (Miles per Gallon)
plot(mtcars$hp,mtcars$mpg, xlab = "HorsePower", ylab = "Miles per Gallon", type = "h", col = "blue")

3. To find relation between hp (Horse Power) and mpg (Miles per Gallon)
plot(mtcars$hp,mtcars$mpg, xlab = "HorsePower", ylab = "Miles per Gallon", type = "h", col = "blue")

4. To draw a barplot of hp
#Horizontal
barplot(mtcars$hp,xlab = "HorsePower", col = "cyan", horiz = TRUE)

5. Vertical
barplot(mtcars$hp, ylab = "HorsePower", col = "cyan", horiz = FALSE)

6. To find histogram for mpg (Miles per Gallon)
hist(mtcars$mpg,xlab = "Miles Per Gallon", main = "Histogram for MPG", col = "yellow")

7. To draw boxplots for disp (Displacement) and hp (Horse Power)
boxplot(mtcars[,3:4])

Challenges Faced:
Collecting and cleaning the Data
Establish relation between the parameters and its dependency on other factors.

To implement the project, run the uploaded data csv file on kaggle and using the commands above, analysis can be done against respective parameters.
Implemented on kaggle: https://www.kaggle.com/code/shreyasaini07/mtcars-data-visualization-using-r
