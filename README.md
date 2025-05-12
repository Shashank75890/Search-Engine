# 🔍 Simple Search Engine

A Java-based mini search engine that includes a **Web Crawler** and a **Search Engine** with a JSP/Servlet web interface. The crawler collects data from the web and indexes it, while the search engine provides a UI for users to search through the indexed data.

---

## 📁 Project Structure


---
SimpleSearchEngine/
├── WebCrawler/ # Java-based web crawler for collecting data
└── SearchEngine/ # JSP-based search UI built with Servlets

## 🚀 Features

### ✅ Web Crawler (`WebCrawler`)
- Starts crawling from a seed URL
- Fetches and parses HTML content
- Extracts and stores textual data
- Can be configured for crawling depth and page limits

### ✅ Search Engine (`SearchEngine`)
- Accepts search queries from the user
- Matches queries with indexed data
- Displays results in a clean JSP-based interface
- Tracks user search history

---

## 🛠️ Technologies Used

- **Java** (Core logic)
- **JSP / Servlets** (Web interface)
- **Apache Tomcat** (Web server)
- **MySQL** or **FileSystem** (Storage layer)
- **Maven** (Dependency management)
- **HTML / CSS** (Frontend)

---

## ⚙️ Setup Instructions

### 🔧 Prerequisites
Make sure you have the following installed:
- Java JDK 8 or higher
- Apache Tomcat 9+
- MySQL (optional, for storing user history/index)
- Maven
- IDE like IntelliJ IDEA or Eclipse

---
