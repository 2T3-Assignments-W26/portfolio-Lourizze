# Projects
---
## Project #1: First Game 

**Description:**  
A game where the player must avoid aliens moving across the screen. The goal is to survive as long as possible while dodging all the enemies.

**Technologies Used:**  
VS Code, C#

**Code Snippet:**  
```csharp
static char AlienChar = '*';

static Int32[] AlienX = new int[NUM_ALIENS];
static Int32[] AlienY = new int[NUM_ALIENS];

static Int32[] AlienOldX = new int[NUM_ALIENS];
static Int32[] AlienOldY = new int[NUM_ALIENS];
static Int32[] AlienOffsetX = new int[NUM_ALIENS];
static Int32[] AlienOffsetY = new int[NUM_ALIENS];
```
![Project Screenshot](aboutme/Project%20%231.jpg)  
> Sadly, I can’t open the game, so this screenshot shows how it’s going to look like.  

**What I Learned:**  
- Learned how to use arrays to store and manage multiple game objects efficiently.


## Project #2: Menu

**Description:**  
In this project, we created a menu system for a game where players can choose which game mode or option to play. The menu provides options such as starting the game, viewing instructions, or exiting.  

**Technologies Used:**  
VS Code, C#

**Code Snippet:** 
``` static void AreasOfRectangles()
            {
                Console.WriteLine();
                Console.WriteLine("         --- Areas of Rectangles ---");
                Console.WriteLine();
                

                Console.Write("       Enter length of rectangle 1: ");
                int length1 = Convert.ToInt32(Console.ReadLine());
                Console.Write("       Enter width of rectangle 1: ");
                int width1 = Convert.ToInt32(Console.ReadLine());
                Console.WriteLine();

                Console.Write("       Enter length of rectangle 2: ");
                int length2 = Convert.ToInt32(Console.ReadLine());
                Console.Write("       Enter width of rectangle 2: ");
                int width2 = Convert.ToInt32(Console.ReadLine());
                Console.WriteLine();

                int area1 = length1 * width1;
                int area2 = length2 * width2;

                Console.WriteLine("       Area of Rectangle 1 = " + area1);
                Console.WriteLine("       Area of Rectangle 2 = " + area2);
                Console.WriteLine();

                if (area1 > area2)
                    Console.WriteLine("       Rectangle 1 has the greater area.");
                else if (area2 > area1)
                    Console.WriteLine("       Rectangle 2 has the greater area.");
                else
                    Console.WriteLine("       Both rectangles have the same area.");
                Console.WriteLine();
                Console.WriteLine();
                Console.WriteLine();
                Console.WriteLine();
            }
```  

![image](aboutme/image.png)
> Since I can’t open my account, I can only show what the beginning looks like.    

**What I Learned:**  
I learned how to use a `switch` statement to create a functional menu, allowing players to choose different game options. This helped me understand control flow and how to structure interactive programs.