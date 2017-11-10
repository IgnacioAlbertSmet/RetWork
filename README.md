# RetWork

RetWork is a project which aims at helping ameliorate Singapore’s aging crisis with the use of information technology. The solution consists in a mobile app and a website that provide a job portal especially targeted for the elderly and/or retired citizens. Here we present the main features as well as the background of the project.

MOVER DONDE PROCEDA: , in order to make job opportunities easily accessible to them. , and offer them the chance to incorporate back to the workforce.

## Motivations

Singapore’s demographics are now in a historical turning point: the population pyramid is experiencing a fast inversion. In the upcoming years, Singapore’s people will be getting old faster than those of any other nation, with the added effect of having a slower population growth. This poses an imminent demographic challenge to the country’s economy, which is growing into an important concern. The government is already applying a number of initiatives to ensure that their system can stay economically and socially sustainable. As a team of millennial engineers attending the GovTech Singapore Hackathon 2017, we decided to tackle this problem by developing an effective, yet accessible, technological solution: RetWork.

## Concept


ADAPTAR TODO:::
A smartphone app guides the user through several recipes, coming from different parts of the world and having diverse levels of difficulty. Step by step, the user receives feedback about his or her cooking technique in a fun and interactive way, allowing him or her to quickly be able to cook delicious food.

A small device is attached to the cooking pan or pot, and measures several parameters related to the food being cooked, such as temperature, CO2, or vibrations. This data is sent over Bluetooth to the smartphone, which analyses them, and convert them into an intuitive feedback. The device is removable and discreet, so it does not bother the user.

<p align="center">
	<img src="doc/Technical_slide.jpg" width="750"/>
</p>

## Hardware Device

ADAPTAR TODO:::
Main features:
* Three sensors measuring temperature, CO2 concentration, and acceleration
* Status LEDs
* Battery powered
* Optimized power consumption: BLE communication, low-power microcontroller, carefully selected sensors...

Early prototype:
* Arduino UNO
* Dallas DS18B20 thermocouple 
* InvenSense MPU-6050 IMU
* Bluetooth HC-05 module
* Green, Orange and Red LEDs controlled by the smartphone

## Mobile App

ADAPTAR TODO:::
Main features:
* Various recipes (levels) accessed on a remote database
* Online account management
* Score and achievments sharing with friends
* Real-time communication with the device
* Feedback such as: "increase/decrease temperature", "give a stir" or "food is burning"

The early prototype was developed for Android with Unity game engine and featured one full recipe. It is already available for feedback on [Google Play Store](https://play.google.com/store/apps/details?id=com.SevaneGames.RetWork).

<p align="center">
	<img src="doc/App_ui_2.png" height="400">
	<img src="doc/App_ui_1.png" height="400">
</p>

## What comes next

ADAPTAR TODO:::
Additional features that could potentially be implemented:
* Allow the user to rate recipes and suggest improvements, use machine learning to update the database based on the score given by many users
* Advanced feedback to the user using fuzzy logic
* Automatic ingredients ordering to local groceries with home delivery

## Awards

This project won the second place of the GovTech Singapore Hackathon 2017, a 3-days event focused on idea development and implementation.

## Credits

* Mobile app development: Alexis Pomares Pastor
* Website development: Andres Lulli
* Business plan and speech: Ignacio Albert Smet
