# WGCF-UI - WGCONFIG Generator

**WGCONFIG Generator** is a modern, user-friendly web application that allows you to generate free **Target WireGuard configurations** powered by Cloudflare's WARP service.

![WGCONFIG Logo](logo.png)

## 🚀 Features

- **Instant Account Generation**: Creates a new Cloudflare WARP account and generates a valid WireGuard configuration in seconds.
- **Cross-Platform Support**: Generates configs optimized for both **Mobile (Android/iOS)** and **PC (Windows/Mac/Linux)**.
- **QR Code Support**: Automatically generates a QR code for easy scanning with the WireGuard mobile app.
- **Edit & Customization**: Allows you to modify the generated config (e.g., change `AllowedIPs` or `DNS`) directly in the UI. The QR code updates automatically!
- **Educational Content**: Includes a built-in "Read More" modal explaining what WireGuard is and why Cloudflare WARP is a great choice.
- **Validations**: Ensures device names and IP ranges (CIDR) are valid before generation.
- **Privacy Focused**: No logs are stored. The tool acts as a bridge to Cloudflare's API.

## ▶️ How to Use

1.  **Open the Application**:
    Navigate to the application URL (or `[https://wgcf-ui.blogspot.com/](https://wgcf-ui.blogspot.com/)`).

2.  **Generate Config**:
    - Enter a **VPN Name** (e.g., "My Phone").
    - Select your **Device Type** (Android or PC).
    - Click **Generate Config**.

3.  **Connect**:
    - **Mobile Users**: Open the WireGuard app, tap **+**, select **Scan from QR code**, and scan the code displayed on the screen.
    - **PC Users**: Click **Download Config** to save the `.conf` file, then import it into your WireGuard client.

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Abdi Syahputra Harahap (Maskoding)**
- Website: [www.Maskoding.com](https://www.Maskoding.com)
- GitHub: [maskodingku](https://github.com/maskodingku)
