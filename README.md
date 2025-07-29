# DRAWING_SHAPES-IN-CANVAS-_-OpenCV
 Drawing Shapes in Canvas using OpenCV
🎯 Objective
This project demonstrates how to draw basic geometric shapes on a blank canvas using OpenCV in Python. It's useful for understanding image creation, computer graphics, and foundational image manipulation techniques.

🛠️ Technologies Used
🐍 Python

📸 OpenCV (cv2)

📘 Jupyter Notebook (.ipynb)

✨ Features
✅ Create a custom-colored canvas using np.full

✅ Draw:

Lines with cv2.line()

Rectangles with cv2.rectangle()

Circles with cv2.circle()

Polylines / Contours with cv2.polylines()

✅ Display the final image using cv2.imshow() or matplotlib.pyplot

📁 File Structure
css
Copy
Edit
📦 DRAWING_SHAPES-IN-CANVAS-_-OpenCV/
 └── Draw_line_shape.ipynb   # Main notebook with all shape drawing operations
📌 Sample Snippets
📐 Create a Canvas
python
Copy
Edit
canvas = np.full((500, 700, 3), (255, 255, 255), dtype=np.uint8)  # White canvas
📏 Draw a Line
python
Copy
Edit
cv2.line(canvas, (50, 100), (600, 100), (255, 0, 0), 3)  # Blue line
🔲 Draw a Rectangle
python
Copy
Edit
cv2.rectangle(canvas, (100, 150), (400, 300), (0, 255, 0), 2)  # Green border
⚪ Draw a Circle
python
Copy
Edit
cv2.circle(canvas, (350, 350), 50, (0, 0, 255), -1)  # Filled red circle
📸 Output Preview
The notebook walks through how each shape is drawn and displays the final result on a canvas — ideal for beginners in computer vision or graphical programming.

▶️ How to Run
Clone the repo:

bash
Copy
Edit
git clone https://github.com/Aryan-1912/DRAWING_SHAPES-IN-CANVAS-_-OpenCV.git
Launch Jupyter Notebook and open Draw_line_shape.ipynb

Run each cell to see shapes drawn on a canvas

🙋‍♂️ Author
Aryan Prajapati
📫 LinkedIn
🔗 GitHub: Aryan-1912

