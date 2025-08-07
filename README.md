# BMI Calculator (Java)

A simple Java-based BMI (Body Mass Index) Calculator that takes user input such as weight and height and calculates the BMI based on the standard formula. The application also categorizes the result into standard categories, including Underweight, Normal, Overweight, and Obese.

## 🧮 What is BMI?

BMI (Body Mass Index) is a measure of body fat based on height and weight. It is commonly used to determine whether a person is underweight, normal weight, overweight, or obese.

**Formula:**
```
BMI = weight (kg) / (height (m))^2
```

## 🚀 Features

- Accepts user input for weight and height
- Calculates BMI using the standard formula
- Provides interpretation:
  - Underweight (BMI < 18.5)
  - Normal (18.5 <= BMI < 24.9)
  - Overweight (25 <= BMI < 29.9)
  - Obese (BMI >= 30)
- Console-based user interface

## 📦 Technologies Used

- Java (Core Java)
- Scanner class for input
- Conditional statements for category classification

## 🧠 Project Structure

```
/src
  └── BMICalculator.java   # Main class with logic to compute BMI
```

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/BMI-Calculator.git
   ```
2. Navigate into the project folder and compile the Java file:
   ```bash
   javac src/BMICalculator.java
   ```
3. Run the application:
   ```bash
   java src.BMICalculator
   ```

## 📸 Sample Output

```
Enter your weight in kilograms: 75
Enter your height in meters: 1.8

Your BMI is: 23.15
You are in the Normal weight range.
```

## 📚 Future Enhancements

- Add a GUI using JavaFX or Swing
- Add support for imperial units (lbs/inches)
- Export result to a text or CSV file

## 🤝 Contributing

Contributions are welcome. Feel free to fork the repository, make improvements, and open a pull request.

---

> 💪 Built by Aman Saifi as part of a Java learning journey.
