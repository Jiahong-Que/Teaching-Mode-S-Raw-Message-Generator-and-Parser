# Teaching-Mode-S-Raw-Message-Generator-and-Parser
Teaching Mode-S Raw Message Generator and Parser

# ADS-B Raw Data Decoder

A lightweight Python tool for understanding and decoding **ADS-B raw data** into structured **ADS-B messages**.

## ✈️ Project Purpose

This project is designed to help users better understand:
- The relationship between **raw ADS-B signals** and **decoded ADS-B messages**.
- The **transformation process** from binary data to structured message formats.
- The internal **message structure** and how each field (such as DF, CA, ICAO address, Type Code, etc.) is extracted and interpreted.

It is intended as a learning resource for aviation data enthusiasts, researchers, and students working with ADS-B systems.

## ⚙️ Key Features

- **Binary Conversion**: Handles the translation from raw data bits into human-readable format.
- **Message Structure Parsing**: Breaks down messages according to the ADS-B protocol, identifying all key fields.
- **Field Extraction**: Recovers important aviation information such as aircraft identification, position, and velocity.
- **Step-by-Step Decoding Process**: Helps users see exactly how raw bits become meaningful ADS-B information.

## 📚 How It Works

The decoding process follows these steps:
1. **Raw Data Input**: Start with a raw ADS-B message frame (binary or hex format).
2. **Hex to Binary Conversion**: Convert hexadecimal input into a full binary string.
3. **Bitstream Parsing**: Segment the binary stream based on the ADS-B message specification.
4. **Field Interpretation**: Decode fields like:
   - Downlink Format (DF)
   - Capability (CA)
   - ICAO Address
   - Type Code (TC)
   - Additional information depending on TC (e.g., aircraft identity, airborne position, airborne velocity)
5. **Output Structured Information**: Present decoded information in a clear, readable format.

## 🚀 Getting Started

### Prerequisites
- Python 3.x

### Example

You can input a sample raw ADS-B message and observe how the fields are decoded step-by-step.

Example input (hex):
```
8D40621D58C382D690C8AC2863A7
```
Output will show each field's interpretation.

## 💬 Contributing

Contributions are welcome!  
Feel free to open an issue, submit a pull request, or start a discussion if you have ideas for improvements.

## 📄 License

This project is open-sourced under the [MIT License](LICENSE).

## 📬 Contact

For questions, suggestions, or collaboration, feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/jiahong-que-215428258/) or open an issue.

---

# Tags
`ADS-B` `Raw Data` `Binary Decoding` `Message Parsing` `Aviation Data` `Python
