# Shopon — CLI Shopping Cart

A Python terminal-based shopping cart application featuring category-based GST calculations (Electronics, Fashion, Stationaries), multiple payment options (Credit Card with WhatsApp OTP, UPI QR, Cash on Delivery), and automated receipt generation.

---

##  Features
- **User authentication** simulating login with username/password.
- **Category-based GST** rates:
  - Electronics: 18%
  - Fashion: 12%
  - Stationaries: 8%
- **Multiple payment methods**:
  - Credit Card (with OTP via WhatsApp)
  - Scan & Pay (UPI QR code)
  - Cash on Delivery
- **Automatic receipt generation** stored in `receipt.txt`.

---

##  Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Technology Stack](#technology-stack)
- [Planned Improvements](#planned-improvements)
- [License](#license)

---

##  Installation

1. **Clone the repository**:
   ```bash
2 Install dependencies (if any, e.g., qrcode, pywhatkit):

bash
Copy
Edit
pip install qrcode pywhatkit
Usage
Run the application:

bash
Copy
Edit
python <your_main_file>.py
Enjoy a command-line interface where you:

Log in with predefined credentials.

Browse categories: Electronics, Fashion, Stationaries.

Add items to your cart.

View your cart, see GST applied, and choose payment.

Receive a generated receipt in the file receipt.txt.

How It Works
The app stores catalog items as tuples (product ID, name, price, category).

GST is calculated based on item category.

Payment options:

Credit Card: Prompts for OTP via WhatsApp message using pywhatkit.

Scan and Pay: Generates a UPI QR code via qrcode library.

Cash on Delivery: Confirms the order and generates receipt.

Every purchase writes a detailed receipt including invoice number, timestamp, product details, and payment method to receipt.txt.

Technology Stack
Python — Core language.

qrcode — Generates UPI QR codes for payments.

pywhatkit — Sends OTP via WhatsApp.

Standard Library — For file operations, random numbers, timestamps.

Planned Improvements
Add unit tests for GST calculations and cart logic.

Enhance error handling and input validation.

Modularize code into multiple files or a package.

Add logging and config-driven payment options.

Refactor credit card validation to be more realistic (e.g., Luhn algorithm).

License
This project is released under the MIT License. See the LICENSE file for more details.

yaml
Copy
Edit

---

### Why This Works:
- Clear **overview** outlining purpose and features. :contentReference[oaicite:1]{index=1}
- **Installation** and **usage** sections make it easy for users to get started. :contentReference[oaicite:2]{index=2}
- **Technology stack** helps highlight tools and skills.
- **Planned improvements** showcase future work and professionalism.
- **License** section clarifies permissions and rights.

   git clone https://github.com/YourUsername/Rolex.git
   cd Rolex
