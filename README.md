# Kali Linux WiFi Interface Issue Fixes

Repository containing troubleshooting solutions for resolving WiFi interface issues in Kali Linux, particularly after monitor mode usage.

## Solutions

- Disable monitor mode and reset the WiFi interface.
- Restart Network Manager to apply changes.
- Verify interface status using `ip a` or `iwconfig`.

## Usage

Follow these steps to reset your WiFi interface in Kali Linux after monitor mode:

1. Disable monitor mode on the WiFi interface.
2. Rename the interface back to its original name (`wlan0`).
3. Bring the interface up and restart Network Manager.

## Contributing

Contributions are welcome! To contribute to this repository, please fork the repository and submit a pull request with your changes. For major changes, please open an issue first to discuss potential updates.

## License

This project is licensed under the [MIT License](LICENSE).
