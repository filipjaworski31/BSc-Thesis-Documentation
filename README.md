(English version/ polish below)

# Interactive Real-Time Event Map (B.Sc. Engineering Thesis)

This repository contains the official documentation for my Bachelor of Science engineering thesis, titled **"Design and Implementation of an Interactive Real-Time Event Map Web Application"**. The project was developed at the Warsaw University of Technology, Faculty of Electronics and Information Technology.

The primary goal of this project was to design, develop, and deploy a full-stack, serverless web application that allows users to discover and browse events happening in their vicinity in real-time.

---

## 📜 Project Overview

The application provides an interactive map interface where events are dynamically displayed as markers. Users can filter events based on various criteria, view event details, and (in future versions) interact with the community through reviews and ticket purchasing integrations.

The entire architecture is built upon a **serverless model** on **Google Cloud Platform (GCP)**, ensuring high scalability, performance, and cost-efficiency by leveraging managed services and eliminating the need for traditional server management.

---

## 🛠️ Core Technologies & Architecture

This project demonstrates a modern, cloud-native approach to web development. The key components of the tech stack include:

### **Frontend**
* **React:** A declarative JavaScript library for building dynamic and responsive user interfaces.

### **Backend**
* **Node.js:** A JavaScript runtime environment used to build the server-side logic of the application.

### **Cloud & DevOps**
* **Google Cloud Platform (GCP):** The core cloud provider for all infrastructure services.
    * **Cloud Run:** For deploying and scaling the containerized backend application.
    * **Cloud Functions:** For handling event-driven, serverless computations (e.g., notifications).
    * **Cloud SQL (PostgreSQL):** A fully managed relational database for storing application data.
    * **Firebase Hosting & Cloud Storage:** For hosting the static frontend assets and storing user-generated files.
    * **Firebase Authentication:** For managing user identity, registration, and login.
    * **Cloud Build:** For automating the CI/CD pipeline (building, testing, and deploying).
* **Docker:** For containerizing the backend application, ensuring consistency across development and production environments.
* **Kubernetes:** For orchestrating and managing the containerized application at scale.

### **External APIs**
* **Google Maps API:** For providing the core interactive map functionality, geocoding, and location services.
* **Facebook Graph API:** For sourcing event data from the Facebook platform.

---

## 📄 Documentation

This repository contains the final thesis report in PDF format, which includes:
* In-depth analysis of the chosen technologies.
* Architectural diagrams and design decisions.
* Detailed functional specification of the application.
* An overview of the development and deployment phases.

**[Link to Thesis PDF](./BSc-Thesis-Documentation.pdf)**

> **Note:** The source code for this project is currently in a private repository pending cleanup of sensitive keys and credentials. It can be made available upon request for recruitment purposes.

---

## 🧑‍💻 Author

* **Filip Jaworski**
    * [LinkedIn Profile](https://linkedin.com/in/filip-j-376b212b5)
    * [GitHub Profile](https://github.com/fiilipjaworski31)
 
---

# Interaktywna mapa wydarzeń w czasie rzeczywistym (licencjat. Praca inżynierska)

To repozytorium zawiera oficjalną dokumentację mojej pracy licencjackiej z inżynierii, zatytułowanej ** „Projektowanie i wdrażanie interaktywnej aplikacji internetowej z mapą zdarzeń w czasie rzeczywistym"**. Projekt został opracowany na Politechnice Warszawskiej, Wydziale Elektroniki i Informatyki.

Głównym celem projektu było zaprojektowanie, opracowanie i wdrożenie pełnozakresowej, bezserwerowej aplikacji internetowej, która umożliwi użytkownikom odkrywanie i przeglądanie zdarzeń mających miejsce w ich pobliżu w czasie rzeczywistym.

---

## 📜 Przegląd projektu

Aplikacja zapewnia interaktywny interfejs mapy, w którym zdarzenia są dynamicznie wyświetlane jako znaczniki. Użytkownicy mogą filtrować zdarzenia na podstawie różnych kryteriów, przeglądać szczegóły zdarzeń i (w przyszłych wersjach) wchodzić w interakcje ze społecznością za pośrednictwem recenzji i integracji przy zakupie biletów.

Cała architektura opiera się na **modelu bezserwerowym** na **Google Cloud Platform (GCP)**, zapewniając wysoką skalowalność, wydajność i efektywność kosztową poprzez wykorzystanie zarządzanych usług i eliminację potrzeby tradycyjnego zarządzania serwerami.

---

## 🛠️ Podstawowe technologie i architektura

Projekt ten prezentuje nowoczesne, oparte na chmurze podejście do tworzenia stron internetowych. Kluczowe elementy stosu technologicznego obejmują:

### **Frontend**
* **React:** Deklaratywna biblioteka JavaScript służąca do tworzenia dynamicznych i responsywnych interfejsów użytkownika.

### **Zaplecze**
* **Node.js:** Środowisko wykonawcze JavaScript służące do budowania logiki aplikacji po stronie serwera.

### **Chmura i DevOps**
* **Google Cloud Platform (GCP):** Główny dostawca chmury dla wszystkich usług infrastrukturalnych.
    * **Cloud Run:** Do wdrażania i skalowania kontenerowej aplikacji zaplecza.
    * **Funkcje chmury:** Do obsługi obliczeń sterowanych zdarzeniami, bezserwerowych (np. powiadomień).
    * **Cloud SQL (PostgreSQL):** W pełni zarządzana relacyjna baza danych służąca do przechowywania danych aplikacji.
    * **Hosting Firebase i przechowywanie w chmurze:** Do hostowania statycznych zasobów front-endu i przechowywania plików generowanych przez użytkowników.
    * **Uwierzytelnianie Firebase:** Do zarządzania tożsamością użytkownika, rejestracją i logowaniem.
    * **Kompilacja w chmurze:** Do automatyzacji procesu CI/CD (kompilacja, testowanie i wdrażanie).
* **Docker:** Do konteneryzacji aplikacji zaplecza, zapewniając spójność w środowiskach programistycznych i produkcyjnych.
* **Kubernetes:** Do organizowania i zarządzania aplikacją kontenerową na dużą skalę.

### **Zewnętrzne API**
* **Google Maps API:** Do zapewniania podstawowej interaktywnej funkcjonalności map, geokodowania i usług lokalizacyjnych.
* **Facebook Graph API:** Do pozyskiwania danych o zdarzeniach z platformy Facebook.

---

## 📄 Dokumentacja

To repozytorium zawiera końcowy raport z pracy dyplomowej w formacie PDF, który zawiera:
* Dogłębna analiza wybranych technologii.
* Schematy architektoniczne i decyzje projektowe.
* Szczegółowa specyfikacja funkcjonalna aplikacji.
* Przegląd faz rozwoju i wdrażania.

**[Link do pracy inżynierskiej PDF](./BSc-Thesis-Documentation.pdf)**

> **Uwaga:** Kod źródłowy tego projektu znajduje się obecnie w prywatnym repozytorium w oczekiwaniu na oczyszczenie poufnych kluczy i danych uwierzytelniających. Można go udostępnić na żądanie w celach rekrutacyjnych.

---

## 🧑‍💻 Autor

* **Filip Jaworski**
    * [LinkedIn Profile](https://linkedin.com/in/filip-j-376b212b5)
    * [GitHub Profile](https://github.com/fiilipjaworski31)
