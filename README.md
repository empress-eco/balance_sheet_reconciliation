<p align="center">
  <a href="https://grow.empress.eco/"><strong>Explore the Documentation »</strong></a>
  <br>
  <a href="https://github.com/empress-eco/balance_sheet_reconciliation/issues">Report Bug</a>
  ·
  <a href="https://github.com/empress-eco/balance_sheet_reconciliation/issues">Request Feature</a>
</p>

## Table of Contents
- [Table of Contents](#table-of-contents)
- [About The Project](#about-the-project)
  - [Overview](#overview)
  - [Key Features](#key-features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License and Acknowledgements](#license-and-acknowledgements)
  - [License](#license)
  - [Acknowledgements](#acknowledgements)

## About The Project

### Overview
The Empress Balance Sheet Reconciliation module for Empress offers a unique solution for reconciling General Ledger (GL) Entries of any selected balance sheet account. It caters to a wide range of balance sheet accounts beyond just receivable and payable accounts - a perfect tool for entities like tax entries that require reconciliation with payments made to revenue departments.

### Key Features
- Enables reconciliation for any selected Balance Sheet account's GL Entries.
- Supports manual and automatic reconciliation.
- Allows for unreconciliation of already reconciled entries.
- For full reconciliations, the system issues a Full Reconcile Number linking each group of reconciled GL Entries together.

## Getting Started

### Prerequisites
- Empress software

### Installation

To install the Empress Balance Sheet Reconciliation module, follow these steps:

1. Open your terminal
2. Change the current working directory to your local Empress instance

    ```sh
    $ cd empress-bench
    ```
3. Clone the repository

    ```sh
    $ bench get-app https://github.com/empress-eco/balance_sheet_reconciliation.git
    ```
4. Install the application

    ```sh
    $ bench install-app balance_sheet_reconciliation
    ```

## Usage
Our comprehensive usage guide, included in the `README.md` file, provides a step-by-step walkthrough on how to use the Empress Balance Sheet Reconciliation module. This guide demonstrates usage with a VAT account as an example.

## Contributing
We welcome contributions! Here's how you can contribute:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License and Acknowledgements

### License
This project is licensed under the MIT License.

### Acknowledgements
We would like to express our sincere gratitude to the Empress Community for their groundbreaking contributions to the tools that constitute the backbone of this project. Their innovation and dedication have been instrumental in building the foundations and functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support.

Also, special thanks to [@kittiu](https://github.com/kittiu) for creating this helpful tool.