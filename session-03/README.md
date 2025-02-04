# Network Models

## 1. OSI Model (Reference Model)
### Purpose:
The OSI (Open Systems Interconnection) model is a conceptual framework that standardizes network communication functions, ensuring interoperability between different systems.

### Layers:
The OSI model consists of seven layers, each with a specific function:
1. **Physical Layer** – Handles raw data transmission over physical media.
2. **Data Link Layer** – Manages data framing, error detection, and MAC addressing.
3. **Network Layer** – Handles logical addressing (IP) and routing of packets.
4. **Transport Layer** – Ensures reliable or best-effort data delivery (TCP/UDP).
5. **Session Layer** – Manages and controls connections between applications.
6. **Presentation Layer** – Handles data translation, encryption, and compression.
7. **Application Layer** – Provides end-user services like HTTP, FTP, and email.

### Architecture:
The OSI model follows a layered approach, allowing modular design and interoperability. Each layer communicates only with adjacent layers through well-defined interfaces.

![Image](https://github.com/user-attachments/assets/a547df88-3ce1-4e10-9474-35c210228688)
---

## 2. TCP/IP Model (Commercial Model)
### Purpose:
The TCP/IP (Transmission Control Protocol/Internet Protocol) model is a practical, real-world networking model that serves as the foundation for the internet and most modern networks.

### Layers:
The TCP/IP model consists of four layers:
1. **Physical Layer** - The physical layer does the same job as the OSI model physical layer, i.e., transmitting data to the destination via physical hardware. This layer can also be a part of the network interface layer in the TCP/IP model. 
2. **Network Interface Layer** – Corresponds to the OSI Physical & Data Link layers, handling hardware addressing and media access.
3. **Internet Layer** – Maps to the OSI Network layer, responsible for IP addressing and routing.
4. **Transport Layer** – Similar to the OSI Transport layer, using TCP for reliable communication and UDP for fast, connectionless communication.
5. **Application Layer** – Combines OSI’s Session, Presentation, and Application layers, supporting protocols like HTTP, FTP, DNS, and SMTP.

### Architecture:
The TCP/IP model is designed to be flexible and scalable, supporting a vast range of devices and networks. It enables end-to-end communication, ensuring reliable data transmission across the internet.

![Image](https://github.com/user-attachments/assets/ebda0a11-ff3f-4739-ae69-115386c12b53)
