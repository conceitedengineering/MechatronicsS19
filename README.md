# MechatronicsS19
<H1>HandCrank Week 1 </H1>
Making something that is simple and hand powered was the first project for Mechatronics. I enjoyed the challenge / freedom of not thinking about motors or complex control and figuring out a simple movement first. While the scope and time for this project was limited, I also wanted to use this opportunity to iterate on an older idea of a Lego kit of my own moving parts. The newer improvement being an attempt to copy the design of the mechanisms found on http://507movements.com/.
The outcome was surprisingly fast and robust. This method of observing a mechanism found online or elsewhere and attempting to convert to a cad file while seemingly simplistic but in the end worked with little time and fuss. For the future I would like to understand the simulation capabilities of Fusion360 a lot better than I do now. This would effectively eliminate my current temp of cardboard iteration, possibly saving lots of time and material wasted. For now I am quite happy with this process and intend on using it for project to come.

<H2>Method</H2>
I start out with a screenshot that I closely try and copy in fusion.
I then take the measurements from the copy and trudgen’s and even them out in a replica drawing.
Laser cut the test files in cardboard and use a pegboard system to identify the optimal position of the various parts.
Assemble, test and iterate.
Cut final parts, test with regular nuts first then move to locknut and grease to wrap up.

<H2>Tools needed</H2>
Adobe Fusion360(mostly free)
Access to Laser cutter
Nuts and Bolt of any size so long as your drawings reflect the right size.

<H2>Process Shots:</H2>

