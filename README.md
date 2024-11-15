# Tumour Detection System

This project is an AI tool designed to assist radiologists by automatically highlighting important areas in medical images such as MRIs, CT scans, and X-rays. The application can distinguish between healthy and abnormal tissues, detect early signs of diseases, and mark areas for further examination. This reduces the workload for radiologists and helps minimize errors.

## Features
- **Scan Upload**: Users can upload MRI, CT, or X-ray scans.
- **Automated Tumor Detection**: AI-powered segmentation to identify potential tumors.
- **AI-Generated Medical Report**: Provides a report highlighting findings for medical review.

## Technology Stack
- **Frontend**: HTML, CSS, JavaScript, React
- **Backend**: Node.js, Express.js, Flask
- **Deep Learning**: TensorFlow, OpenCV for image segmentation and tumor detection
- **Authentication**: JWT (JSON Web Tokens)
        
## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/raghu-gurram/Tumour-Detection-System.git
   ```

2. **Install dependencies**:
   - For the backend:
     ```bash
     cd api
     npm install
     ```
   - For the frontend:
     ```bash
     cd client
     npm install
     ```

3. **Start the application**:
   - Run the backend server:
     ```bash
     cd api
     node index.js
     ```
   - Run the frontend:
     ```bash
     cd client
     npm start
     ```

## Usage
1. Open the web application in your browser.
2. Upload a medical scan (MRI, CT, or X-ray) using the provided interface.
3. Receive an AI-generated report indicating the presence of any tumors.

## Contact
For any questions or support, please contact [Raghu Gurram](mailto:raghugurram5690@gmail.com).
```

This README provides an overview of the project, the tech stack, setup instructions, and a project structure outline, making it easier for others to understand and contribute to your repository.