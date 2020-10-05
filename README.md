# audflexbutok.github.io
CS 4331 Virtual Reality Project 1

[Web Based Application](https://audflexbutok.github.io/#)

[Source Code](https://github.com/audflexbutok/audflexbutok.github.io/blob/main/index.html)

[Assets](https://github.com/audflexbutok/audflexbutok.github.io/tree/main/assets)

[Video Presentation: Duration - 2 mins 18 seconds](https://www.youtube.com/watch?v=LPSFmtwnRBE&t)

[Video Demo (for readme.md): Duration - 50 seconds](https://www.youtube.com/watch?v=C2NTOvv4vPg)

# Description
The goal of this project was to create a VR environment that reflected a change brought about by the COVID pandemic. Since this project was web-based using A-Frame, HTML was utilized.

# Getting Started - Layout
I created a layout of the floorplan in Microsoft OneNote. This plan also gave me an idea of the models that I needed to make and acquire for my VR environment. Some of this was adjusted for the final product. For example, I removed the kitchen to avoid having to place more models and have a lower load time and framerate.

![](/images/SummaryReport/layout.png)

# Biggest Issues & Challenges 
 Most of the models that I made myself include textures or properties that are not easily renderable within A-Frame. I unfortunately had to make sacrifices in the quality of these models in order to keep the load time and framerate reasonable. One of these models was a window, which had really awesome transparency and reflection so it looked just like glass. After some troubleshooting, I was able to make it look decent within the A-Frame environment, but it reduced the framrate so significantly that any interaction was useless.
 
 I also had issues with toggling the visibility of the objects for "COVID" mode. I ran across several ways to implement this feature, but the easiest was the event-set__ method.
 
 I originally loaded in some really neat coffee bags that were arranged very nicely on the shelf between the booths and espresso machine, and they were able to be picked up. Unfortunately, these models were high-poly and made my project load about twice as slow as it did without them. I was unable to find a low-poly replacement that was free, so I made the decision to delete them since I had other objects that were able to be picked up and were also low-poly.
 
# Models
I used gltf models as stated in the Project 1 
 
# Contributors
This project was entirely individual and created by Audrey Cooper.

# Features
When you first enter the scene, the coffee shop has chairs, cups, and tables. Upon clicking the red "COVID" button, the coffee cups and chairs disappear to indicate the emptiness of the shop during the lock-down. Note that the tables are not removed because the shop remained open! The tables were left out specifically to make us look "more open" rather than having an entirely empty dining room. The chairs were removed to discourage seating and make more room for social distancing.

![](/images/SummaryReport/actions.png)

![](/images/SummaryReport/covidmode.png)

By clicking the blue button, you can revert back to the original "pre-COVID" mode, where there are chairs and coffee cups on the table.

![](/images/SummaryReport/pre-covidmode.png)

When clicking on the cash register, you will find that it makes a "cha-ching!" noise. This is accurate as our point-of-sale system makes the same noise when cashing out a sale.


![](/images/SummaryReport/counter.png)

The cups on the tables can also be picked up and "thrown" using the scroll wheel on a mouse. There are not actual physics attached, so the cups will just stay wherever they are put upon the release of the right-click mouse button.

![](/images/SummaryReport/cup.png)

# Unique Models
*main counter where the espresso machine and cash register are*
![](/images/SummaryReport/countermodel.png)

*shelf for creating extra low-poly counter space*
![](/images/SummaryReport/shelfmodel.png)

*octagon table found specially at J&B*
![](/images/SummaryReport/tablemodel.png)

*windows*
![](/images/SummaryReport/windowmodel.png)

*shelf for holding merchandise and bags of coffee*
![](/images/SummaryReport/bookshelfmodel.png)

# Assets & Images Reference
[Barstool](https://sketchfab.com/3d-models/chair-3eea733e04684fd981801a29974792fd)

[Ceiling Lamp](https://sketchfab.com/3d-models/sapphire-small-ceiling-lamp-98237-82bc5c6dd4bf49818aa7f44c505e9584)

[Hanging Bar Lamp](https://sketchfab.com/3d-models/lamp-02-lowpoly-0f5519beb6644e5ea714055382c20d5f)

[Chairs](https://sketchfab.com/3d-models/low-poly-chair-59a3a516a13f46d3be7ec7da587b4b6d)

[Tables](https://sketchfab.com/3d-models/table-01-lowpoly-pbr-texture-ebe332e891cc485eb79f15c6f49ab261)

[Cash Register](https://www.turbosquid.com/3d-models/cash-register-caja-registradora-3d-model-144079)

[Cash Register Sound](https://www.wavsource.com/sfx/sfx.htm)

[Bicycle](https://www.cgtrader.com/free-3d-models/vehicle/bicycle/bicycle--17)

[Espresso Machine](https://sketchfab.com/3d-models/commercial-coffee-machine-bab05bc7805d4b0dbc2cdcbb48441956)

[Booths](https://www.cgtrader.com/free-3d-models/interior/living-room/bench-with-raised-back)

[Wood Ceiling](https://previews.123rf.com/images/natthanim/natthanim1710/natthanim171000017/87804145-plywood-surface-in-natural-pattern-with-high-resolution-wooden-grained-texture-background-.jpg)

[Brick Walls](https://i.pinimg.com/originals/65/23/6e/65236ef31bda2d8b74096b6f7ec82f03.jpg)

[Concrete Floors](https://3.bp.blogspot.com/-QOJgDm7gIek/VhrwWRL3i_I/AAAAAAAAIZA/fASX3UgfGUM/s1600/%2528CONCRETE%2B11%2529%2Bgranite%2Bwall%2Bsmooth%2Bdirt%2Bpillar%2Btexture.jpg)

[SkyBox](https://www.flickr.com/photos/devilgorgor/50413671191/in/pool-equirectangular/)

