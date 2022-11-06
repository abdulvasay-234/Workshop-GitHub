# Arthmetic and variables

- Run the below code to calculate the total number of seconds in a year.
```python
num_years = 4
days_per_year = 365 
hours_per_day = 24
mins_per_hour = 60
secs_per_min = 60
# Calculate number of seconds in four years
total_secs = secs_per_min * mins_per_hour * hours_per_day * days_per_year * num_years
print(total_secs)

```

- Define a variable `births_per_min` and set it to 250. (There are on average 250 babies born each minute.)
- Define a variable `births_per_day` that contains the average number of babies born each day. (To set the value of this variable, you should use `births_per_min` and some of the variables from the previous code cell.)


```python
# TODO: Set the value of the births_per_min variable

# TODO: Set the value of the births_per_day variable

print(births_per_day)
```
If you execute the above program you will get `births_per_day = 360000`

To submit the answer [click here.](https://github.com/afnanabdulvasay-234/Workshop-GitHub/blob/python-assignment/Assignment/python/1-Arithmetic-and-Variables/1-Arithmetic-and-Variables.py)

Remember you can get a hint if you need it.
<details>
  <summary><h2>Hint</h2></summary>
How can you use the variables to calculate the number of minutes in one day? Once you have that, you need only multiply that number by the number of births per minute.
  </details>
