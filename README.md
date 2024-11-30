**Name:**Anuj Singh Bhadauriya
**Company:**CODTECH IT SOLUTION
**ID:**CT08DS9744
**Duration:**October 30th,2024 to November 30th,2024
**Mentor:**

**OVERVIEW OF THIS CODE**

This C++ program is a simple network scanner that performs two main tasks: port scanning and banner grabbing. Here's a detailed explanation:

Features
Port Scanning:

It checks whether common ports (e.g., 21 for FTP, 22 for SSH, 80 for HTTP) are open on the target system.
Uses the socket API to create a connection to the target system on each port. If the connection is successful, the port is considered open.
Banner Grabbing:

If a port is open, the program sends an HTTP HEAD request to retrieve the response header from the target system.
Extracts details about the server and software (if available) from the response.
Common Ports Scanned:

Ports: 21 (FTP), 22 (SSH), 23 (Telnet), 25 (SMTP), 53 (DNS), 80 (HTTP), 110 (POP3), 143 (IMAP), 443 (HTTPS), and 8080 (Alternative HTTP).
How It Works
Input:

The program prompts the user to enter the target IP address or domain name.
Scanning:

Loops through a predefined list of ports.
For each port:
Tries to establish a connection.
If successful, the port is marked as open, and the program attempts banner grabbing.
Output:

Displays whether each port is open or closed.
For open ports, the server's banner information (if available) is printed.
Completion:

After scanning all ports, the program prints "Scan complete."

**OUTPUT**

![Screenshot 2024-11-30 124616](https://github.com/user-attachments/assets/3c1eef23-8d07-4cf6-9a92-625b71570b66)

