# WhatsApp Message Automation Script

## Overview
This Python script automates the process of sending WhatsApp messages via WhatsApp Web using the Selenium WebDriver. It is useful for automating the sending of predefined messages to multiple contacts. The script works by navigating to the WhatsApp Web interface, locating the message input field, and sending the specified message to a contact.

## Features
- Automates the process of sending messages on WhatsApp Web.
- Supports sending messages to multiple contacts.
- Uses Selenium WebDriver for browser automation.
- Configurable message content and recipient numbers.

## Requirements
- Python 3.x
- Selenium
- Chrome WebDriver
- `webdriver_manager` (for managing ChromeDriver automatically)

### Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/ShresthKhanna-python/Whatsapp-Automation.git
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

    **Note**: The `requirements.txt` file should include:
    ```txt
    selenium
    webdriver_manager
    ```

3. Make sure you have Google Chrome installed and that the latest version of `chromedriver` is compatible with it. The `webdriver_manager` automatically handles this for you.

## Usage

1. Open the script and modify the `numbers` list with the recipient's phone numbers. Make sure the numbers are in the international format (e.g., `+919873311622`).
2. Set the desired message you want to send in the `message` variable.
3. Run the script:
    ```bash
    python whatsapp_message_automation.py
    ```

4. You will need to scan the QR code on WhatsApp Web manually when prompted. After the QR code is scanned, the script will automatically send the messages to the specified contacts.

## Notes
- You may need to adjust the timing or XPath based on the responsiveness of WhatsApp Web or changes in its layout.
- Ensure the contacts you wish to message are already registered on WhatsApp Web.

## Contributing
If you would like to contribute to this project, feel free to fork the repository and submit a pull request. Contributions are always welcome!

## License
This project is open-source and available under the [MIT License](LICENSE).
