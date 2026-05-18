# Lyntica Property Management System

A simple, lightweight automation script designed to streamline monthly bill generation for landlords and property managers. This system calculates payments, combines utilities, tracks arrears, and makes sending tenant reminders effortless.

## Features

- **Rent Tracking**: Manage monthly base rent calculations for your properties.
- **Utility Breakdown**: Automatically include and itemize billing for:
  - Electricity Bills
  - Gas Bills
  - Water Bills
- **Arrears Management**: Factor in previous outstanding balances directly into the current billing cycle.
- **Easy Reminders**: Simplifies the process of generating and sending clear payment summaries to tenants.

## Repository Structure

- `Monthly Bill Generator.ipynb`: The core Jupyter Notebook containing the automation script.
- `README.md`: Repository documentation.

## Tech Stack

- **Language / Environment**: Jupyter Notebook (Python 100%)

## Getting Started

### Prerequisites

To run this automation script, you will need to have Python and Jupyter Notebook installed on your system. You can install them via Anaconda or using `pip`:

```bash
pip install notebook
```

### Installation & Usage

1. **Clone the repository** to your local machine:
   ```bash
   git clone https://github.com
   ```

2. **Navigate into the directory**:
   ```bash
   cd lyntica_property_management_system
   ```

3. **Launch the Jupyter Notebook environment**:
   ```bash
   jupyter notebook
   ```

4. Open `Monthly Bill Generator.ipynb` from the dashboard, input your tenant's data (rent, utility readings, and previous balance), and run the cells to generate the bill summary.

## License

This project is open-source. Feel free to modify and adapt it to your specific property management needs.
