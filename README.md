
<h1 align="center">Bazauger</h1>
<p align="center">
  <a href="https://github.com/uploak/bazauger/blob/main/LICENSE" target="_blank">
    <img alt="license" src="https://img.shields.io/badge/License-GNU%20General%20Public%20License%20v3.0-ff2121" />
  </a>
</p>

<p align="center">A project aiming to predict market prices on Hypixel Skyblock's bazaar using Neural Networks!</p>

-----
Introduction
-----
This is a quick little project i've been working on for the past week that uses XXX neural networks to predict bazaar buy and sell prices. It could probably also predict buy and sell volumes and whatnot, but it probably won't be as accurate.

I don't exactly have a website for people to see the predicted prices and whatnot because i'm too lazy to set one up, so i've just left the `.h5` models under the output folder. Though, I do plan on creating an interactive demo soon enough.

How it was done
-----
Just like anyone other machine learning project, it's divided into 3 parts. That being, data collection, training, and testing. Data collection was by far the hardest part because of the amount of time and research I had to do in order to figure out a way to request and store the data for free.

  ### Data Collection
  -   Firstly, I just started off by creating a program that could request and store all the bazaar data into separate spreadsheets. This was pretty simple.
  -   Next, I needed a way to run the code pretty much 24/7 every hour for the next month or so, so that I could get a decent chunk of data. I originally thought of buying a Raspberry PI, adding the script there, and having it run at my house, but I was soon stopped by the realization of the amount of money I would need due to the shortage of Raspberry PIs (why is that even a thing). Luckily, after some digging, I found a platform called Heroku that let you run code on their servers for free 24/7. The catch was that there was a limited amount of hours per month I could run my code for, and that I couldn't store any files on there.
