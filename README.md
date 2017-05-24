# WendyHu_Symposium2017_Journal
Journals for Symposium 

05/04/17
Goal for today:
  Setup repository for project Plague and work with Tracy to plan out the layout of how the game will work, look and split up the work.
  Research why gamers are a fan of the game Plague, points of the game that will have to remain the same so that the game will not lose its initial function and attractiveness. 
  
  Progress:
    Planned out how the game may look when launched: start screen, main screen
    Planned out the main necessities of the game (look at obstacles...)
    http://cramgaming.com/plague-inc-evolved-review-27920/
    
    Obstacles faced: One of the main attractions of the game Plague is that it is a very strategy based game, the spreading of the virus 
    can be impacted by a lot of things: climate, region, transmission....So, it will be difficult for us to replicate everything in the 
    game, will need to decide what we can do and what we cannot. Also, the story line of Plague is infecting the entire world, however 
    the entire world may be too large of a scale for us, so right now might begin with just the United States or the continent of North 
    America.

  Will Need For Tomorrow:
    Create game repository! 
    
---------------------------------------------------------------------------------------------------------------------------------------  
5/05/17
Goals for today:
  Setup repository
  Planout layout and features of game

  Progress:
    Created repository but need the GUI and etc. 
    Planned out initial layout of game: 
    
      Will be based on the United States
      
      Each state will be an instance of a class
        Will have vars: name, climate, population
        
      Display of the map will change with the change in population infected: 
        The more the population is infected the more red the map becomes
        When everyone in state dead map becomes black
        
      Will have a stats bar on the bottom of screen:
        OnHover of a state show: state name, population infected, population dead
        
      Will have a Disease menu and a cure menu
        In Disease menu: more on transmission, bacteria evolution, bacteria abilities
        
        In Cure menu: more on status of cure and stats....
     
     New members to our group
     Started coding some classes
     
   Need to Do:
   
     Plan out all the classes that are needed
     
     Plan out display of map (not sure how we will display the map as pieces of states put together or just use rectangles...)
     Distribution of work
     
--------------------------------------------------------------------------------------------------------------------------------------- 
     
5/08/17
Goals for today:
 Get addition members onto git repository
 Plan out roles of each member
 How are we going to draw out the map of the US??
  
  Progress:
  
    Stats bar will be a component and will show up on the left side of the screen when a state is clicked
   
    Each state will be a clickableImage?When infected pop increases the color of pic will change use (setRGB()?)
  
    Tracy and Jimmy will come up with how the images of states and display of map will work...?
   
    There will also be a component to display DNApoints
   
  Need To Do:
    NEED TO IMPORT GUI AND COMPONENTS
  
  NOTE:WILL NOT BE HERE IN CLASS 5/09 and 5/10 DUE TO AP TESTING
    
--------------------------------------------------------------------------------------------------------------------------------------- 

5/11/17
Goals for today:
  Import jars
  Start working on stats component
  Create a presentation for the game like how we did for the arcade project?
  
    Progress:
    
    Copy and pasted gui and components from my own instead of jars
    
    Made a MainScreen Class will have the stats bar and buttons and map there
    
    Was going to create a Stats component with all the other textlabels inside it but don't know why it did not work (ref. DragonLand.shopScreen and shopLabel)
    
    Tracy and Jimmy will work on map 
    
  Need to Do:
    Create the introScreen that will be intro to the game
    Learn how to have player type input for game ex Player's name
    
---------------------------------------------------------------------------------------------------------------------------------------

5/12/17
Goals for today:
  Create an intro screen
  -will need to learn how to use scanners to have user input
  http://stackoverflow.com/questions/11871520/how-can-i-read-input-from-the-console-using-the-scanner-class-in-java
  
  Progress:
  
  Instead of using scanner for user input have change GUI to Mr.Nockles' GUI so that I can use the textfield component for user input
  
  Need to Do:
    Finish intro screen
  
---------------------------------------------------------------------------------------------------------------------------------------

5/15/17
Goals for today:
  Finish intro screen
  Edit stats component
  
  Progress:
  
  Instead of working on intro screen had been working with tracy on mainscreen and map
  Problem: how do i call the button within the button's action
  
  
  Need to Do:
    Finish intro screen
    Remember how to call button itself inside the action fo that button
  
 ---------------------------------------------------------------------------------------------------------------------------------------
 
 5/16/17
 Goals for today:
  Finish Intro screen
  If have enough time get back to button problem............
  
  Clarifying my role for now: responsible for front end all the display
  
  Progress:
    Working on intro screen tried to make title and input
    
  Need to do:
    Finish intro screen and work on mainscreen buttons
    
 ---------------------------------------------------------------------------------------------------------------------------------------
     
  5/17/17
  Goals for today:
    Finish Intro screen
    -add background
    Work on mainscreen buttons

  Progress:
    Made intro screen and mainscreen
    Will need a background
    will need to start chain of events:when click a state  start infection
    
  Need to do:
    Work more on Mainscreen
    When the sleeper is done add it to mainscreen

---------------------------------------------------------------------------------------------------------------------------------------

5/18/17
Goals for today:
  add DNApoints
  start the infection chain
  
Progress:
  Mr.Nockles helped me fix the welcome on mainscreen
  created infection thread that will start running when first state is clicked
  created adStates method that will be used to find the adstates 
  -will need to test out to see if the method works
  
---------------------------------------------------------------------------------------------------------------------------------------

5/22/17
Goals for today:
  add DNApoints
  work on adStates method
  
Progress:
  Working on adStates method had previously messed up distance formula calculation now woks with states above,below,left,right but unable to find diagonal states....
  Didnt have time to work on dna points
  
  Need to do:
    fix adStates to include diagonal or maybe not
    work on dnapoints
    work on changing numbers of infected
    
 ---------------------------------------------------------------------------------------------------------------------------------------
 
 5/23/17
 Goals for today:
  add DNApoints start thread for points
  adStates method will not work with diagonals
  
  Progress:
    Created multiple threads new bubble pops up at the first infected state however unable to click it....?
    Need to work on spreading the infection and infected pop. nums
    
 ---------------------------------------------------------------------------------------------------------------------------------------
  
  5/24/17
  Goals for today:
    try to finish the adding dnapoints threading problem: unable to click the bubble...?
    spreading the infection to adjacent states
  Need to do:
    Try to fix bubbles
    spread infection!
  
