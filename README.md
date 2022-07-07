# weather

packages used:
    get
    http
    intl
    lottie
    simple_shadow

This was a team effort by Asir Abdelhady, ID:77920 and Saif Mohammed, ID:77690

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


## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
