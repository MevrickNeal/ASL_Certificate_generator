*Alpha Science Lab Certificate Generator*

Overview

The Alpha Science Lab Certificate Generator is a lightweight, web-based tool designed to create professional, print-ready certificates for club members. Built with a focus on minimalism and engineering aesthetics, this tool allows for real-time customization of award details, signatures, and branding without the need for complex design software.

Features

🎨 Customization

Real-time Preview: See changes instantly as you type names and dates.

5 Award Templates: Pre-written descriptions tailored for specific roles:

The Innovator: For creativity and technical aptitude.

The Distinction: For leadership and competitive performance.

The Project Lead: For successful execution of engineering projects.

The Organizer: For event planning and management.

General Member: For active participation and community involvement.

🖼️ Branding & Assets

Multi-Logo Support: Inputs for:

Center Logo (acts as watermark and main icon).

Top-Left Corner Logo.

Top-Right Corner Logo.

Digital Signatures: Upload PNG images for both the President and Faculty Advisor signatures.

🖨️ Print Optimization

CSS Print Media Query: specific styles ensure the control panel is hidden and the certificate fills the page perfectly.

Layout: Optimized for Landscape A4.

How to Use

Launch: Open certificate_generator.html in a modern web browser (Google Chrome is recommended for best print rendering).

Input Data:

Enter the Student Name and Date Awarded in the control panel.

Select the Award Category from the dropdown.

Upload Images:

Upload your Club Logo (PNG/JPEG) for the watermark.

(Optional) Upload logos for the top corners.

Upload signature files for the signatories.

Generate:

Click the Print Certificate button.

Print Settings (Crucial):

Layout: Landscape

Margins: None (or Minimum)

Background Graphics: Checked (if applicable in your browser settings).

Save as PDF or send to a printer.

Technologies Used

HTML5: Structural semantic markup.

Tailwind CSS: Utility-first CSS framework (via CDN) for styling.

JavaScript: Vanilla JS for handling form inputs and image rendering (FileReader API).

Google Fonts:

Montserrat: Headers and UI elements.

Libre Baskerville: Main body text for readability.

Great Vibes: Script font for "Signature" placeholders.

Project Structure

/
├── certificate_generator.html  # Main application file
└── README.md                   # Documentation


Notes

Internet Connection: An internet connection is required to load Tailwind CSS and Google Fonts as they are linked via CDN.

Privacy: All data processing happens locally in your browser. No images or names are uploaded to any external server.
