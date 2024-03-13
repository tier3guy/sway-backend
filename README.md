# Sway Backend 🗳️

> Empowering anonymous polling through blockchain technology.

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![GitHub Issues](https://img.shields.io/github/issues/tier3guy/sway)](https://github.com/tier3guy/sway/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/tier3guy/sway)](https://github.com/tier3guy/sway/pulls)

---

## Table of Contents

-   [About](#about)
-   [Features](#features)
-   [Installation](#installation)
-   [Usage](#usage)
-   [Blockchain Integration](#blockchain-integration)
-   [Contributing](#contributing)
-   [License](#license)

---

## About

Sway is a backend service designed to facilitate anonymous polling using blockchain technology. It provides the core functionality for creating polls, recording votes, and securely managing poll data.

---

## Features

✅ **Anonymous Polls:** Users can create polls and vote without revealing their identities.

🔗 **Blockchain Integration:** Utilizes blockchain to secure and validate poll transactions.

📊 **Real-time Results:** Instantly view the results as votes are cast.

🔐 **Security:** Ensures the confidentiality and integrity of poll data.

🌐 **Scalability:** Designed for high performance and scalability to handle large volumes of polls and votes.

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/tier3guy/sway
```

2. Navigate to the project directory:

```bash
cd sway
```

3. Create a virtual environment (optional but recommended):

```bash
python -m venv venv
```

4. Activate the virtual environment:

```bash
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
```

5. Install dependencies:

```bash
pip install -r requirements.txt
```

6. Set up the database and configure blockchain integration.

7. Configure the `.env` file as explained in the `.env.example` file.

---

## Usage

1. Run the application:

```bash
uvicorn app.main:app --reload
```

2. Use Sway's API endpoints to create polls, retrieve poll data, and record votes.

3. Implement client-side functionality to interact with the backend service.

4. Ensure secure communication between the frontend and backend components.

5. Explore real-time results and analytics through the provided endpoints.

---

## Blockchain Integration

Sway leverages blockchain technology to enhance the security and transparency of the polling process. Each vote is recorded as a transaction on the blockchain, providing a tamper-resistant and verifiable record.

---

## Contributing

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Submit a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to reach out to us if you have any questions or feedback. Happy coding! 🚀