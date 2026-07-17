PDF Structural Parser
A high-performance parser designed for dense PDF documents, using PyMuPDF (fitz) for coordinate-clustering data extraction.
Key Features
8-Column Logic: Processes complex table layouts using X-coordinate gap detection.  

Merged Cell Inheritance: Automates data integrity by filling empty cells based on parent headers.  

Drift Tolerance: Implements a 10px safe-zone gutter to handle coordinate variations without data loss.  

Efficiency: Optimized for financial documents, processing pages in under 0.5s.  

Technical Approach
Unlike traditional OCR, which struggles with irregular banking document layouts, this method uses a coordinate-clustering algorithm to ensure reliable financial data extraction.
