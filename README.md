# Wifi_Local_Messenger
Messaging application that allows users to communicate over local internet connections (Wi-Fi, ethernet, etc.). Connection is established by entering the local IP address of the other person (your local IP will be displayed to you for reference).

## Screenshots
![Alt text](https://github.com/bfaure/Wifi_Local_Messenger/blob/master/resources/test_screen_1.png)
![Alt text](https://github.com/bfaure/Wifi_Local_Messenger/blob/master/resources/test_screen_2.png)

## Usage
The main UI is launched by running ```python main.py``` from the base directory.

## Dependencies
Python 2.7, PyQt4

## Future Improvements
Allow for multiple users in the chat, show list of local IPs on network (ability to send chat invite to any), ability to send multimedia over network as well as text. Implement the encryption algorithms in the algo folder to encrypt messages passed over network, implement transfer protocol to validate message content, add 'name' to each local IP and show that name when they send a message.
