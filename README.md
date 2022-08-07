# Car-Price-Analyzing-Dashboard-Using-Dash-With-Python



# Objectives
<div class="alert alert-block alert-info" >
After completing the lab you will be able to:

* Create a dash board layout
* Add a bar chart
</div>

## Task 3: Practice Exercise
## Story:

Here we are looking into an __automobile dataset__ which has various attributes like __drive-wheels,body-style and price__.

Lets view the snapshot of our selected dataset.

Here let's say we are selecting 3 important features __drive-wheels, body-style and Price__.

*    The possible values of drive-wheels are __4 wheel Drive(4wd),Front WheelDrive(fwd) and Rear wheel Drive(rwd)__.

*    The different body styles of the cars are hardtop,sedan,convertible and so on.


__There are 2 types of people here:__

*    A customer who wants to purchase the cars with less price , different body styles and wants to look for the drive wheel with this arrangement.

*    A dealer who wants to showcase the prices for the cars with different body styles and drive wheels.

*    As a data analyst, you have been given a task to visually show the __body-style and prices__ with respect to each __drive wheel__ selected.

*    So ideally you want to showcase this in the form of 2 interactive charts such as __pie chart__ and __bar chart__ on selection of drive wheel.

## Components of the item
1. Drive Wheel Type

    For the chosen Drive wheel,

      *  Pie Chart showing body style and price.

      *  Bar Chart showing body style and price.

    
Below is the key item,

*    Drive wheels


## Requirements to create the expected result

*    A dropdown menu: For choosing Drive wheel type
*    The layout will be designed as follows:
*    An outer division with two inner divisions (as shown in the expected layout)
*    One of the inner divisions will have information about the dropdown(which is the input) and the other one is for adding graphs(the 2 output graphs).
*    Callback function to compute data, create graph and return to the layout.

## To do:

1. Import required libraries and read the dataset
2. Create an application layout
3. Add title to the dashboard using HTML H1 component
4. Add a dropdown using dcc.dropdown
5. Add the pie chart and bar chart core graph components.
6. Run the app
