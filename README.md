# IPScout

## 🌐 IP Intelligence Gathering Tool

IP Intelligence Gathering Tool is an interactive Python application designed to perform bulk queries for IP addresses using APIs from multiple services. Quickly gather and analyze abuse reports, geolocation data, detailed IP information, and authoritative registry data in a single, unified interface.

**[View code](https://nbviewer.org/github/Blodarn/ipscout/blob/main/ipscout.ipynb)**

## ✨ Key Features

- 🛡️ **AbuseIPDB Integration**: Fetch abuse score, ISP reports, and last reported time for IPs.
- 🗺️ **IPGeolocation.io Integration**: Retrieve geolocation details such as country, city, latitude, and longitude.
- 🏷️ **IPInfo Integration**: Extract Autonomous System Number (ASN), domain details, and related information.
- 📜 **ARIN RDAP Integration**: Query authoritative registry data (e.g., net range, registration details).
- 🔗 **Multi-Source Merge**: Combine results from multiple services into a unified table for comparison.
- 🖥️ **Interactive GUI**: User-friendly interface with buttons for each service or for querying all services at once.
- 📤 **Export Results**: Download query results as a CSV file for further analysis.
- ⚡ **Parallel Processing**: Leverages multithreading for fast query execution on multiple IPs.

## 🖼️ Preview

## 🚀 How to Use

1. **🔎 Input IP Addresses**: Enter one or more IP addresses (comma-separated) in the input field.
2. **🛠️ Choose a Service**: Click a service button (e.g., *Check AbuseIPDB*) or *Check All* to query all services.
3. **📊 View Results**: Results are displayed interactively in a styled table.
4. **📁 Export Data**: Export the table as a CSV using the "Export to CSV" button.
5. **🧹 Clear Output**: Use the "Clear Output" button to reset the display.

## 📋 Requirements

- 🐍 **Python 3.8+**
- Required Python libraries:
  - `requests`
  - `pandas`
  - `ipywidgets`
  - `tqdm`
- API keys for the following services:
  - [AbuseIPDB](https://www.abuseipdb.com/)
  - [IPGeolocation.io](https://ipgeolocation.io/)
  - [IPInfo.io](https://ipinfo.io/)

## 💻 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/ip-intelligence-tool.git
   cd ip-intelligence-tool
2. Run the application in a Jupyter Notebook: [JupyterHub](https://jupyter.org/install)
3. Open the notebook file and run all cells
4. Input your IP list separated by comma

## 📜 License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). See the LICENSE file for details.

## 🤝 Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to improve this tool.

## 🙏 Acknowledgments
Special thanks to:
- 🛡️ AbuseIPDB
- 🗺️ IPGeolocation.io
- 🏷️ IPInfo.io
- 📜 ARIN RDAP
