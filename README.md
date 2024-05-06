# Postal Points Integration

This repository contains HTML components for displaying postal service points for "Poczta Polska" and Inpost "Paczkomaty". Below you will find the descriptions and usage instructions for each component.

## Components

### 1. Poczta Polska Points Map (`pocztex_punkty.html`)

#### Description
This component integrates a map displaying various types of service points including post offices, ORLEN stations, and parcel lockers associated with Poczta Polska. It utilizes the `ppwidget.js` from Poczta Polska for map functionality.

#### Features
- Dynamically loads points onto the map based on the selected service types.
- Displays detailed information about each point in a popup.
- Information about the selected point is saved to `localStorage`.

#### Usage
To use this component, include it in your project and ensure the `ppwidget.js` script is properly linked. The map requires a container with full height and width to display correctly.

### 2. Inpost Paczkomaty Map (`inpost_paczkomat.html`)

#### Description
This HTML file integrates the Inpost Geowidget to display Paczkomaty locations across Poland. The component uses Inpost's official SDK to render the map and handle user interactions.

#### Features
- Utilizes the Geowidget from Inpost to display parcel lockers on a map.
- Allows users to interactively select a Paczkomat and view details such as ID and address.
- Saves the selected Paczkomat information to `localStorage`.

#### Usage
Make sure to include the `sdk-for-javascript.js` and `easypack.css` from Inpost's resources to enable full functionality. The component captures click events on the map to trigger details display and data storage.

## General Notes

- Both components are designed to be embedded directly into HTML pages.
- Ensure that your web application has access to the internet to load external scripts and map data.
- Local storage is used to save selected points for later retrieval during the session or after reloading the page.

## Contributing

Contributions to improve these components are welcome. Please adhere to standard web development best practices when proposing changes.

---

For any issues or further assistance, please open an issue on the repository or contact the support team.
