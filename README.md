# python_api_challenge
Module 6 challenge for Morgan Bee

In this challenge, I used all of the class activities from Module 6 to help guide my code. They were extremely helpful for API requests and making sure that I had correct formatting for each line of code so that it all ran successfully. 

I also utilized the Xpert Learning Assistant extensively. That tool helped me understand the following lines of code, which I added to my assignment: 
    - defining and calling a function in Python using def, returning an output, and then calling it later in your code
    - understanding the concept of r^2 and why it is important for the relationship between two variables
    - using "&" to filter for multiple values in an existing DataFrame
    - creating a copy of a dataframe using .copy() to create a new DataFrame without disrupting the previous DataFrame
    - troubleshooting the "filters" portion of "params" when making a request for Geoapify data. I learned that I needed to take the value of each row of my DataFrame rather than the whole column in order to make my code work. 
    - adding labels to the hover message in VacationPy, using hover_cols=[]

One final note - in the VacationPy notebook, some of my "ideal locations" returned "no hotel found" when given the radius of 10000 meters. I double checked to make sure the code was running properly by increasing the radius, and when I did so, I was able to return hotels for most of the cities on the list. I believe some of the cities found may just be very remote with truly no hotels around. For the purpose of the assignment and to fulfill the requirement, I changed the radius back to 10000 for submission of the challenge. 