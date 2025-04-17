# Aether Social

**Aether Social** is an open-source and free social network, designed to provide a privacy-respecting alternative to traditional social platforms. Our mission is to create a space where users can interact freely while having full control over their data.

## Features

- **Open-Source**: The source code is fully available and can be modified by anyone.
- **Privacy-Respecting**: No collection of personal data without explicit consent.
- **Decentralized**: Uses decentralized technologies to avoid censorship and single points of failure.
- **Interoperability**: Compatible with other decentralized social networks via standard protocols.
- **Active Community**: A community of passionate developers and users actively contributing to the project.

## Installation

To install Aether Social on your own server, follow these steps:

### Prerequisites

- Node.js (version 14 or higher)
- npm (version 6 or higher)
- MongoDB (version 4 or higher)

### Installation Steps

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Sky-Genesis-Enterprise/aether-social.git
   cd aether-social
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Configure the environment**:
   Create an `.env` file at the root of the project and add the necessary environment variables:

   ```env
   MONGO_URI=your_mongodb_uri
   PORT=3000
   SECRET_KEY=your_secret_key
   ```

4. **Start the server**:

   ```bash
   npm start
   ```

5. **Access the application**:
   Open your browser and go to `http://localhost:3000`.

## Contribution

We encourage community contributions! If you would like to contribute to Aether Social, please follow these steps:

1. **Fork the repository**:
   Create a copy of the repository on your own GitHub account.

2. **Create a branch**:

   ```bash
   git checkout -b feature/your-new-feature
   ```

3. **Make your changes**:
   Add your changes and commit them.

4. **Submit a Pull Request**:
   Push your changes to your fork and submit a Pull Request to the main repository.

## License

Aether Social is distributed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or suggestions, feel free to contact us at contact@skygenesisenterprise.com
