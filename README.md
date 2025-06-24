# Weekly Calorie Intake Calculator

## About the Project

**Weekly Calorie Intake Calculator** is a Python application that helps you track your weekly food consumption by entering either the food name or its weight in grams. At the end of the week, it estimates your total food intake in grams and gives an approximate calorie burn goal.

---

## Foods and Their Gram Values

The application uses the following foods and their corresponding gram values for quick entry:

| Food           | Grams |
|----------------|-------|
| Hamburger      | 250   |
| Kebab          | 350   |
| Iskender       | 500   |
| Chicken Doner  | 120   |
| Beef Doner     | 175   |
| Kumpir         | 300   |
| French Fries   | 400   |
| Salad          | 50    |
| Barbeque       | 375   |

---

## How It Works

1. **Start the Program:**  
   When you run the script, you’ll see a welcome message and instructions.

2. **Daily Entry:**  
   For each day of the week (Monday to Sunday), the program will prompt you to enter what you ate.  
   - You can enter either the food name (from the list above) or the weight in grams.
   - Type `done` when you finish entering foods for that day.

3. **Input Method:**  
   - If you enter a number, it is treated as grams.
   - If you enter a food name, the corresponding gram value is added.
   - Invalid entries will prompt you to try again.

4. **Daily Summary:**  
   At the end of each day, you’ll see your total food consumption in grams for that day.

5. **Weekly Summary:**  
   After all days are entered, the program displays:
   - Your total food consumption in grams for the week.
   - An estimated weekly calorie burn goal (assuming an average of 200 calories per 100 grams, as a rough estimate).

---

## Example Usage
