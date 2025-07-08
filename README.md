# Scan Ride Project

This is a mini-project developed as part of my BE EEE coursework. It focuses on enabling secure vehicle ignition using QR code scanning and passkey verification through a mobile website interface.

## 💻 *Project Overview*

- A user scans a QR code attached to the bike using their mobile phone.
- The QR leads to a website where the user enters a *passkey*.
- If the *passkey is correct*:
  - The user is redirected to a *map page*.
  - The bike starts automatically via relay activation.
- If the *passkey is incorrect*:
  - The website displays *“Passkey Incorrect”*, and the bike remains off.

---

## 🌐 *Live Demo*

Currently, this project uses **direct website access** instead of a QR code. You can visit the project website here:

🔗 [Scan Ride Website](https://scan-ride.vercel.app/)

In the future, this can be integrated with a QR code for quick scanning and redirection to the website.

---

## ⚙ *Technologies & Components Used*

- *Arduino IDE*
- *NodeMCU (ESP8266)*
- *Relay Module*
- *Mobile Website Interface (HTML, CSS, JS)*
- *QR Code for website link*

---

## 📚 *What I Learned*

- Integrating *hardware and web technologies* for IoT-based solutions
- Working with *NodeMCU and relay modules*
- Developing *simple web interfaces* for user interaction
- Secure passkey validation logic

---

## 🚀 *Future Improvements*

- Implement OTP-based verification for higher security  
- Store user data securely using a database and server  
- Integrate Google Maps API for live vehicle tracking  
- Develop a complete Android app for better UI/UX

---

> This project was completed during my 4th semester project based learning course work (Jan 2025 - May 2025).
---

### 📸 *Demo & Screenshots*


Below are sample screenshots of the project interface:

#### Page 1 – Correct Passkey
![Page 1 – Correct Passkey](Page%201.jpg)

#### Page 1 – Incorrect Passkey
![Page 1 – Incorrect Passkey](Page%201%20-%20incorrect%20passkey.jpg)

#### Page 2 – Map Page
![Page 2 – Map Page](Page%202.jpg)


