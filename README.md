# weather

packages used:
    get
    http
    intl
    lottie
    simple_shadow


This is a simple one screen app that shows the user the weather in a specific place, in this case
I chose the weather in Cairo since i live there.

I found a free api link that presents weather stats in any area. 
Then i used a http package to handle the url since we are changing the value of the city to be only
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
