Project: clock-display
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class ClockDisplay. Then inspect this 
instance and leave the object inspector window open. With the inspector window open, 
call the object's methods, such as timeTick and setTime. Watch the 
"displayString" in the inspector.

The displayString field simulates the actual clock display device. Were this 
program running in a real clock, it would change the real, physical display 
hardware instead of this string. The timeTick method would be triggered once 
every minute by some timer hardware.

Everything else could be pretty much the same.


Note: This project does not implement adequate handling of errors.

PART II: clock-dispay project

21. In the constructor that is the default time and there are no parameters where we can add our own values for hours and minutes.

23. I would have to call it 60 times. By callin the special method: ClockDisplay (int hours, int minutes) and writing 1 in the hours and 0 in the minutes.

24. Definiton: private NumberDisplay digit;
    Assignement: digit = new NumberDisplay(10);

25. private Rectangle window;
    public Rectangle (int width, int length) 
    {
      window = new Rectangle;
    }

26. The second constructor lets us put in the values of the when we create an object, so that we can see our own values whhen we call the method getTime.

27. They both have this: hours = new NumberDisplay(24);
                         minutes = new NumberDisplay(60);
However, the first constructor has updateDisplay(); because the default value is 00:00  meaning it has nothing to validate so it just updates the display. However, the other one has setTime(hour, minute); because since we are putting in the values of hours and minutes, it has to validate what we put in there.

28. public void print(String filename, boolean doubleSided)
    - p1.print("README.txt", "true");
    - p1.print("README.txt", "false");

public int getStatus(int delay) 
  - p1.getStatus(10);
  - p1.getStatus(20);

I am not sure about this question



29. Circle, Square and Triangle

30.roof.changeSize(60, 180);
   roof.moveHorizontal(20);
   roof.moveVertical(-60);
   roof.makeVisible();

31. NO

32. 2

33. When both or the first number is negativ the answer in negative but wwhen it is only the second number then it returns positive.

34. The remainder will be between -4 and 4 where -4 and 4 are included. 

35. All number negative or positive could be a possible result except for 0. I think.

37. I think option 1 was easier and faster to do. However, I think option 2 was better because it says if it pm and does not just go from 1-12 on a loop without knowing the if it is pm or am.











