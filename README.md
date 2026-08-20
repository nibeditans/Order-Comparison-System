# Order Comparison

This Python module defines an Order class that facilitates the comparison between two orders based on their prices. It uses Python's special (or "dunder") method __gt__ to override the greater-than operator (>), making it possible to easily compare two instances of the class in terms of their price attribute. This module can be a handy addition to applications dealing with e-commerce, inventory management, or anywhere order comparisons are necessary.

## Features

* **Item and Price Storage:** Each order instance stores an item and its corresponding price.
* **Order Comparison:** Allows for intuitive comparison between two orders to determine which has a higher price.

## Requirements

`Python 3.12.1` (Version can vary)

## Installation

No installation is required beyond having Python installed on your system.

## Usage

To use the Order class in your project, follow these steps:

1. Ensure Python 3.x is installed on your system.
2. Download the order_comparison.py script from this repository (assuming the script is named as such).
3. Import the Order class from the script into your project as needed.

## Example

```py
from order_comparison import Order
    
order1 = Order("Chips", 20)
order2 = Order("Biscuit", 15)
    
if order1 > order2:
    print(f"{order1.item} is more expensive than {order2.item}.")
else:
    print(f"{order2.item} is more expensive than {order1.item}.")
```

## This should output: `Chips is more expensive than Biscuit.`

## Customization

The Order class can be extended or modified to include additional attributes such as quantity, discounts, or taxes. The comparison logic can also be adjusted or expanded (e.g., `implementing __lt__` for less-than comparisons) based on your application's specific needs.

## Contributing

Contributions, suggestions, and improvements are welcome! Please feel free to fork the repository, make your changes, and submit a pull request.

## License

This project is open-source and available under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions, feedback, or contributions, please open an issue in the GitHub repository for this project.