![Rilla1](https://user-images.githubusercontent.com/47313658/54501624-8e149380-48e3-11e9-8d85-d059e1a7e4ee.jpg)

![Rilla2](https://user-images.githubusercontent.com/47313658/54501587-5f96b880-48e3-11e9-8bc4-912f8ce14716.jpg)

<H2>Acknowledgments</H2>
	<p>•	http://507movements.com/ (Obvi)</p>
	<p>•	<a href="https://www.noisebridge.net/">Noisebridge</a> is a free(donation based, no one turned away) Hackerspace in the Mission.</p>

# HandCrank Week 2
Mostly just moving from early prototype cardboard and MDF to finished black plexiglass . 

![IMG_9544](https://user-images.githubusercontent.com/47313658/54502286-17799500-48e7-11e9-9a65-aa51f5e1fe4f.JPG)

![IMG_9547](https://user-images.githubusercontent.com/47313658/54502330-46900680-48e7-11e9-9665-90423741dc0b.JPG)

## Demonstration Video of end result

[link to video!](https://drive.google.com/file/d/1mSc1XzzPOMfCjuESsQyoCMMJZz72qq9C/view?usp=sharing)

# Mechanical Contraption Week 4

For this project I wanted to continue my seemingly neat approach to conceiving of and making complex moving parts. However I quickly found myself in a familiar place of asking, but why?
After a few days of pure contemplation and zero actions I suddenly came across the writings of Yuk Hui and found myself staring at a number of logs scattered by CCA. 
In his critique of Kant’s reductionist view of nature Hui elaborates on a Kantian view of nature and in essence the foundations of his Cosmopolitics.

>Consider Kant’s example of the tree from §64 of the Critique of Judgment. First, the tree reproduces itself according to its genus, meaning that it reproduces another tree. Second, the tree produces itself as an individual; it absorbs energy from the environment and turns it into nutrients that sustain its life. Third, different parts of the tree establish reciprocal relations with one another and thus constitute the whole.

He then Capps of with an incredible lesson about Dao & Chinese metaphysics

> What I love is Dao, which is much more splendid than my skill. When I first began to carve a bullock, I saw nothing but the whole bullock. Three years later, I no longer saw the bullock as a whole but in parts. Now I work on it by intuition and do not look at it with my eyes. My visual organs stop functioning while my intuition goes its own way. In accordance with the principle of heaven (nature), I cleave along the main seams and thrust the knife into the big cavities. Following the natural structure of the bullock, I never touch veins or tendons, much less the big bones!

I do not do the whole reading any justice and meerly pull out two striking quotes that had fuled this project. [Read the full thing!](https://www.e-flux.com/journal/86/161887/cosmotechnics-as-cosmopolitics/) Its free and awesome. Some familiarity with Kant and Hegel would pay off, otherwise ok!

## Method
For this project I resorted to my old ways of scraping together whatever I find to make thing move and work. 
Surprise surprise! this was a completely unworkable approach and I doubled down on the nonsense the more it failed. It took till the very end for me to learn my lesson and clean up my act. For instance ditching the first DC motor plus tire approach for a more predictable stepper motor and linkage. In the end I learned the value of strategic planing and design even though the artist within me is dying to staple-gun a bunch of shit together and pray it works.
## Documentation Videos

> coming soon!

# Final Proposal
This project builds upon an old project I briefly worked on and abandoned.
When I first met a contact mic, I was thoroughly impressed and confused how I had lived without hearing of these magical things.
My first few experiments involved no micro-controllers and were just an exploration of different materials’ capability to transfer vibrations. A few months later once I learned how to interface the Arduino with OSC enabled software a whole new world was opened up for me.
Following few experiments, I was part of a flash show in collaboration with TWR radio in SFAI and installed a visualization of the vibrational data from around campus. [link to project.](http://twr.sfai.edu/nvj.html)
I enjoyed this process but ultimately moved on. Fast forward to today and a few developments have caught my eye. The first is a fantastic new micro-controller I had a chance to play with at one of my jobs called the ESP32. Basically a beast packing a lot of processing power as well as WiFi and Bluetooth capabilities all on a $2 board!(Economies of scale) 
The second being some tools I had a chance to play with that make the process of creation and deployment of machine learning easy(ish).

Now, I’m thinking what if I had a network of Piezo pics in my home, attached to every surface. What if I then used ML to train my computer to discern between taping my fridge and scratching my cabinets. Basically the transformation of almost anything as an input device. I find this idea quite fascinating.
I could have sworn I saw a similar idea made a few months back but can’t seem to find it. I did find a few science papers on exactly what I’m talking about but so far no finished(ish) consumer available goods.

## Proposal
I would like to make a simple [Esp32](https://www.amazon.com/Espressif-ESP32-ESP32-DEVKITC-ESP-WROOM-32-soldered/dp/B01N0SB08Q) + [Piezo](https://www.adafruit.com/product/1740) mic circuit and use Machine Learning or similar [tools](http://www.wekinator.org/) to ‘teach’ a system various gestures.

For instance a user can attach this to their office / home desk and train the system to pick p a number of gestures such as light taps or rhythmic interactions and use say, a service like [IFTTT](https://ifttt.com/) to control various tasks from smart home automation to emailing colleagues.

The hardware part I have few fears about, in the end the large part of this product is going to be the software and I have a few leads in the right direction. The full extent of what is possible and what is not should manifest itself in the initial weeks of this project allowing me to adjust my goals or expectations accordingly.

## Initial Circuit plan
<img width="1039" alt="Screen Shot 2019-03-17 at 8 04 04 PM" src="https://user-images.githubusercontent.com/47313658/54504199-dfc31b00-48ef-11e9-9df9-926edf3dc195.png">

## Fake Code for aesthetic
```javascript
// Include Libraries
#include "Arduino.h"
#include "PiezoSensor.h"


// Pin Definitions
#define PIEZOSENSOR_PIN_POS	12



// Global variables and defines

// object initialization
PiezoSensor piezoSensor(PIEZOSENSOR_PIN_POS);


// define vars for testing menu
const int timeout = 10000;       //define timeout of 10 sec
char menuOption = 0;
long time0;

// Setup the essentials for your circuit to work. It runs first every time your circuit is powered with electricity.
void setup() 
{
    // Setup Serial which is useful for debugging
    // Use the Serial Monitor to view printed messages
    Serial.begin(9600);
    while (!Serial) ; // wait for serial port to connect. Needed for native USB
    Serial.println("start");
    
    
    menuOption = menu();
    
}

// Main logic of your circuit. It defines the interaction between the components you selected. After setup, it runs over and over again, in an eternal loop.
void loop() 
{
    
    
    if(menuOption == '1') {
    // Piezo Element - Test Code
    int piezoSensorVal = piezoSensor.read();
    Serial.print(F("Val: ")); Serial.println(piezoSensorVal);

    }
    
    if (millis() - time0 > timeout)
    {
        menuOption = menu();
    }
    
}



// Menu function for selecting the components to be tested
// Follow serial monitor for instrcutions
char menu()
{

    Serial.println(F("\nWhich component would you like to test?"));
    Serial.println(F("(1) Piezo Element"));
    Serial.println(F("(menu) send anything else or press on board reset button\n"));
    while (!Serial.available());

    // Read data from serial monitor if received
    while (Serial.available()) 
    {
        char c = Serial.read();
        if (isAlphaNumeric(c)) 
        {   
            
            if(c == '1') 
    			Serial.println(F("Now Testing Piezo Element"));
            else
            {
                Serial.println(F("illegal input!"));
                return 0;
            }
            time0 = millis();
            return c;
        }
    }
}

```
