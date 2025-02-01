

# **Linked_List_DSA**  
### **IPL Player Performance Analysis Using Sparse Matrices & Linked Lists**  

## 📌 **Project Overview**  
This project implements **sparse matrices using linked lists** to efficiently store and analyze **IPL player performance data**. Instead of storing a **120 × 74** matrix in a 2D array, we use **linked lists** to store only non-zero values, reducing memory usage.  

The dataset contains:  
- **Batting Matrix** → Stores half-century records (1 for Yes, 0 for No).  
- **Bowling Matrix** → Stores wicket records (1 for Yes, 0 for No).  

The program processes these matrices to **identify all-rounders**, compute the **transpose**, and perform **efficient queries** on the data.  

---

## 🚀 **Features**  
✅ **Sparse Matrix Representation:** Store only **non-zero values** in **linked lists** to optimize memory.  
✅ **Transpose Computation:** Efficiently compute and display the **transpose of matrices**.  
✅ **All-Rounder Detection:** Identify players who have **scored at least one half-century** and **taken two or more wickets**.  
✅ **File Handling:** Read input player statistics from external files (`half_centuries.txt`, `two_plus_wickets.txt`).  
✅ **Time Complexity Analysis:** Measure **execution time** for parsing, processing, and displaying data.  

---

## 🛠 **Technologies Used**  
🔹 **C Programming** (for linked list implementation)  
🔹 **File Handling** (to read and write matrix data)  
🔹 **Data Structures** (Linked Lists, Sparse Matrices)  
🔹 **Performance Analysis** (using `clock()` for execution time measurement)  

---

## 📂 **Project Structure**  
```
/Linked_List_DSA
│── /src
│   ├── main_prg.c                 # Main program (menu-driven)
│   ├── all_rounder.c               # Identifies all-rounders
│   ├── half_century.c              # Parses half-century data
│   ├── 2+_wickets.c                # Parses wickets data
│   ├── transpose_matrix.c          # Computes the transpose of the sparse matrix
│── /include
│   ├── half_century.h              # Header for half-century functions
│   ├── 2+_wickets.h                # Header for wickets functions
│── /data
│   ├── half_centuries.txt          # Input file for half-century data
│   ├── two_plus_wickets.txt        # Input file for wickets data
│── README.md
```

---

## 📜 **How to Run the Project?**  
1️⃣ **Clone the repository:**  
```bash
git clone https://github.com/yourusername/Linked_List_DSA.git
cd Linked_List_DSA
```
2️⃣ **Compile the program:**  
```bash
gcc main_prg.c -o main.exe && ./main.exe
```
3️⃣ **Follow the prompts** to select:  
   - **Half Centuries**  
   - **Wickets Taken**  
   - **All-Rounder Players**  
   - **Transpose Matrix**  

---

## 📊 **Applications of Sparse Matrices**  
✔ **Memory Optimization** for large datasets.  
✔ **Graph Representation** using adjacency matrices.  
✔ **Machine Learning** datasets (e.g., recommendation systems).  
✔ **Text Processing** (storing term frequency in NLP).  

---

## 🖥️ Sample Output

Here is an example of the program execution:

![Sample Output](screenshots/Sample_output.jpg)


## 👨‍💻 **Contributors**  
🔹 **Abhilash G**  
🔹 **Md Faizan Ansari**  
🔹 **Muskan Kumari**  
🔹 **Harshvardhan Manavalan**  

📌 **Feel free to contribute!** Fork, modify, and submit a PR.  
🔥 **Star this repo if you found it useful!** 🌟  

