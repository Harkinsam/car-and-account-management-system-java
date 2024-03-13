# Car and Account Management System

This Java project serves as a simple system for managing cars and bank accounts. It consists of two main classes: `Car` and `Account`.

## Car Class

The `Car` class represents a basic model of a car with properties such as number of doors, wheels, model, engine, and color. However, in this implementation, only the model property is utilized, with restrictions on the accepted models.

### Features:

- **Model Validation:** The `setModel()` method validates and sets the model of the car. Only models "Carrera" and "Commodore" are considered valid. Any other model will be labeled as "unknown".

## Account Class

The `Account` class represents a bank account with properties such as account number, balance, customer name, email address, and phone number.

### Features:

- **Deposit and Withdrawal Operations:** The class provides methods to deposit and withdraw funds from the account. It ensures that withdrawals are not processed if the balance is insufficient.
- **Information Management:** It allows setting and retrieving account information such as account number, balance, customer name, email address, and phone number.

## Usage

The `Main` class contains a sample usage scenario demonstrating the functionalities of both the `Car` and `Account` classes.

### Car Usage:

- Creates instances of cars and sets their models.
- Demonstrates the model validation feature.

### Account Usage:

- Creates an instance of an account and sets its details.
- Performs deposit and withdrawal operations on the account.
- Demonstrates handling of insufficient balance during withdrawal.

## How to Use

To use this project:

1. Clone or download the repository.
2. Open the project in your favorite Java IDE.
3. Run the `Main` class to see the sample usage scenario in action.


## Contributors

This project was created by [Akinrinade Samson](https://github.com/harkinsam), with the package structure inspired by `com.sam.carmanagementsystem`.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to extend this project or utilize its functionalities as needed. If you encounter any issues or have suggestions for improvement, please create an issue or pull request on the GitHub repository. Thank you for using this project!

