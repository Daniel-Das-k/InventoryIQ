# InventoryIQ

InventoryIQ is a simple inventory management system created for the requirements of a company.

## About

InventoryIQ is capable of keeping track of incoming and outgoing stock with a dynamically rendered bill. Each supplier is provided with a profile where they can see the history of their transactions with the company.

## Features

- Interactive Chart to display current available stock
- Stock details like current available stock are maintained
- Incoming transactions are done through purchases
- Outgoing transactions are done through sales
- Every transaction performed through the software is recorded
- Bill is dynamically rendered and can be printed
- Separate profiles are maintained for suppliers

## Developers

- Daniel Das K
- Fazil S
- Gowthaman J

## How to Run

To run InventoryIQ locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Daniel-Das-k/InventoryIQ.git
   
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   
3. Navigate to the project directory:
   ```bash
   cd InventoryIQ

4. Apply database migrations:
   ```bash
   python manage.py migrate

5. Create a superuser (admin account):
   ```bash
   python manage.py createsuperuser

6. Run the application:
   ```bash
   python manage.py runserver

