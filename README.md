# GitHub Data Summary Generator

Welcome to the **GitHub Data Summary Generator**! 🎉 This nifty tool allows you to fetch and summarize your public repo information in a PDF file.

<div align="center">
    <img src="https://github.com/user-attachments/assets/f0693797-0b20-48e5-a9da-73ee290c08b1" style="height:250px">
</div>

## Features

- Fetches your public GitHub repositories.
- Summarizes key details: stars, forks, issues, size, and description.
- Generates a PDF report that's easy to share or print.

## External Libraries Used

- **gofpdf**: This fantastic library helps us create PDFs in Go. It allows for flexible formatting and customization, making our reports look professional and clean. Check it out [here](https://github.com/jung-kurt/gofpdf). In fact, the image of the report generated by this app in this README is from jung-kurt's repo (●'◡'●).

## Getting Started

1. Clone this repository to your local machine.
2. Install the required Go packages.
3. Run the application:
    ```bash
    go run github-summary.go
    ```
   and enter your GitHub username (e.g., `Lidiya-MK`) when prompted.
4. Voilà! Your PDF report will be generated and ready for viewing.

## Why Use This Tool?

It's perfect for reflecting on your projects or just having a neat overview of your GitHub activity. Plus, you get to view this information from your terminal—just one command and your GitHub username will do!

## Contribution

Feel free to contribute to this project! Whether it's fixing a bug, improving the code, or adding new features, your input is always welcome.
