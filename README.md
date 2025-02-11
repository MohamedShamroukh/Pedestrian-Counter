# Pedestrian Counter

A simple, elegant, and mobile-friendly web application for counting pedestrians in a specific area.  This application stores data locally and allows for exporting the count data as a CSV file.

## Features

*   **Clean and Elegant Design:**  A user-friendly interface designed for simplicity and ease of use, especially on mobile devices.
*   **Mobile-First Approach:** Optimized for phone displays, with larger, touch-friendly buttons and a responsive layout.
*   **Local Data Storage:**  Persistently stores count data in the browser's local storage, so data is preserved across sessions.
*   **CSV Export:**  Allows exporting the collected count data as a CSV file for further analysis or record-keeping.  Includes the area name in the filename.
*   **Area Name Input:** Prompts the user to enter an area name, which is used in the CSV export and displayed on the page.
*   **Reset Functionality:**  Provides a button to reset the counter and clear the stored data (with an option to export the data first).
*   **Timestamped Log:** Records the timestamp and count for each increment, displayed in a log area on the page.

## Usage

1.  **Enter Area Name:**  On the first visit, or after clearing the data, you will be prompted to enter the name of the area you are counting pedestrians in.  This name will be used in the exported CSV file.
2.  **Count Pedestrians:** Click the "Count" button to increment the pedestrian count.  Each click records the current timestamp and the updated count.
3.  **View Log:**  The log area displays a history of each count, with timestamps.
4.  **Export Data:** Click the "Export CSV" button to download the data as a CSV file.  The filename will include the area name and the current date.
5.  **Reset Counter:** Click the "Reset" button to clear the counter and the log data. **Important:** You will be prompted to export the data *before* the reset occurs, preventing data loss.

## Technologies Used

*   HTML
*   CSS (with mobile-first responsive design)
*   JavaScript (for data handling, local storage, and CSV export)

## Installation

This is a client-side web application, so no installation is required. Simply open the `index.html` file in your web browser.

## Contributing

Contributions are welcome! Please feel free to submit pull requests with improvements or bug fixes.

## License

This project is open source.  (Replace with the specific license you choose, e.g., MIT License)

## Author

Mohamed Shamroukh

m.shamroukh@lboro.ac.uk

## Example CSV Output

The exported CSV file will contain the following columns:

The filename will be in the format `[Area Name]_pedestrian_data.csv`.  For example, if the area name is "High Street", the filename will be `High Street_pedestrian_data.csv`.

## Future Enhancements

*   Option to edit existing log entries.
*   Visualizations of the count data.
*   Integration with a backend database for more robust data storage.
*   Geolocation support to automatically detect the area.
