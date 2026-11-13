# Algorithm Battle – Which Data Structure Wins?

## Student details
- **Name:** Shrinidhi C S
- **Register Number:** RA251004205005

## Project overview
A C-based Student Record Management System comparing Binary Search Tree (BST), AVL Tree and Hash Table with Linear Probing. Each record contains Student ID, name, department and marks.

## Dataset
The program uses 30 records in a new mixed insertion order. IDs range from 5203 to 5297.

| Student ID | Name | Department | Marks |
|---:|---|---|---:|
| 5207 | Aadhira | CSE | 91 |
| 5242 | Bala | ECE | 84 |
| 5286 | Charvi | IT | 96 |
| 5221 | Dharshini | EEE | 88 |
| 5269 | Ezhil | AIML | 93 |
| 5293 | Fathima | CSE | 79 |
| 5214 | Gokul | ECE | 95 |
| 5277 | Harini | IT | 82 |
| 5235 | Inba | EEE | 90 |
| 5258 | Jaswin | AIML | 97 |
| 5203 | Kavin | CSE | 85 |
| 5281 | Lavanya | ECE | 92 |
| 5228 | Mithra | IT | 78 |
| 5262 | Nithya | EEE | 94 |
| 5297 | Praveen | AIML | 87 |
| 5249 | Rithika | CSE | 99 |
| 5219 | Sanjana | ECE | 83 |
| 5271 | Tharun | IT | 89 |
| 5232 | Udhaya | EEE | 96 |
| 5254 | Varsha | AIML | 86 |
| 5289 | Yuvan | CSE | 93 |
| 5209 | Zara | ECE | 81 |
| 5265 | Abinaya | IT | 91 |
| 5225 | Bharath | EEE | 80 |
| 5291 | Deepa | AIML | 88 |
| 5244 | Girish | CSE | 77 |
| 5274 | Kishore | ECE | 98 |
| 5211 | Meena | IT | 86 |
| 5251 | Naveen | EEE | 92 |
| 5284 | Roshni | AIML | 84 |

## Operations
1. Search using BST
2. Search using AVL Tree
3. Search using Hashing
4. Display BST traversals
5. Display AVL traversals
6. Display Hash Table
7. Insert a new student
8. Run performance experiment
9. Display all student records
0. Exit

## Configuration
| Parameter | Value |
|---|---|
| Initial records | 30 |
| Maximum capacity | 100 |
| Hash table size | 47 |
| Hash function | `h(id) = id % 47` |
| Collision handling | Linear probing |
| Successful search key | 5269 |
| Unsuccessful search key | 5399 |

## Measured performance
The following values were obtained by compiling and running `student.c` with this dataset.

| Measurement | BST | AVL Tree | Hash Table |
|---|---:|---:|---:|
| Height (nodes) | 8 | 6 | Not applicable |
| Successful search (5269) | 4 comparisons | 4 comparisons | 1 probes |
| Unsuccessful search (5399) | 5 comparisons | 5 comparisons | 3 probes |
| Insertion collisions | Not applicable | Not applicable | 6 |

## Compile and run
```bash
gcc -std=c99 -Wall -Wextra student.c -o student
./student
```
On Windows with GCC/MinGW:
```bash
gcc -std=c99 -Wall -Wextra student.c -o student.exe
student.exe
```

## Repository structure
```text
Algorithm_Battle_Submission/
├── student.c
├── student
├── README.md
├── report.docx
└── Screenshots/
    ├── avl_successful_search_5269.png
    ├── avl_traversals.png
    ├── avl_unsuccessful_search_5399.png
    ├── bst_successful_search_5269.png
    ├── bst_traversals.png
    ├── bst_unsuccessful_search_5399.png
    ├── hash_successful_search_5269.png
    ├── hash_table.png
    ├── hash_unsuccessful_search_5399.png
    ├── initial_dataset.png
    ├── insert_student_5301.png
    ├── performance_comparison.png
```

## GitHub repository
https://github.com/harinishrinithi1-hash/Algorithm_Battle.git

The updated local files in this ZIP should be pushed to the GitHub repository to update its online contents.