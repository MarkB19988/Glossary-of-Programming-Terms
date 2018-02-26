### Glossary of Programming Terms


##### 1. Algorithm

  An algorithm is a set of instructions that are used to complete a task or to solve a problem.
   
##### 2. Programming Paradigms

  ###### Procedural Paradigm
   
  Procedural programming is the idea/concept of using procedures. A procedure (also knows as a routine) is a set of commands that can be called from any point in the program (including being called from other procedures)
  
  Procedural programming is very common to see, especially in larger projects as it has the following benefits:
  * Re-Using sections of code without re-typing it
  * Easy to follow the structure and logic of the program
  * The Code is easier to edit and maintain
  
  This paradigm is usually how you expect a computer or a application to function, you provide the computer a set of step by step instructions and the computer carries them out in order. This makes procedural programming very intuitive however can sometimes be more time consuming when creating more complex functions 
  
  ###### Object Oriented Paradigm
   
  Object oriented programming is the idea/concept of using objects that can contain data in the form of fields and code in the form of methods. A key feature of objects is that they can aceess and edit the data fields of other objects that they are linked to. A method in object-oriented programming is similar a procedure in procedural programming. The main difference between the two is that a method is part of an object. In object-oriented programming, you create objects and give them properties. For example, a person can be seen as the object and every person has a name, age, sex ect. These are it's properties
  
  As both data and methods are combined into one object, this allows you to create mroe complex functions and programs with less code as you can re-use blueprints of objects multiple times.
  
  ###### Event Driven Paradigm
   
  Event Driven programming is idea/concept that the program will run by recting to user inputs. It can react to different kinds of input, like a button click, choosing from a drop down list, entering text into a text box, and many other kinds of inputs. Event Driven programming is very similar and usually implements features of object oriented programming. This is because in GUIs (Graphical User Interfaces) an object, for example a button, is listening out for and input from the user. However, it is important to remember that just becasue alot of event driven programs are also object oriented, does not mean that the opposite is also true.
  
  The advantage of Event Driven Programming is in the ability to create more interactive programs because of how easy it is to listen for user inputs and to execute code in reaction to the input.
  
  However a big disadvantage is that event loops take up alot of processing power, this is why the event driven paradigm is not often used for large applications, as the processing power required would be to high for most systems to run smoothly.
  
  
  ##### 3. Debugging Process
  
  In software development, debugging is the act of locating and fixing any errors in your code. Debugging is a key aspect of software testing and is an essential part of software development in general. The process of debugging starts as soon as the fist lines of code are written and continues to grow as more code is written and begins to take the form of a full software program. In a large program that has thousands of lines of code, the process of debugging can be made simpler and quicker by using strategies such as unit tests, code reviews and pair programming.
  
  The process of debugging is as follows:
  
  ###### 1. Find and Describe the bug
  
  Although not a part of the process itself, in order to fix a bug you need to find one in the first place. A good place to start is using unit testing to find errors and bugs in small sections of code. Once found you have to describe what is going wrong.
  
  ###### 2. Reproduce and Snapshot
  
  Once a bug is found, you must next try to reproduce the bug when you run the program again. Once the bug happens, you need to 'snapshot' the bug. This involves you finding out the state of your code at the time of the bug (e.g. The values of variables, which function is running?) 
  
  ###### 3. Analyse the Snapshot
  
  Once you have the snapshot, you can use this information to dig deeper into the code and see if individual functions are producing the error. Once you identify a possible cause, you can begin to test possible solutions.
  
  ###### 4. Test Solution(s)
  
  Now you have a possible solution, you need to test it. If the solution fixes the bug and doesn't introduce any new bugs into the code, your solution was succesful and the debugging process is complete. If it does not correct it or introduces new errors you need to repeat these steps until the bug is corrected.
  
  ##### Advantages of debugging using an IDE
  
  Using an IDE has many advantages over using a normal text editor. Firstly, a normal text editor has no way to assist you if you were to make a spelling or a syntax error. When using an IDE, it can have the language you are writing in stored so that it can predidct what you are trying to type and offer you a possible end to your line of code. It can also tell you when it is expecting to see a ';' or other syntax and tell you what line it is missing from. 
  
  IDEs also offer other debugging features that make the process easier or faster, these are as follows:
 
  ###### Realtime Editing and Running
  Some IDEs allow you to edit your code while it is running, this allows you to see the real time results of the changes you have made. This is useful because it can help you save time and try out more possible solutions alot faster than if you had to compile and run the code independantly.
  
  ###### Change Variable Values While Running
  Aditionally, some IDEs also allow you to change the value of variables manually while the code is running. This is useful because it allows a developer to test how their code works at multiple stages or with invalid inputs in real time. It also saves time for the same reasons stated above.
  
  ###### Skip or Repeat Sections Of Code
  IDEs offer the user tools that let them isolate snippits of their code from the rest of the program. This lets the developer quickly make theoretical changes to individual sections of the code without having to edit the whole program or create a new document and copy the snippet into that new document. If the changes he/she makes are benificial, they can simply reintroduce the snipped to the main body of code. If it doesn't then the changes can be easily erased.
  
  
  ##### 4. The Process of Building an Application
  
  ###### Step 1. Assemble a team (or decide to work alone)
  Firstly you must decide on who will be working with you on this project, make phonecalls or arange meetings with a designer or a developer and try and get them on board. Alternatively, you can chose to undertake the project alone, but be aware that it will be a lot of work.
  
  ###### Step 2. Wireframing
  Wireframing is a rough visual idea of what your app will look like. Each wireframe sketch should show what will happen on every possible screen/scene of your app and what interactions could be had (e.g. arrows to show something can move across the screen)
  
  ###### Step 3. Design
  Next you must create solid, final design documentation and conecpt art that will clearly explain and show the features the app will have. Concept images should be as close to how you want the app to look as possible. In your documentation you can talk about different colours, fonts, features ect.
  
  ###### Step 4. Development
  Development is where you make your app. In the development stage any mistakes that arise could be very costly, both in terms of time and money, so having a clear plan and design before hand is critical.
  
  ###### Step 5. Testing
  Testing is important to make sure that you havent left any bugs or errors in your app and that it works as intended. Testing can also be done along side development to correct any errors as they surface but it is always good to do a final 'beta test' before realease to make sure the whole game works correctly
  
  ###### Step 6. Launch
  Once all of the above has been completed you can go ahead an release your app on your chosen platform. Be aware that some platforms may have fees for putting an app on the store.
  
  ###### Step 7. Post Launch Support
  After launch is important to collect regular feedback from your users so you can fix any bugs that arise or introduce new features that are highly requested.
  
  ##### 7. What Is The Process from Writing Code to Execution
  
  After you write your code, there are a number of steps that happen in the background before your code is executed.
  
  ###### Step 1. Writing
  Before any code can be run, it has to be written. Most of the time this is done in a chosen source code.
  
  ###### Step 2. Compilation
  After the code is written it must be compiled. Compiling is the process of converting the programs code (the source code) into another programming laguage (the target language). This is usually, but not always, the process of turning high level code like a program written in C++ into low level code, most commonly machine code.
  
  ###### Step 3. Invoke (Load into Memory)
  Once the program has been converted to machine code, it is then alocated memory. This process is handled by the operating system that determins how much memory the program needs.
  
  ###### Step 4. Execution
  Once all of the above steps have been completed, the computer can finally run the program. Each instruction is now in machine code that the computer can read. Each instruction triggers thousands of simple actions on the executing machine that culminate to do what the program was written for.
  
 
