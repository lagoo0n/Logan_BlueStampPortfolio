# Omni Wheel Robotic Car
Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Logan C. | Dublin High School | Electrical Engineering | Incoming Junior

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone
For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Second Milestone
For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# First Milestone

The most important part of this whole project is to build the car and getting the omniwheel car to move in every direction. For my first milestone, I built up the whole car and implemented the code into the arduino to get it to start moving. One change that I did make was that I replaced the battery pack that had originally came with the kit. This change was made as a safety precaution as the batteries that would be used in the previous battery holder were lithium batteries. A few challenges that I had faced was putting the wires together. There was a lot of wiring required in order to get all the functions on the car to work. Another challenge that I had faced was getting all the parts tightened on my car. I had to constantly go back to certain parts on the car, especially the wheels. My plan going forward is to make slight modifications that can utilize the cars ability to move in any direction and also be able to control where it can go on command using bluetooth.

<iframe width="560" height="315" src="https://www.youtube.com/embed/ESY4f17Ovg0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

![Headstone Image](Screenshot 2023-06-23 121200.png)

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Car Chassis | Base of the omniwheel car | $7.99 | <a href="https://osoyoo.store/collections/parts-for-blue-mecanum-wheel-robotic-car-kit-for-arduino-mega2560-model-2021006601/products/model-2021006600-blue-mecanum-wheel-robotic-car-acrylic-chassis?variant=40715880333423"> Link </a> |
|:--:|:--:|:--:|:--:|
| Gear Motor | Turns the wheels on the robot car | $5.99 | <a href="https://osoyoo.store/collections/parts-for-blue-mecanum-wheel-robotic-car-kit-for-arduino-mega2560-model-2021006601/products/tt-motor-with-wire-and-connection-for-arduino-v2-0-robot-carmodel-2016013200m-1?variant=31648986857583"> Link </a> |
|:--:|:--:|:--:|:--:|
| Mecanum Wheels | Wheels used for the car | $19.99 | <a href="https://osoyoo.store/collections/parts-for-blue-mecanum-wheel-robotic-car-kit-for-arduino-mega2560-model-2021006601/products/model-2021006600-blue-mecanum-wheels-60mm?variant=40715901698159"> Link </a> |
|:--:|:--:|:--:|:--:|
| Mega2560 Arduino Board | Arduino board used to upload arduino program into | $20.69 | <a href="https://www.amazon.com/SunFounder-ATmega2560-16AU-Board-Compatible-Arduino/dp/B00D9NA4CY"> Link </a> |
|:--:|:--:|:--:|:--:|
| Osyoo Wi-Fi Shield | Allows the arduino to connect to the internet using WiFi | $12.99 | <a href="https://osoyoo.store/products/esp8266-wifi-shiled-osoyoo-wifi-internet-of-things-learning-kit-for-arduino-uno?variant=31955252215919"> Link </a> |
|:--:|:--:|:--:|:--:|
| Osyoo Model Y 2.0 Motor Driver Module | Connects the motors to all other systems in the car | $19.98 | <a href="https://osoyoo.store/products/products-model-y-motor-driver-board-for-arduino-robotic-car-kit-model-2021006600?variant=41034891231343"> Link </a> |
|:--:|:--:|:--:|:--:|
| Obstacle Avoidance Sensor | Sensor used to locate where objects are | $3.50 | <a href="https://osoyoo.store/collections/parts-for-blue-mecanum-wheel-robotic-car-kit-for-arduino-mega2560-model-2021006601/products/ir-obstacle-avoidance-module-for-arduino-v2-0-robot-carmodel-2016000400?variant=31648429015151"> Link </a> |
|:--:|:--:|:--:|:--:|
| Tracking Sensor Module | Can detect the color of an object | $9.99 | <a href="https://osoyoo.store/collections/parts-for-blue-mecanum-wheel-robotic-car-kit-for-arduino-mega2560-model-2021006601/products/5-channel-tracking-sensor-for-osoyoo-model-3-robot-learning-kit-v2-model-2020001700?variant=31930528497775"> Link </a> |
|:--:|:--:|:--:|:--:|
| Ultrasonic Sensor Holder and Ultrasonic Sensor| Senses ultrasonic energy waves and is connected to the motors | $9.99 | <a href="https://osoyoo.store/collections/parts-for-blue-mecanum-wheel-robotic-car-kit-for-arduino-mega2560-model-2021006601/products/ultrasonic-sensor-and-ultrasonic-sensor-holder?variant=32077243809903"> Link </a> |
|:--:|:--:|:--:|:--:|
| SG 90 Servo Motor | Rotates the ultrasonic sensor to detect objects | $7.99 | <a href="https://osoyoo.store/products/micro-servo-sg90-blue-for-arduino-v2-0-robot-carmodel-lacc200610?variant=31648847560815"> Link </a> |
|:--:|:--:|:--:|:--:|
| Voltage Meter | Gives the amount of volts going through the car | $6.99 | <a href="https://osoyoo.store/products/voltage-meter-for-arduino-v2-0-robot-carmodel-2017005300?variant=31648871121007"> Link </a> |
|:--:|:--:|:--:|:--:|
| LED Light | Light placed in the front of the car for better vision | $8.99 | <a href="https://osoyoo.store/collections/parts-for-blue-mecanum-wheel-robotic-car-kit-for-arduino-mega2560-model-2021006601/products/led-lights-for-blue-mecanum-wheel-robotic-car-kit-for-arduino-mega2560-model-2021006600?variant=40715976474735"> Link </a> |
|:--:|:--:|:--:|:--:|
| Battery Pack | Holds the batteries that power the entire car | $1.80 | <a href="https://www.amazon.com/Vanki-Battery-Holder-Case-Leads/dp/B073XC52BG/ref=sr_1_3?keywords=5%2Baa%2Bbattery%2Bholder&qid=1687379525&sr=8-3&th=1"> Link </a> |
|:--:|:--:|:--:|:--:|
| AA Batteries | Powers the entire car | $9.73 | <a href="https://www.amazon.com/AmazonBasics-Performance-Alkaline-Batteries-20-Pack/dp/B00NTCH52W/ref=sr_1_5?crid=2P2IO9C1C9G8U&keywords=AA+battery&qid=1687379629&sprefix=aa+battery%2Caps%2C155&sr=8-5"> Link </a> |
|:--:|:--:|:--:|:--:|


# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
