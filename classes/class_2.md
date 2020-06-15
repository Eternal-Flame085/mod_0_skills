# Employees

## variables
* salary (float)
* name (String)
* job (string)
* hours_worked (int)
* clocked_in (boolean)

## methods
* give_raise(amount) : (adds an amount to the salary variable for the employee raise)
* change_name(name) : (changes the name of the employee in case of misspelling, marriage, ect...)
* change_position(job) : (changes what their job is at the restaurant)
* add_hour(adds to the hours_worked integer by one)
* clock_in (changes clocked_in to true and every hour executes the add_hour method)
* clock_out (changes the clock_in to false and stops the add_hour method)
