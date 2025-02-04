## what is a Repaircafe  


---

### by Jogi 

![Jogi](yogi_bear-head.jpg)

---

### Microcontroller Talks

1. **Jogi:** Introduction, history incl 6502, 80C166, via Arduino to Raspi Pico, [Code](https://github.com/jogi-k/micro-controller-slides/tree/gh-pages) and [Slides](https://jogi-k.github.io/micro-controller-slides) 
2. **Jogi:** MC-based learning-platforms, Micro:Bit & Calliope, [Code](https://github.com/jogi-k/micro-controllers-part2/tree/gh-pages) and [Slides](https://jogi-k.github.io/micro-controllers-part2)
3. **Felix:** ESP8266- and EPS32-Universe, [Felix](https://github.com/fliiiix), Lightning Talks-Repo 
4. **Jogi:** More Pi Pico, Environments, Comparison, Eco-System, [Code](https://github.com/jogi-k/micro-controllers-part4) and [Slides](https://jogi-k.github.io/micro-controllers-part4)
5. **Jogi:** usecase RLX-Testfarm, making use of [RubberJogi OSS](https://github.com/jogi-k/RubberJogi), Lightning Talks Repo

---

![Board Turbine](./pics/Turbine_Vorstand.jpg)

---

## Sometimes: Spare-Time 

* Working in a ["Maker-Space"](https://www.turbine-brunnen.ch)
* Member of the Board
* Responsible for IT, Webpage, etc
* Organizing Soldering-Events for Kids
* Programming-Courses for kids (see Micro-Controller-Talks II :-) ) 

---

![Makey Soldering](./pics/Makey_Loeten.jpg)

---

![Programming Kids](./pics/Programming_Kids.png)

---

## Sometimes: Spare-Time 

* ...
* ... and more ...
* and : Repair-Cafes 

---

## what is a Repaircafe ? 

---

## Rather easy concept

### We connect 

* People with defect objects 
* with 
* People doing repair as hobby and for free 

---

## Thanks

## Q & A 

---

# Topics

* History 
* Where ?
* How ? 
* What ?
* Why ?
* Conclusion 

---

# History

---

## First Repair Cafe

### Ever 

#### Sunday, 18-Oct-2009

#### Amsterdam / Netherlands

#### Oct 2024 : 15th Birthday

#### [Video 15 Years](https://www.youtube.com/watch?v=hV0nljoAyJk )

---

### Anouncement


![First_Repaircafe_Amsterdam.png](./pics/First_Repaircafe_Amsterdam.png)

---

### Martine Postma


![Martine_Postma_1.png](./pics/Martine_Postma_1.png)

---

### First Repair Cafe in Switzerland :  

* 2013: Roger Fleury from Thun saw Repair-Cafes in Netherlands 
* decided to organize something similiar at home. 
* being himself not a repair-guy, he did not find others
* idea was not suceessful
* In 2014 he was contacted by [Konsumentenschutz](https://www.konsumentenschutz.ch) 
* together : very first Repair Cafe in Switzerland
* In Thun on 16-Aug-2014 (around 200 visitors , 71 objects, 44 repaired) 
* [Source: Repair-Cafe Thun](https://repaircafe-thun.ch/die-geschichte/)


---


### First Repair Cafe in Brunnen

* The very first Repair-Cafe we organized in our [Maker-Space](http://www.turbine-brunnen.ch) 
* was on 20-Oct-2018   
* this was also the first birthday of our Maker-Space
* (we gifted ourselves a rather expensive Laser-Cutter ...)

---


![Poster_Repaircafe_Brunnen_2018.jpg](./pics/Poster_Repaircafe_Brunnen_2018.jpg)


---

### already in 2019

![Team Brunnen 2019](./pics/Team_Brunnen_2019.jpg)

---


## Since then

* Every year : 3 or 4 Repair Cafes
* Always saturdays
* Also during Corona-Pandemic
* Repairing with open windows
* Facemasks
* And the reception outside


---

![Receiption_2020_Corona.jpg](./pics/Receiption_2020_Corona.jpg)

---

# Where ?

---

### Innerschwyz

![repaircafes-around-rotkreuz.png](./pics/repaircafes-around-rotkreuz.png)

---

### Our Repair-Cafe

![repaircafe-brunnen.png](./pics/repaircafe-brunnen.png)

---

### Basel  

![repaircafes-basel.png](./pics/repaircafes-basel.png)

---

### Switzerland :  200 Repaircafes

![repair-cafes-switzerland.png](./pics/repair-cafes-switzerland.png)

---

### St. Cugat / Barcelona  

![repaircafes-in-barcelona.png](./pics/repaircafes-in-barcelona.png)

---

### USA

![repaircafes-in-usa.png](./pics/repaircafes-in-usa.png)

---

![Worldwide_Movement.png](./pics/Worldwide_Movement.png)

---

# How ?

---

## Some principles everywhere

* Repair itself has to be free
* Repairer has to be volunteer
* No professionals 
* Material can be charged
* Cafe, Cake etc can be charged
* Guests are allowed to donate

---

## How it works I

* Guests come and bring their objects
* We have a lot of tools, but also:
* Repairers bring their tools
    * Some a pocket-knife 
    * some a car full of electronic equipment
* While guests waiting: drink coffee, eat cake
* we try to limit the time to 30-40 mins

---

## How it works II

* Still best:
    * encourage guest to repair themselves
    * with help of repairer
* At least:
    * guests "have" to stay
    * Its **not** drop and come back later 
    * They need to tell the problem
    * And to say yes/no e.g. on opening/cracking ...

---


## Experimenting with structure I

* Introduced Repair-Evening
    * For stuff where we had hope
    * but expected time >> 30-40 mins
    * or material was missing
    * some weeks later, w/o any guests, just nerds :-)

### Success, we kept that

---


## Experimenting with structure II

* Introduced two repair-queues 
    * One, where the people were waiting 
    * One, for people who didn't have time

### Fail !

---

## Why Fail ?

* Most guest did not know the basic principle
* We couldn't tell them how long to wait
* dropped their objects
* Repairers could not ask about the problem
* Repairers could not clarify about "cracking"
* less repaired objects ...
* Unhappyness on all ends ... 

---

## Solution 

* Digitalised the process 
* Self-Registration of guests (3 Laptops)
* Registration-office operates Kanban-Board 
* Dashboard for guests with estimated waiting-time
* Kanban-Board (ro) for repairers
    * showing them the queue-length
    * "forcing" them to stop latest after 30-40 mins
* Web-based, [open-source](https://github.com/jogi-k/repaircafe) (Python, Flask, Bootstrap...)
* A lot of improvement-ideas (as soon as I have time) ...

---

### The Dashboard

![Dashboard ](./pics/dash_board_new.jpg)

---

### The Kanban Board

![Kanban Board ](./pics/kanban_board_II.jpg)

---

### Next level :-)

![Next level: Pager](./pics/queuing_next_level.jpg)


---

# WHAT ?

---

* We basically "try" everything
* Electronics 
* Household applicances
* Clothes
* Bicycles
* Computers, Mobile Phones
* Coffee-Machines ( I hate it...)
* Childrens toys

---

![Image_20241019_180455_115.jpg](./pics/Image_20241019_180455_115.jpg)

---

![Image_20241019_180455_172.jpg](./pics/Image_20241019_180455_172.jpg)

---

![Image_20241019_180455_242.jpg](./pics/Image_20241019_180455_242.jpg)

---

![Image_20241019_180455_312.jpg](./pics/Image_20241019_180455_312.jpg)

---

![Image_20241019_180455_385.jpg](./pics/Image_20241019_180455_385.jpg)


---

![DetailsRepairing_III.jpg](./pics/DetailsRepairing_III.jpg)

---

![DetailsRepairing_II.jpg](./pics/DetailsRepairing_II.jpg)


---

![RemoteControl_III.jpg](./pics/RemoteControl_III.jpg)

---

# A lot of stuff:

* "Main" difficulty is to open it

---

![Spend-time-find-out.png](./pics/Spend-time-find-out.png)

---

![Open_hope_no_crack.png](./pics/Open_hope_no_crack.png)

---

![Screwdriver long](./pics/screwdriver_extralong.jpg)

---

# WHY ?

---

## Why are people doing this ?

* They/We are nerds and
* We like to fix stuff
* We want to make people happy
* We want to improve **xxx** a little
* xxx : the world, ourselves, ... 
* Avoid garbage
* Environment / Sustainability 


---

# Repair-Month Oct

*  2024 
*  more than 50 Repaircafes in switzerland
*  more than 1300 objects
*  Around 65-70 % success


---


 
![statistic_oct_2024.png](./pics/statistic_oct_2024.png)



---


## Greater movement

* [Repairability - Guide by iFixIt](https://www.ifixit.com/repairability)
* France :  [since 2021 Repair-Index](https://www.economie.gouv.fr/particuliers/tout-savoir-indice-reparabilite)
* European Law 2024 : [Right to repair Press](https://www.europarl.europa.eu/news/de/press-room/20240419IPR20590/recht-auf-reparatur-reparieren-einfacher-und-attraktiver-machen)
* European Law 2024 : [The Law itself](https://eur-lex.europa.eu/eli/dir/2024/1799/oj/eng)

---

![iFixIt-Repair-Index.png](./pics/iFixIt-Repair-Index.png)

---

## Companies 


* Fairphone 
* Framework Laptop
* Philips designing Coffee-Machine
* Even Apple : [iPhone 16 Battery removal](https://www.macrumors.com/2024/09/23/ifixit-iphone-16-teardown/)  
* more and more are coming

---

![iFixt-Principle.png](./pics/iFixt-Principle.png)


---


![Fairphone_5_Repairindex.png](./pics/Fairphone_5_Repairindex.png)

---

![Fairphone-5-disassembled.jpg](./pics/Fairphone-5-disassembled.jpg)

---

![Framework-Laptop.png](./pics/Framework-Laptop.png)

---

# Conclusion

--- 

# Please help !

## Visit a Repair-Cafe

## Engage !

---


![Next Repaircafe Schwyz Museum](./pics/Next-Repaircafe_Schwyz.png)

---

## Links 

* [Repaircafe Switzerland](https://www.repair-cafe.ch/wissen/informationen/)
* [Konsumenten-Schutz Schweiz](https://www.konsumentenschutz.ch/)
* [Repaircafe International](https://www.repaircafe.org)
* [iFixIt Repairability](https://www.ifixit.com/repairability)
* [EU Right to repair](https://eur-lex.europa.eu/eli/dir/2024/1799/oj/eng)

---

### Resources 

* This talk [git-repo sources (branch gh_pages)](https://github.com/jogi-k/lightning-talk-repaircafe/tree/gh-pages/)
* This talk [as slides on the web](https://jogi-k.github.io/lightning-talk-repaircafe/)

* Later: The slides on lightning-talk-repo


---

### The END 

![Jogi](yogi_bear-head.jpg)


