# PortCraft - IP Subnet Calculator & Network Tool Suite

A comprehensive network engineering tool suite featuring IPv4/IPv6 CIDR subnet calculations, binary visualizers, and common port references.

## Features

- **IPv4 & IPv6 Subnet Calculator**: IPv4 & IPv6 Subnet Calculator: calculate network address, broadcast address, usable host ranges, and total hosts from any CIDR mask
- Visual binary breakdown displaying network bits vs. host bits in real-time
- Subnet mask cheatsheet (/8 through /32) with CIDR notation and wildcards
- Common network port reference lookup table (HTTP, HTTPS, SSH, FTP, DNS, MySQL, etc.) with search filter
- IP address class detection (Class A, B, C, Private, Loopback, Multicast)
- One-click copy for all computed network parameters

## Tech Stack

- HTML5
- CSS3
- JavaScript (ES6+)
- Tailwind CSS
- Font Awesome

## Screenshots

<!-- TODO: Add application screenshots here -->
![PortCraft - IP Subnet Calculator & Network Tool Suite Screenshot](https://via.placeholder.com/800x450.png?text=PortCraft+-+IP+Subnet+Calculator+and+Network+Tool+Suite)

## Folder Structure

```
PortCraft---IP-Subnet-Calculator-Network-Tool-Suite/
├── portcraft_ip_subnet_calculator_network_tool_suite.html
└── README.md
```

## Installation & Setup

This is a standalone, client-side web application. No complex build pipelines, database configurations, or package installations are required.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SSManikandaprabu/PortCraft---IP-Subnet-Calculator-Network-Tool-Suite.git
   cd PortCraft---IP-Subnet-Calculator-Network-Tool-Suite
   ```

2. **Run the application:**
   - **Direct Browser Launch**: Double-click `portcraft_ip_subnet_calculator_network_tool_suite.html` to open it directly in any modern web browser (Chrome, Firefox, Safari, Edge).
   - **Or via Local HTTP Server**:
     ```bash
     python -m http.server 8000
     ```
     Then open [http://localhost:8000/portcraft_ip_subnet_calculator_network_tool_suite.html](http://localhost:8000/portcraft_ip_subnet_calculator_network_tool_suite.html) in your browser.

## Usage

1. Launch the application in your browser following the setup instructions above.
2. Interact with the application controls and input fields tailored for PortCraft - IP Subnet Calculator & Network Tool Suite.
3. Preferences and data are stored locally in your browser's LocalStorage where applicable.

## Environment Variables

None required. All IP bitwise logic runs locally in JavaScript.

## Live Demo Link

<!-- TODO: Add live demo link once deployed (e.g. GitHub Pages or Vercel) -->
_No live demo link currently configured. Refer to the TODO section below._

## Project Roadmap & TODOs

- [ ] Add screenshot of subnet breakdown and port directory

## Author

- **S.S. Manikanda Prabu** - [GitHub Profile](https://github.com/SSManikandaprabu)
