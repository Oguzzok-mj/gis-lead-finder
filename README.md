# MapLeads (GIS Lead Finder)

A desktop application written in C++ that helps automate B2B lead generation by searching local businesses on 2GIS and filtering out those that don't have an official website. Perfect for web studios, marketers, and local business service providers.

## 🚀 Features

*   **Interactive 2GIS Map Integration:** Visual display of organizations and search areas.
*   **Targeted Search:** Query businesses by category (e.g., cafes, auto services, dental clinics) and location.
*   **Smart Filtering:** Automatically parses API responses to isolate companies lacking a website (`website` field is empty).
*   **Data Export:** Saves filtered leads with titles, phone numbers, and addresses for easy outreach.
*   **Fast & Lightweight:** Built with modern C++ for high performance.

## 🛠 Tech Stack

*   **Language:** C++ (C++17 or newer)
*   **API:** 2GIS Catalog API & Maps API
*   **Libraries:** 
    *   `libcurl` (for network HTTP requests)
    *   `nlohmann/json` (for JSON parsing)
    *   `Qt / QWebEngineView` (for GUI and map rendering)

## ⚙️ Installation & Setup

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/gis-lead-finder.git](https://github.com/your-username/gis-lead-finder.git)
