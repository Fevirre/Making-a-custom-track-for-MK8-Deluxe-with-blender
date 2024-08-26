# Making a custom track for MK8/Deluxe with blender

So you finally want to use blender to make custom tracks but lost as heck and have no idea how to make them. So here is a currently work in progress text tutorial to help you 
This is also based on squadaloo's tutorial but straight to the point and without all the time wasting yapping

# Understanding blender's keybinds and making your first course
As soon as you open blender you are met with this ![image](https://github.com/user-attachments/assets/4570d275-e507-4b6c-90c8-c03515c04aa0) 

yeah we will not be needing these.
all you need to do is press A and then X and click on the delete button prompt
![image](https://github.com/user-attachments/assets/e87e1869-ec04-4de9-8b9d-d9a7abcbe053)

Once those are out of sight and out of mind go ahead and import the startgrid obj by going here
![image](https://github.com/user-attachments/assets/dd46509d-5e9a-4e10-a8d2-650cf9988399)

Once that is done and it has a fog like effect just press N and set these up ![image](https://github.com/user-attachments/assets/972c192a-4f51-4c1f-96cf-039706396f56)

Hold shift and A and select mesh and then plane and then hold on the S key to scale it
![image](https://github.com/user-attachments/assets/bcd223dc-55e8-4cbb-b49e-64c1fab5ebbf) ![image](https://github.com/user-attachments/assets/3619cfc0-72bd-4daa-bf92-2f93504f073e)

Then hold X while you are scaling your plane mesh and hover over the mesh by going to edit mode and holding CTRL and R to add in between 8-10 splits ![image](https://github.com/user-attachments/assets/2ea938e0-e037-43eb-baf1-bc9889ab6768) ![image](https://github.com/user-attachments/assets/bfaca696-1a79-4935-a7d3-bbf33383f7a2)


Then do Shift A and click on Curve and the path and Scale it ![image](https://github.com/user-attachments/assets/e251ab58-fc22-48ba-bbaa-1556d53b4db3)


Then add in 2 modifiers, one for Array and one for Curve for your plane mesh and under curve object select nurbspath, the mesh will follow along the path when you put new points down you will see in a second (Psst. click on the wrench icon) ![image](https://github.com/user-attachments/assets/543929f8-fc01-4add-b2a2-7d8bd38013f0)

Click on the wrench icon again under your plane mesh and select the array modifier and make sure the Array count is set way higher than 2 (e.g 200)
![image](https://github.com/user-attachments/assets/5a143556-bf38-4285-88b6-f5e8215ca7e8)


Now select nurbspath and go to edit mode, select the point farthest way from your startgrid and press E and your mesh will start going along the path
to place it down just click with your mouse and keep doing this until you have a layout you like
Then select the end point and the start point and press the F key to connect it all ![image](https://github.com/user-attachments/assets/9f58a8e0-c0eb-47c4-a183-81b621d806c6)


