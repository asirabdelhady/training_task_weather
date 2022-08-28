# weather



packages used:
    get
    http
    intl
    lottie
    simple_shadow

Asir Abdelhady: I created the Model classes that help receive the data from the api as well as 
the fetch class that fetch the result from the api url.

Saif Mohammed: I designed the UI and then coded the interface that will be receive from the model
classes that we created and represent the data.

Details:
This is a simple one screen app that shows the user the weather in a specific place, in this case
I chose the weather in Cairo since i live there.

We found a free api link that presents weather stats in any area. 
Then We used a http package to handle the url since we are changing the value of the city to be only
Cairo as well as the apiID. I used a function to fetch the weather info using the city name.

I then created a model class to receive the result of the fetch in json format.

Then I created the design of the UI in a separate dart file, imported the model dart file and started
to replace all the variables with all the data that came from the api like:
    id
    humidity
    country
    name
    description
    speed
    temp


This is what the app looks like:

![Weather page](https://user-images.githubusercontent.com/104396012/187096739-15122cd0-dd68-40c9-bf90-4edfb00e1874.jpeg)
