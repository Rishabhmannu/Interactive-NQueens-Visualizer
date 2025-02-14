# N-Queens Visualizer 👑

![N-Queen-visualisation](visualisation.gif)

*A web-based interactive visualizer for the classic N-Queens problem using backtracking algorithm*

## 📖 Description
- The N-Queens puzzle is the problem of placing N chess queens on an N×N chessboard so that no two queens threaten each other. Thus, a solution requires that no two queens share the same row, column, or diagonal.
- This project provides an animated visualization of the N-Queens puzzle solution using backtracking algorithm. Users can specify the number of queens (N), control animation speed, and watch the algorithm place queens on a chessboard while ensuring no two queens attack each other.
- This algorithm is designed using recursion.

## ✨ Key Features
- **Interactive Controls**: Adjust animation speed with SLOW/FAST slider
- **Real-time Visualization**: Watch backtracking algorithm work step-by-step
- **Multiple Board Display**: Shows all valid arrangements simultaneously
- **Error Prevention**: Input validation (1 ≤ N ≤ 8)
- **Responsive Design**: Clean UI with modern styling
- **Solution Counter**: Displays total valid arrangements for given N

## 🧠 Core Algorithm
**Backtracking Algorithm** implementation that:
1. Places queens column by column
2. Checks for conflicts in rows and diagonals
3. Backtracks when no valid placement possible
4. Recursively finds all valid solutions

## 🛠️ Technologies Used
- HTML5
- CSS3 (Flexbox, Grid)
- Vanilla JavaScript
- Font Awesome Icons

## ⚙️ Installation & Usage
1. Clone repository:
   ```bash
   git clone https://github.com/your-username/N-Queens-Visualiser.git
   ```
2. Open `index.html` in web browser
3. Enter number of queens (1-8)
4. Adjust speed using slider
5. Click ▶️ Play to start visualization

## 📦 Dependencies
- Internet connection (for Font Awesome icons CDN)
- Modern web browser with ES6 support

## 🎨 UI Components
- Dark purple/violet themed controls
- Capsule-styled input field
- Speed control slider with gradient effects
- Animated chessboards with queen placement
- Solution counter display

## 📚 Theory Behind N-Queens
The N-Queens puzzle requires placing N chess queens on an N×N chessboard so that no two queens threaten each other. This problem demonstrates:
- Constraint satisfaction
- Recursive backtracking
- Combinatorial optimization

## 🌟 Unique Aspects
- Visual representation of backtracking process
- Clear conflict highlighting during placement checks
- Smooth animation transitions
- Multiple board display for all solutions
- Performance optimized for N ≤ 8

## 🤝 Contributing
Contributions welcome! Please follow:
1. Fork the repository
2. Create your feature branch
3. Commit changes
4. Push to branch
5. Open a Pull Request

## 📄 License
MIT License - see [LICENSE](LICENSE) file for details
