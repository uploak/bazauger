How it was done
-----
Just like any other machine learning project, this one is divided into 3 parts. That being, data collection, training, and testing. Data collection was by far the hardest part because of the amount of time and research I had to do in order to figure out a way to request and store the data for free.

I'm not sure if anyone really cares, but the name for this project is a combination of the words Bazaar and Augur. Bazaar for the Hypixel bazaar, and Augur meaning predicition or something that will happen. Bazaar + Augur = Bazauger? Maybe Bauger or Baugur was a better idea...

### Data Collection
- Firstly, I just started off by creating a program that could request and store all the bazaar data into separate spreadsheets. This was pretty simple.
- Next, I needed a way to run the code pretty much 24/7 every hour for the next month or so, so that I could get a decent chunk of data. I originally thought of buying a Raspberry PI, adding the script there, and having it run at my house, but I was soon stopped by the realization of the amount of money I would need due to the shortage of Raspberry PIs (why is that even a thing). Luckily, after some digging, I found a platform called Heroku that let you run code on their servers for free 24/7. The catch was that there was a limited amount of hours per month I could run my code for, and that I couldn't store any files on there.
- Both of these were solved relatively quickly. For the limited amount of hours, I could just use their [scheduler](https://devcenter.heroku.com/articles/scheduler) or just build a (custom clock)[https://devcenter.heroku.com/articles/clock-processes-python]. For the file storage, I decided to just store it on google drive.
- All the code for this is included on this github repo.

### Training
- To be continued

### Testing
- To be continued

