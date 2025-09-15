Flood-It is a Java game that floods a colored grid from the top-left cell until the whole board matches. It’s built with the javalib course libraries 
(impworld, worldimages) and uses the tester framework for launching and basic tests. Board size and number of colors are adjustable, with a step counter, 
timer, and a reset key (r). All code is contained in src/floodpt2.java. 

How to Run in Eclipse

1. Import the project into Eclipse  
   - Go to File → Import → Existing Projects into Workspace 
   - Select the project folder and click Finish

2. Add the required libraries  
   - Right-click the project → Build Path → Configure Build Path**  
   - Go to the Libraries tab → Add JARs
   - Add both javalib.jar and tester.jar

3. Create a Run Configuration  
   - Go to Run → Run Configurations 
   - Select Java Application → New Configuration
   - Set Project to your project name  
   - Set Main class to:
     tester.Main
   - In Program arguments, type:
     ExamplesFloodItWorld

4. Run the game  
   - Click Run 
   - The Flood-It game window will appear.  
   - Click colors to flood the board, and press r to reset the game
