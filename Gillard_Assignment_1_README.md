# TEMPERATURE CONVERSION AND CHANGE CALCULATOR PROGRAMS

## TEMPERATURE CONVERSION

### Purpose:

The temperature conversion program converts temperatures between Celsius, Fahrenheit, and Kelvin.

### Inputs:

- `value`: The temperature value to be converted.
- `from_scale`: The original temperature measurement (Celsius, Fahrenheit, Kelvin)
- `to_scale`: The target temperature measurement (Celsius, Fahrenheit, Kelvin).

### Expected Output:

The converted temperature value in the specified target scale.

### Execution:

1. Run the program.
2. Call the `convert_temperature` function with appropriate values for `value`, `from_scale`, and `to_scale`.

### Possible Improvements:

- Could add in greater decimal control on the readouts. Some of the information could be modified to be greater or less than.
- Validation tests could also prove useful. Outlier temperature readings could prove fatal to program feasability.

## CHANGE CALCULATOR

### Purpose:

The change calculation program determines the amount of change and the minimum amount of each dollar denomination and coin needed for a transaction.

### Inputs:

- `tendered`: The amount tendered by the customer.
- `cost`: The total cost of the transaction.

### Expected Output:

The change amount and the minimum number of each dollar denomination and coin.

### Execution:

1. Run the program.
2. Call the `calculate_change` function with appropriate values for `tendered` and `cost`.

### Possible Improvements:

- Could make the coin and dollars more optimal. Insuring that the best transaction of money is done in the most efficient way possible.
