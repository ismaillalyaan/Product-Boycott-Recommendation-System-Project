# Product Boycott Recommendation System Project

## Project Idea
- User scans a product barcode.
- Identify the product based on the barcode.
- Determine if the product is boycotted or not.
- If boycotted, suggest alternative products using a Deep Learning model.

## Technologies Used
- Python
- PyTorch (to build the recommendation model)
- pyzbar + OpenCV (for barcode reading and analysis)
- Streamlit (for building the user interface)
- Deploy on Azure
- CSV (for storing the product database)

## How the Project Works
1. Read and process the barcode image.
2. Search for the product in the database.
3. Check the product status (boycotted or not).
4. If boycotted, suggest alternatives using the recommendation model.
5. Display the results through the Streamlit app.
