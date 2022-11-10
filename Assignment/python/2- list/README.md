## Lists
Create a list by assigning a sequence of values to a variable. Each value is separated by a comma and surrounded by brackets []
                                      <!--TASK-1 -->
                                     
### Task-1
Create a list of all planets in the `planets` variable:
<details>
  <summary><h2>Name of planets</h2> </summary>

- Mercury
- Venus
- Earth
- Mars
- Jupiter
- Saturn
- Uranus
- Neptune
  
</details>
                                                        <!--TASK-2 -->
                                                        
### Task-2

Access list items by index
<pre>
OUTPUT:

The first planet is Mercury
The second planet is Venus
The third planet is Earth
</pre>

<details>
  <summary><h2>HINT</h2></summary>
  
You can access any item in a list by putting the index in brackets [] after the list variable's name. Indexes start from 0, so `planets[0]` is the first item in the list `planets`
</details>
                                                          <!--TASK-3  -->
                                                          
                                                          
### Task-3
Determine the length of a list
<pre>
Output:

There are 8 planets in the solar system
</pre>

<details>
  <summary><h2>Hint</h2> </summary>
  
To get the length of a list, use the built-in function `len()`. Creates a new variable, `number_of_planets`. The code assigns that variable with the number of items in the list planets (8)
  
</details>
                                                        <!-- TASK-4 -->
                                                        
### Task-4
Add values to lists.

Add `"Pluto"` to the existing list
<pre>
Output:

There are actually 9 planets in the solar system.
</pre>

<details>
  <summary><h2>Hint</h2> </summary>

Lists in Python are dynamic: you can add and remove items after they're created. To add an item to a list, use the method `.append(value)`.
  
</details>
                                                                <!--TASK-5 -->
                                                                
### Task-5 
Remove values from lists

Remove `Pluto` from the list
<pre>
Output:

No, there are definitely 8 planets in the solar system.
</pre>

<details>
  <summary><h2>Hint</h2> </summary>

You can remove the last item in a list by calling the `.pop()` method on the list variable:
  
</details>
                                                                         <!--TASK-6  -->
                                                                         
### Task-6
Find a value in a list
<pre>
Output

Jupiter is the 5 planet from the sun
</pre>
<details>
  <summary><h2>Hint</h2> </summary>

To determine where in a list a value is stored, you use the list's `index` method. This method searches for the value and returns the index of that item in the list. If it doesn't find a match, it returns `-1`.
  
</details>

