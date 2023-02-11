# thekettle
A simulation of the electric kettle.
<img width="1002" alt="Screenshot 2566-02-11 at 22 54 21" src="https://user-images.githubusercontent.com/122988058/218270168-f6212f4b-53d2-4afe-a3f2-43eaa5f767f3.png">
## Input:
Water volume integer (in ml).

## Output: 
Water temperature (in degree Celsius) and total energy (in kilojoule).

## How to run:
`$ javac MyKettle.java` <br />
`$ java MyKettle`

## How to use:
Just add water and turn it on. (See MyKitchen.java)

## How does it work:
A kettle is a kitchen appliance that dumps as much energy into a volume of water as quickly as possible. This particular kettle is rated for 1800 watts, but because some heat can escape through the wall of the container, it can only push 92% of that energy into the water (See Kettle.java, line 29). In this program, we infer the water temperature by calculating the amount of energy added to the water. The kettle shuts off when the water reaches 100°C. 

How Electric Kettles Work: https://www.explainthatstuff.com/how-electric-kettles-work.html

Why don’t Americans use electric kettles: https://www.youtube.com/watch?v=_yMMTVVJI4c


