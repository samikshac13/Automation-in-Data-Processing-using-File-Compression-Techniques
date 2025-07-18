# 🤖 Automation in Data Processing Using File Compression Techniques
This project presents an intelligent file compression system powered by AI that dynamically selects the most efficient compression algorithm based on file characteristics such as type, size, and entropy. Designed for handling large-scale data (10–50 GB), the system automates compression and decompression with real-time feedback, progress tracking, and reinforcement learning for improved future decisions.

## ✅ Features
1. File & folder compression/decompression with real-time GUI
2. AI-powered algorithm selection using supervised & reinforcement learning
3. Integration of multiple compression methods (Zstandard, LZ4, Bzip2)
4. Tkinter-based GUI with user-friendly interface for non-technical users
5. Multi-threaded execution and chunked processing for large datasets
6. Real-time performance tracking (compression ratio, CPU/RAM usage)
7. Secure data handling with file integrity validation
## 🧩 System Architecture
The system comprises the following modules:
- File Analysis Module: Reads file attributes for entropy, format, and size
- AI Decision Engine: Suggests best-fit algorithm using supervised + reinforcement learning
- Compression Engine: Executes selected method with logging
- Performance Tracker: Monitors CPU/RAM usage, compression speed, and success ratio
- GUI Layer: Multi-frame interface using Tkinter with compression stats visualization

Architecture and process flow diagrams are included as System_Architecture.png and Process_Flow.png in the repository.

## 🔁 Application Flow
Step-by-Step Flow:
- Launch GUI and select file/folder
- System analyzes the file's type, size, and entropy
- AI recommends the optimal compression algorithm
- User confirms and starts compression
- Progress bar and stats displayed in real-time
- Option to decompress and verify original file integrity
- AI learns from result and logs performance

Application screenshots and flow diagrams are included in the repository.

## 📊 Performance Results
- Achieved 30% better compression ratio than standard ZIP/GZIP
- Reduced processing time by 15–20% for large datasets (20–50GB)
- Adaptive AI logic provides file-type-specific algorithm selection
- Maintained CPU usage under 60% and RAM under 70% during heavy tasks

## 📂 Published Research
- Journal: IRJMETS – International Research Journal of Modernization in Engineering Technology and Science
- Volume: 07, Issue 06, June 2025
- DOI: https://www.doi.org/10.56726/IRJMETS80336
- PDF: Included in the repository as Published_Research_Paper.pdf

## 👩‍💻 Author
Miss. Samiksha Ashok Chavan

Student, Dept. of Information Technology

University of Mumbai, Sindhudurg Sub Campus

📧 samikshachavan1310@gmail.com

🔗 LinkedIn (https://www.linkedin.com/in/samiksha-chavan-74031b375)

## ⚠️ Disclaimer
This repository includes a demonstration of the core functionalities of the AI-powered file compression system developed as part of an academic research project. Due to institutional privacy and academic submission guidelines, the full implementation code and certain modules (e.g., the complete AI model and cloud automation scripts) are not publicly available.

However, the project is under active development, particularly with respect to Google Drive integration for cloud-based compression of aged files.
If you are interested in collaborating, contributing, or exploring the full implementation, especially in extending the cloud features, feel free to reach out. I would be happy to work further on these enhancements as part of a collaborative effort or internship/industry engagement.
