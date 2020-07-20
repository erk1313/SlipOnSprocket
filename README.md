### Slip-On Sprocket for the Early-Rider 16" Belt-Driven Bicycle

The Early Rider Belter/Seeker 16 comes with a tall gear ratio that's tough for hilly areas or timid riders.  The easiest thing is to buy a bike with a chain with a replaceable sprocket, but what's the fun in that?! This project is for a rear sprocket that slips over the existing 22t sprocket.

Here's how the gain ratio of popular 16" bikes stack up.  Lower ratios make it easier to climb hills, while higher ratios limit top speed on straight-aways.  The Early Rider comes with a 46t front chainring and a 22t rear sprocket, making it the highest gain ratio on this list

### Gain Ratios of 16" bikes*
| Bike             | Gain Ratio | Gear Ratio  | Crank Length  | TIRE OD | Notes|
|------------------|------------|-------------|---------------|---------|------|
|Early Rider (Seeker)|4.05      |46/22t **STOCK**|105mm       |407mm**  ||
|Spawn Yoji        |3.97        |24/12t       |102mm          |405mm*   | |
|Prevalo Alpha     |3.80        |25t/14t      |**95mm**       |403mm*   |Gain Ratio listed on [Prevalo](https://prevelobikes.com/products/alpha-two) |
|Early Rider (Hellion)|3.70     |30/15t       |110mm          |407mm**  ||        
|Woom 3            |3.54        |25/15t       | **95mm**      |403mm*   ||
|Islabike Cnoc     |3.52        |25/14t       |102mm          |401mm*   ||
|Priority Start    |3.38        |?            |?              |?        |Gain Ratio listed on [Priority Start](https://www.prioritybicycles.com/products/startfw2) |
|Commencal Ramones |3.12        |28/16t       |114mm          |407mm**  ||
|Cleary Hedgehog   |3.09        |25/16t       |102mm          |404mm*   |Flip-flop hub with 14t would result in Gain Ration of 3.54 (like a Woom 3)|
|Early Rider (Seeker)|2.97      |46/30t **CUSTOM**|105mm      |407mm**  ||
|Early Rider (Seeker)|2.79      |46/32t **CUSTOM**|105mm      |407mm**  ||

(*) *Tire OD estimated based on tire width (not very accurate)*

(**) *Tire OD measured by marking one circumference, then dividing by pi.  YMMV...If you own one of these bikes, please measure and update the tire diameter :)*

> *Gain ratio?* You mean gear ratio?  
[Gain ratio](https://prevelobikes.com/blogs/news/bicycle-gear-ratio-gear-inches-and-gain-ratio) takes into account the size of the tires and the crank length, which factor in to how easy it is to pedal. Thanks Prevalo, for your awesome [Gain Ratio Calculator] (https://prevelobikes.com/blogs/news/gear-ratio-gear-inches-gain-ratio-calculator).

### Early Rider - Stock Specs
Here are the specs that determine the gain ratio on the stock bike:
* Front Chainring: 46t
* Rear Sprocket: 22t
* Crank: 105mm
* Tire Diameter: 406.8mm (Vee-Crown Gem 16" x 2.25" width).  
Plugging that in the gain ratio calculator yields 4.05.  Suprisingly, the Spawn Yoji is also high on the list, even though it is meant for the bike park.  

### Lowering the Gain Ratio with a New Rear Sprocket
With a belt drive, you can't just add a link in the chain to make it longer. The stock belt is a 840mm long and the next size up is 880mm long.
>Stock belt: Gates HTD series, which is a round tooth profile.  840-8M-12 translates to 880mm long; 8mm pitch (spacing between teeth); 12mm width
 
If we want to keep the distance between the front and rear axles the same, then the belt length is going to dictate the number of rear teeth (assuming the front chainring stays the same).  With the new belt length of 880mm, the rear sprocket needs to be 32t.  We could cheat it a bit, by allowing the rear axle to slip back.

|Gear Ratio     |Belt Length  |Axle Spacing*  |Change in Spacing from Stock|
|---------------|-------------|---------------|-----------------|
|Stock 46/22t   |840mm        |282mm (11.11in)|                 |
|46/32t         |880mm        |283mm (11.16in)|+0.05            |
|46/31t         |880mm        |285mm (11.23in)|+0.12            |  
|46/30t         |880mm        |287mm (11.31in)|+0.20            | 
* *Axle spacing is based on the theoretical pitch diameter.  It seems that Early Rider varied from this, which would have effected the actual axle spacing.

>Solidworks figures all this out for me... Here is an image of the stock setup.
<img src="https://i.imgur.com/nTLmv0j.png" height="100"/>

With the 32t slip-on sprocket and a newly tensioned belt, I had to move the rear wheel back about 1/16" (as expected).  This is great if you can live with the really low gain ratio.  For now, it works beautifully for my son.  He can now climb hills to get around all by himself.

With the 32t setup, I have about 0.18" more travel in the horizontal dropout.  So one might be able to accomodate the 30t or 31t sprocket. it would require repositioning the rear brake pads, which are also near their limit.  If we get some interest in another order, I can try to mock up what the brakes would look like with the rear wheel shifted.

### Photo Gallery
<img src="https://i.imgur.com/5nRr9sL.png" height="100"/>
<img src="https://i.imgur.com/Bt8BAmj.png" height="100"/>

[Video of a 4-yr with a 32t Slip-on Sprocket installed](Photos/SlipOn_46-32t.mp4)

### Revision Notes
*Rev-A*: The first run was a batch of 3 parts.  The clearance between the existing sprocket and the matching interior of the slip-on sprocket was 0.005" (radially). This fit perfect!  All three parts were tested on my 2020 Seeker, as well as an old hub I bought off a member, which had a screw on hub instead of the current spline. I was actually surprised.  YMMV as I used a cheap Chinese fabricator with no specified tolerance on machining (to keep cost down).  They inner face was also bead blasted, which could have helped.  If needed, the design might fit more universally with a 0.007"-0.010" clearance and making up the slop with a expandable pin. 

*Rev-1.0* (unreleased - see Develop branch): Changed clearance for the internal teeth from 0.005" to 0.010" for better fit.  Added tappd set screw (10-32 x .375") to retain the sprocket.
