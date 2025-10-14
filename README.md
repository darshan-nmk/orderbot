# OrderBot

This repository combines two major components of the OrderBot ecosystem:

- **dashboard_backend**: The AI-driven order management and dashboard backend (from the [orderbot](https://github.com/darshan-nmk/orderbot) repository)
- **intent_handler**: The FastAPI-based intent handler service (from the [orderbot-intent_handler](https://github.com/darshan-nmk/orderbot-intent_handler) repository)

---

## dashboard_backend

### Overview

A multi-tenant SaaS application that allows businesses to create custom Telegram chatbots for order management using Dialogflow NLP. Each business gets their own isolated database and customized chatbot for managing orders, products, and inventory.

### Features

- 🔒 Multi-tenant architecture with isolated databases
- 🤖 Dialogflow NLP integration for natural conversations
- 💬 Telegram bot integration for each business
- 📊 Real-time order tracking dashboard
- 🏪 Product and inventory management
- 📈 Sales reporting and analytics
- 🌐 Responsive web interface

### Tech Stack

- **Backend**: Python 3.8+, Flask
- **Frontend**: HTML5, CSS3, JavaScript
- **Database**: MySQL 8.0+
- **AI/NLP**: Google Dialogflow
- **Chat Platform**: Telegram Bot API

### Setup & Usage

Please refer to `dashboard_backend/README.md` for detailed installation, configuration, and usage instructions.

---

## intent_handler

### Overview

A FastAPI-based backend service that handles intents for a restaurant chatbot system. The system supports multiple restaurants through dynamic database connections and provides order management capabilities.

### Features

- Multi-restaurant support through dynamic database connections
- Order management and tracking
- Menu management
- Customer information handling
- Session-based order processing
- Real-time order status updates

### Setup & Usage

Please refer to `intent_handler/README.md` for detailed installation, configuration, and usage instructions.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Authors

- Nagamanikandan (@darshan-nmk)

## Acknowledgments

- Google Cloud Platform
- Telegram Bot API
- Flask & FastAPI Communities
- MySQL Community
