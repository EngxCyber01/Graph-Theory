# 📊 Graph Theory Academy - Interactive Learning Platform

Welcome to the Graph Theory Interactive Learning Platform! This comprehensive educational platform covers fundamental concepts of graph theory and data structures through the lens of graph algorithms.

## 🎯 Features

### ✨ Comprehensive Content
- **4 Complete Lectures** covering core graph theory topics
- **Dual Format Learning**: Full detailed lectures + Quick summaries for each topic
- **Multiple Practice Questions** per lecture (12+ questions each)
- **Interactive Code Examples** with simulated terminal output
- **Real-world Applications** demonstrating practical use cases

### 📚 Course Structure

1. **Lecture 1: Concept of Graph Theory**
   - Introduction to graphs
   - Types of graphs (undirected, directed, weighted, complete, DAG)
   - Essential terminology (degree, path, cycle, connected graphs)
   - Python implementations
   - 12 practice questions

2. **Lecture 2: Graph Representation**
   - Adjacency Matrix representation
   - Adjacency List representation
   - Edge List representation
   - Comparison and use cases
   - Python implementations for all three methods
   - 12 practice questions

3. **Lecture 3: Planar Graphs**
   - Planar graph definition and properties
   - Euler's Formula (V - E + F = 2)
   - Kuratowski's Theorem
   - Graph coloring and Four Color Theorem
   - Python implementations
   - 12 practice questions

4. **Lecture 4: Spanning Trees**
   - Spanning tree concepts
   - Minimum Spanning Tree (MST)
   - Kruskal's Algorithm with Union-Find
   - Prim's Algorithm with Min-Heap
   - Complete Python implementations
   - 12 practice questions

### 💻 Built-in Code Terminals

Each lecture includes:
- **Interactive code examples** showing how to implement graph algorithms
- **Step-by-step execution** with clear output
- **Complete working implementations** ready to test
- **Multiple examples** demonstrating different scenarios

### 🎨 Responsive Design

- **Mobile-friendly**: Works on smartphones and tablets
- **Laptop-optimized**: Best experience on laptops and desktops
- **Clean, modern UI**: Easy-to-read layout with clear navigation
- **Color-coded sections**: Visual hierarchy for better learning

## 🚀 Getting Started

### Option 1: Open Directly in Browser

1. Navigate to the project folder: `c:\Users\hillios\OneDrive\Desktop\GG\`
2. Double-click on `index.html` to open in your default browser
3. Start exploring the lectures!

### Option 2: Use Live Server (Recommended for Development)

1. Open VS Code
2. Install the "Live Server" extension if you haven't
3. Right-click on `index.html`
4. Select "Open with Live Server"
5. The platform will open in your browser with hot-reload enabled

### Option 3: Simple HTTP Server

Using Python:
```bash
cd "c:\Users\hillios\OneDrive\Desktop\GG"
python -m http.server 8000
```

Then open: `http://localhost:8000` in your browser

## 📁 Project Structure

```
GG/
├── index.html              # Main landing page
├── styles.css              # All styling for the platform
├── script.js               # Interactive functionality
├── pdfs/                   # Original lecture PDFs (reference)
│   ├── Concept of graph theory.pdf
│   ├── Graph Representation.pdf
│   ├── Plannar Graph.pdf
│   └── Spanning Trees.pdf
└── lectures/               # Individual lecture pages
    ├── concept-full.html          # Full lecture 1
    ├── concept-summary.html       # Summary lecture 1
    ├── representation-full.html   # Full lecture 2
    ├── representation-summary.html# Summary lecture 2
    ├── planar-full.html          # Full lecture 3
    ├── planar-summary.html       # Summary lecture 3
    ├── spanning-full.html        # Full lecture 4
    └── spanning-summary.html     # Summary lecture 4
```

## 🎓 How to Use This Platform

### Learning Paths

**For Complete Understanding:**
1. Start with Lecture 1 Full Version
2. Work through all code examples
3. Attempt practice questions
4. Review the summary for quick reference
5. Move to next lecture

**For Quick Review:**
1. Read the summary version of each lecture
2. Review key formulas and concepts
3. Try quick practice problems
4. Refer to full lecture for detailed explanations

**For Exam Preparation:**
1. Review all summaries first
2. Focus on key formulas and algorithms
3. Practice coding implementations
4. Work through all practice questions
5. Review full lectures for unclear topics

