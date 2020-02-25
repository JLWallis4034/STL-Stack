STL Tutorial: STACK

1. Overview

A stack is a data structure used to organize items into a collection. With the way these items are organized, a stack can be useful in many ways. This document will explain how stacks work, alongside a Visual Studio project made to illustrate how a stack is affected through various actions.

2. How does the stack work?

A stack in C++ programming follows an organization method known as LIFO ("Last In, First Out"). This means that whatever items are added to the stack last will be taken off of it first. Think of it like a competitive card game, where someone plays a card that does something, and someone plays a card in response to stop it. The last card to be played will "resolve," or go through its process, first. The stack is similar in that regard.
When putting items onto a stack, you would "push" it onto the top, placing it above everything else (if anything) in the stack. Once the object on the top of the stack has served its purpose, it is then "popped" - or removed from the top of the stack - to make way for the item below it. This item becomes the new "top." 
Apart from pushing and popping, the stack can also be read to determine its size and whether or not it is empty or full. This relies on the value of a variable known as "top," which is set to -1 upon a stack's creation (when it is empty). "Top" is capable of reaching a value of 1 less than the max stack size, denoting the stack as "full." The size of the stack can be determined by adding 1 to the value of "top."

3. What makes the stack useful?

The stack is very useful as a data structure. One example of where it is used is an application with temporary pop-up windows. If an application opens a pop-up window, chances are that window has to close before the main application window can close. That window is put onto a stack, locking access to other windows until that one is removed. Another data structure, such as a queue, wouldn't work for this, as it wouldn't be able to add and remove windows from the screen correctly. A specific example of this can be seen with a website like Blackboard. When you click the button to submit a file from your computer as an assignment, it opens the computer's File Explorer. This Explorer window locks out all interaction with the Blackboard window until it is either closed or a file is selected.

4. Further Reading

Further reading on the implementation of stacks can be done by following the links below, which were used to aid in the creation of the Visual Studio project.

Works Cited:
http://www.cplusplus.com/reference/stack/stack/ - This page contains all the member functions outlined in the Visual Studio project as well as some other ones that were not included.
https://www.techiedelight.com/stack-implementation-in-cpp/ - This page contains a well-made implementation of a stack in C++, going as far as to print every change done to the stack through the life of the program.
