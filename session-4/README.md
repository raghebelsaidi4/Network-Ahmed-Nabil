# Network Protocols

## Application Layer

### 1. HTTP (HyperText Transfer Protocol)
- **Protocol**: A set of rules using a group of programming languages.
- **HyperText**: Supports rich text, audio, video, and other multimedia elements.
- **Usage**: Used for browsing the web and communication between a client and a web server.

### 2. FTP (File Transfer Protocol)
- **Purpose**: Designed for transferring large files.
- **Usage**: Used for uploading and downloading files between a client and a file server.

### 3. SMTP (Simple Mail Transfer Protocol)
- **Usage**: Used for sending emails (e.g., Hotmail, Gmail).
- **How It Works**:
  - The email client connects to an SMTP server.
  - The server forwards the email to the recipient's email server.
  - The recipient retrieves the email using protocols like POP3 or IMAP.

### 4. POP3 (Post Office Protocol v3)
- **Purpose**: Used to retrieve emails from a mail server.
- **How It Works**:
  - The client connects to the mail server.
  - Emails are downloaded to the client’s local device.
  - Once downloaded, emails are typically deleted from the server.

### 5. Telnet
- **Usage**: Used for remote login and configuration of network devices.
- **Functionality**:
  - Allows users to access remote systems over a network.
  - Used primarily for system administration and troubleshooting.

---

## Transport Layer

The Transport Layer is responsible for reliable data transmission and communication between devices.

### Key Functions:

1. **Segmentation**
   - Divides large data into smaller parts called segments.
   - Each segment has a maximum size of **1460 bytes**.

2. **Error Detection**
   - Uses **Cyclic Redundancy Check (CRC)** (2 bytes) to ensure data integrity.

3. **Addressing**
   - Uses **software port numbers** (16-bit) ranging from **0 to 65535** for communication.

4. **TCP (Transmission Control Protocol) Specific Functions**
   - **Session Establishment**: Establishes a connection before data transfer.
   - **Session Management and Control**: Manages ongoing communication sessions.
   - **Session Termination**: Closes the connection after data transfer is complete.

---

