# Rectangle Area and Perimeter Calculator

This Java program calculates the **perimeter** and **area** of a rectangle based on user input for width and height.

## How It Works

- The program prompts the user to enter the width and height of a rectangle.
- It then calculates:
  - **Perimeter**: \( 2 \times (\text{width} + \text{height}) \)
  - **Area**: \( \text{width} \times \text{height} \)
- The results are printed with formatted output.

## Usage

1. **Compile the program:**

   
   javac W01_P1.java
   

2. **Run the program:**

  
   java W01_P1
   

3. **Input:**

   - Enter the width (as a number), then press Enter.
   - Enter the height (as a number), then press Enter.

4. **Output:**
   - The program will display the perimeter and area with clear formatting.

### Example

```
Input:
5.0
3.0

Output:
Perimeter is 2*(3.0 + 5.0) = 16.00
Area is 5.0 * 3.0 = 15.00
```

## Notes

- The program uses `Scanner` for input and `System.out.printf` for formatted output.
- Input values should be valid numbers (decimals allowed).
