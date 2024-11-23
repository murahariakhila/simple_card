1.Simple app with a single page containing about the kpop group blackpink and an image of the group's logo

2.Started with the necessary imports which you could later on add while you code

3.In kotlin the class MainActivity is pretty much same for every code 

4.MainActivity : ComponentActivity(): This defines the entry point of the app 

5.onCreate: This is Where you set up your app when it starts

6.setContent { ... }: it is the UI page for the app (like how your app looks)

7.Scaffold: handles UI elements

8.The Greeting function is a small part of the app that shows something on the screen, like text.In this case, it displays a message (e.g., "Hello Android") and adds space around it using padding

9.next using @Composable created a function called Greeting here the paramenters passed are name and modifier

10.created a box for the image to insert the image. A modifier is a  UI tool that lets you do so many things .

11.fillmaxSize() is used to fill the the box fully to the screen.

12.opened the image and attached the image .

13.you can use contentDescription to describe the picture you used or just set it to null

14.ContentScale decides how the picture is to be set in the screen .. like you can use contentscle.crop if you want to crop the picture if its out of the screen o=r you could use contentscle.fit to fit the entire picture into the screen and there are many other options..

15.using modifier image is set with fillMaxWidth() , .height(400.dp) ,  .padding(bottom=300.dp)

16.Next created an other box for the text below the image
 
17.Another box is created for the Sub-title and the description of blackpink. using column both the texts are placed in the center one after other

18.In column vertical arrangement is used to arrange both the texts verically in center and same for the horizontalAlignment but it Aligns in center Horizontally 

19.last is the preview section to preview the ui elements in your code

20.you can run the code on an  emulator device or on your phone. 
