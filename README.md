#include <iostream>

int main() {
    // 1. Declare variables for Celsius and Fahrenheit
    double celsius, fahrenheit;

    // 2. Ask the user for input
    std::cout << "Enter the temperature in Celsius: ";
    std::cin >> celsius;

    // 3. Convert to Fahrenheit using the provided formula
    // Formula: F = (C * 1.8) + 32
    fahrenheit = (celsius * 1.8) + 32;

    // 4. Output the result
    std::cout << celsius << "°C is equal to " << fahrenheit << "°F" << std::endl;

    // 5. Bonus: Conditional logic for Freezing and Hot
    if (celsius < 0) {
        std::cout << "Freezing!" << std::endl;
    } else if (celsius > 30) {
        std::cout << "Hot!" << std::endl;
    }

    return 0;
}
