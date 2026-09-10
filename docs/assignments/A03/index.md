# A3 – [Parametric and FEA]

## Part 1: Design Considerations and Calculations 

In this assignment we were tasked with designing a hollow box beam that would have a maximum deflection of 0.009 inches. To start we were given a load value of 300lbf to 500lbf. The maximum deflection as well as a range for Youngs modulus fromm (8.5-10.5)*10^6 psi.   

I began by using formulas that were given in the book to calculate my beam, this is where my first mistake comes, my mistake is when starting it says of a circular diameter in the canvas page so my first equation was solving for that which would be corrected after seeing the thickness requirement down the line.  

<img src="IMG_7287.jpeg" alt="Picture of work done" width="500">
<img src="IMG_7288.jpeg" alt="Picture of work done" width="500">  

Using this work I was able to find a maximum span of 52.73 inches for my design. 


## Part 2: Cad Design  

I would design the model using Creo parametric as my cad software according to the parameters I just created and create a hollow box using an extrusion.
<img src="creoreal2.png" alt="Picture of Parameters used" width="500">  

Next I would go on to create another extrusion this time to get the length for my beam 
<img src="creomistake.png" alt="Picture of Parameters used" width="500"> 


## Part 3: Proving the Design 

Next I would have to redownload creo due to my simulation software not being installed in the package the first time, with the help of an staff member I was able to redownload and figure out this issue. 

After the reinstall I would go to simulation and create a FEA for my beam, starting by creating a force for my object as shown below.  
<img src="Screenshot 2026-09-10 020639.png" alt="Picture of Parameters used" width="500">  

Then a constraint would be added to keep the beam as rigid as possible as shown below.  
<img src="Screenshot 2026-09-10 020232.png" alt="Picture of Parameters used" width="500">  

Finally I would change the material to the parameters given and what can be found about the material properties for aluminum as they were required to run the simulation. 
<img src="Screenshot 2026-09-10 020024.png" alt="Picture of Parameters used" width="500">  

## Part 4: Running the simulation FEA 

For my simulation my maximum stress was a lot higher than what would be allowed for aluminum, this is due to my own I assume due to a negligence in calculations or problem with the way I oriented in creo

* Displacement *
<img src="displacement.png" alt="Picture of Parameters used" width="500">

* von Mises Stress map*
<img src="stress.png" alt="Picture of Parameters used" width="500">

## Part 5: Result Checking 
My deflection from my hand calculations was 0.009 inches and from my FEA it was 0 which is a percent difference of a large 200%! 
This large discrepancy more than likely comes from a bad transfer of ideology to practice, in theory I shouldn't have this large of a discrepancy and it can only stem from bad cad design on my part as the number started with was a fixed value. I would trust the design stress that was given while I do trust my own cad designs to work as intended. I don't believe it is possible to create a beam that can have no stress from a 400 lbf load when the bar is that small. 

*b* 
Because my area was equal to 0.2344in my total psi would be 1,706.5 and the max stress would be 2.5 times that value at 4,266.25 psi. Assuming a yield strength of 40,000 psi my safety factor would be 40,000/4266.25, totaling 9.38 This would easily pass the safety factor requirement. 

## Part 6: Final Statements 

From this project I learned that I have to learn more about cad while I was doing this project a lot of the errors I ran into came from not knowing Creo as well as I would like to know it. The mistake of seeing a circular vs hollow box beam though isn't something that can be fixed with better cad design. I think one of the main things I learned here was to never give up and you can always push through a difficult assignment. My time spent was around 6 hours from beginning to end. 

Download my files here 
