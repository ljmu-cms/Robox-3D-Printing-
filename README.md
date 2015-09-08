# Robox 3D Printing

### Resources and knowledge base repo for the School's [Robox][r] 3D printer
[r]: http://www.cel-robox.com/.

##Getting started 
- Log on to the desktop computer with your user credentials.
    - Alternatively [download the software][d] to your laptop computer (Mac, Linux and Windows available).
- Ensure the USB is plugged in to the computer you are using.
- Turn the Robox on.
    - There is a rocker switch at the back on the side that holds the reel of filament.

##Printing
1 Run the Automaker software on your computer.
    
    - A virtual printer should appear in a tab labeled "Status".
- If the door is not open click "Unlock Door".
- Remove any debris plastic from the environment.
- Clean the PEI bed with isopropyl.
- Close the door.
2 Click the "+" next to the status tab.
- Click either icons that read:
    - Add model
    - From cloud (requires an [account][mmf])
- Move your model so you are happy with it's placing.
    - Use the "Transform" section in the left pannel to rotate the x-axis and scale your model.
    - Use the "Lay flat" command and hand to select a side to change either z or y co-ords to x co-ords.
3 Click "To settings"
    - Use the sliders in the left panel to adust the print quality.
    - Click "Make".
    - You will return to the "Status" tab. 
- The software will slice the model accordingly to create layers, the amount of layers and the print time will be relayed to you in the Status tab you were returned to.
4 Set "Speed x" in the left panel to 0.5 with the slider.
   - Leave this set at 0.5 if your model is intricate.
- The print will begin when all components reach their target temperatures, details of which are relayed back to you in the panel in the left panel of the Automaker software. It will complete after the final layer has been printed.
- After the first five layers set the "Speed x" slider back to 1, increase it if your model is simple (max speed 1.5).
5 When the print head has stopped allow the environment to cool and the door will eventually unlock when it is safe.
- Use the carving tools to prise the print object from the PEI bed.
- Give the nozzles a scrub with some towel (we do need to get a decent brush for this!).
- Turn the printer off if you're finished with it.

##General know how
- Filament reels carry a microchip this enables the [Robox Software][d] to identify and configure the printer environment for use (extrusion).
- A mechanism, known as an extruder sits behind the the reel. The extruder feeds the filament through Bowden tubes into the print head's needle valves which are encased by Daal nozzles. The nozzles are heated above 200 degrees and open and close regulating the flow of viscous material onto a PEI bed which is heated to over 100 degrees. This process is known as extrusion.
- ABS filament absorbes moisture so ensure your hands are clean if you are handling material (eg [ejecting material][er]).
- The PEI bed is warped! You will get better results if you arrange your models in the corners of the bed. That said all corners are not equal! An issue (has/will/should) (be/been) raised.
- Clean the bed between prints.
    - Use the isopropyl alcohol on a piece of paper towel to clean the PEI bed.
         - Don't get any on your fingers and ensure the PEI is cool.
- Scrape any build up of material away from the tips using the carving tools (One carving tool is missing, please bring it back #carvingtoolamnesty).


###Raise issues you come across [here][gi].
####Self-led learning

#####Support
-The official [Roxox site is here][r]. It features manuals, support portal and a community.
-The unofficial community [Roboxing is here][rb].

#####Models
-[My MiniFactory][mmf] provides free and purchasable models that have been optimised for CEL-Robox 3D printers.
-[Thingiverse][tv].

#####Modelling
-To learn how to edit files see [this Instructible][stli].
-If you're a novice, get coffee, get google and search for "[Tinkercad][tc] tutorials" and get comfy.
 
[d]: http://www.cel-robox.com/downloads/ "CEL Robox offical site"
[gi]: https://github.com/ljmu-cms/Robox-3D-Printing-/issues "LJMU CMS 3D Printer Issues"
[er]: http://www.cel-robox.com/wp-content/uploads/RoboxDocuments/Robox%20User%20Manual%20v1.3.pdf "Please see chapter 4 for reel usage."
[rb]: http://www.roboxing.com/start "Unoffical community wiki"
[mmf]: http://www.myminifactory.com/ "Offical ROBOX 3D Models"
[tv]: http://www.thingiverse.com/ "Large online resource of various maker projects"
[stli]:http://www.instructables.com/id/How-to-edit-stls-for-3D-printing/?ALLSTEPS "How to edit STLs"
[tc]: https://www.tinkercad.com/ "Browser based modeling software"
