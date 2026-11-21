# Assignment 4 – Designing Reusable Class Hierarchies

**Name:** S. Adithiyan  
**Register Number:** 1925260197  
**Course:** Object Oriented Programming with C++ (DSA01)  
**GitHub repository (provided):** https://github.com/Adithiyan-1005/DSA0112-1925260197-4.git

**Required repository name (per assignment):** `DSA01-1925260197-Assignment4`

## Compiler and build

Compiler: GNU g++ (use the version installed on your system; check with `g++ --version`).

Compile each program from the repository root:

```bash
g++ -std=c++17 -Wall -Wextra Task01/main.cpp -o Task01/task01
g++ -std=c++17 -Wall -Wextra Task02/main.cpp -o Task02/task02
g++ -std=c++17 -Wall -Wextra Task03/main.cpp -o Task03/task03
g++ -std=c++17 -Wall -Wextra Task04/main.cpp -o Task04/task04
g++ -std=c++17 -Wall -Wextra Task05/main.cpp -o Task05/task05
g++ -std=c++17 -Wall -Wextra Task06/main.cpp -o Task06/task06
```

Run each executable (Windows PowerShell: use `.[0mTask01\task01.exe` if compiled with `.exe`; Linux/macOS: `./Task01/task01`). The `output.txt` files in each task folder contain a sample run from the build environment; run locally and capture your own screenshots before submission.

## Task summary

| Folder | Main result |
|---|---|
| Task01 | Staff base class and derived payroll types; polymorphic `pay()` |
| Task02 | Person/Student/Staff hierarchy, virtual diamond and TeachingAssistant |
| Task03 | Base/member initialization, construction/destruction order and member classes |
| Task04 | Virtual rate, virtual destructor and RAII-managed account pointers |
| Task05 | Direct object, pointer, reference, dynamic allocation, `this`, chaining and pointer-array search |
| Task06 | Abstract Vehicle hierarchy, polymorphic fleet, rental/return and ElectricBus extension |

## Assignment report

See `Assignment4_Report.docx` for the written answers, UML-style diagrams, access table, output predictions, design comparisons, pseudocode and complexity analysis.

## GitHub workflow (commit progressively)

```bash
git init
git add README.md Assignment4_Report.docx Task01
git commit -m "Complete Task 1 payroll hierarchy"
git add Task02 && git commit -m "Complete Task 2 people hierarchy"
git add Task03 && git commit -m "Complete Task 3 constructors and members"
git add Task04 && git commit -m "Complete Task 4 polymorphic accounts"
git add Task05 && git commit -m "Complete Task 5 object pointers and this"
git add Task06 && git commit -m "Complete Task 6 vehicle fleet design"
```

Then connect the local repository to your GitHub repository (`https://github.com/Adithiyan-1005/DSA0112-1925260197-4.git`) and push. Add faculty as collaborator if the repository is private. Upload the report and working GitHub link to the required submission location. Do not submit until you have compiled, run, reviewed and understood every program.