### Practice Questions

Each lecture includes 12+ practice questions covering:
- **Conceptual questions**: Test your understanding
- **Calculation problems**: Apply formulas and theorems
- **Coding challenges**: Implement algorithms
- **Real-world scenarios**: Apply concepts to practical problems

### Code Examples

All code examples are:
- ✅ **Complete and runnable** - Copy and test locally
- ✅ **Well-commented** - Understand each step
- ✅ **Multiple examples** - See different use cases
- ✅ **Output included** - See expected results

## 🛠️ Customization

### Modifying Styles

Edit `styles.css` to customize:
- Colors and themes
- Layout and spacing
- Font sizes and families
- Button styles
- Responsive breakpoints

### Adding More Content

To add new lectures:
1. Create new HTML files in `/lectures/` folder
2. Follow the existing template structure
3. Update `index.html` to add navigation buttons
4. Add appropriate styling in `styles.css`

### Testing Code Locally

To test the Python code examples:
1. Copy code from any lecture page
2. Save as `.py` file
3. Run in your terminal: `python filename.py`
4. Compare output with shown results

## 📱 Device Compatibility

✅ **Desktop/Laptop** (Recommended)
- Full-screen experience
- Easy code reading
- Best for typing practice solutions

✅ **Tablet**
- Good reading experience
- Portable learning
- Touch-friendly navigation

✅ **Mobile**
- On-the-go review
- Quick summary access
- May require zooming for code

## 🔧 Technical Requirements

- **Browser**: Any modern browser (Chrome, Firefox, Safari, Edge)
- **JavaScript**: Must be enabled
- **Screen Resolution**: 360px+ (mobile), 768px+ (tablet), 1024px+ (optimal)
- **Internet**: Not required (fully offline after download)

## 📖 Topics Covered

### Graph Fundamentals
- Graph definitions and notation
- Vertex and edge concepts
- Degree calculations
- Paths, walks, and cycles

### Graph Types
- Undirected graphs
- Directed graphs (digraphs)
- Weighted graphs
- Complete graphs
- Trees and forests
- DAGs

### Representations
- Adjacency Matrix (O(V²) space)
- Adjacency List (O(V+E) space)
- Edge List (O(E) space)
- Time complexity comparisons

### Planar Graphs
- Planarity testing
- Euler's formula
- Kuratowski's theorem
- Graph coloring
- Four Color Theorem

### Spanning Trees
- Spanning tree properties
- Minimum Spanning Tree (MST)
- Kruskal's Algorithm
- Prim's Algorithm
- Union-Find data structure

### Algorithms Implemented
- Graph traversal basics
- Planarity testing
- Greedy coloring
- Kruskal's MST algorithm
- Prim's MST algorithm
- Union-Find operations

## 💡 Study Tips

1. **Read Full Lectures First**: Get comprehensive understanding
2. **Practice Coding**: Type out examples yourself
3. **Solve All Questions**: Test your knowledge thoroughly
4. **Use Summaries for Review**: Quick refreshers before exams
5. **Draw Graphs**: Visualize concepts on paper
6. **Compare Algorithms**: Understand trade-offs
7. **Build Projects**: Apply concepts to real problems

## 🎯 Learning Objectives

After completing this course, you will be able to:
- ✅ Understand fundamental graph theory concepts
- ✅ Implement graphs in Python using multiple representations
- ✅ Choose appropriate representation based on use case
- ✅ Analyze graph properties (connectivity, planarity, etc.)
- ✅ Apply graph algorithms to solve real-world problems
- ✅ Implement MST algorithms (Kruskal's and Prim's)
- ✅ Understand time and space complexity of graph operations

## 📞 Getting Help

If you encounter any issues:
1. Check browser console for JavaScript errors
2. Ensure all files are in correct folders
3. Verify file paths match your system
4. Try different browser if problems persist

## 🚀 Next Steps

1. **Complete all 4 lectures** in order
2. **Solve practice questions** for each lecture
3. **Implement algorithms** from scratch
4. **Apply to projects**: Try building:
   - Social network analyzer
   - Route finding system
   - Network optimization tool
   - Task scheduling app

## 📝 License

This educational platform is created for learning purposes. Feel free to modify and extend it for your educational needs.

---

**Happy Learning! 🎓**

Start your journey by opening `index.html` and clicking on Lecture 1!
