# Experiment 1 - HTML Image Map  

## 🎯 Objective  
To create a web page that embeds an image map, defines hotspots, and shows relevant information when clicked.  

## 📌 Instructions  
1. Open `index.html` in a web browser.  
2. Click on the different hotspots in the image to navigate to different pages.  
3. Modify the `coords` attribute to change the clickable areas.  

## 🛠 Technologies Used  
- HTML5  
- CSS3  

---

## 🔍 Understanding the `coords` Attribute  
The `coords` attribute specifies the coordinates of the clickable areas in the image. It differs for different shapes:  

### 🟥 **Rectangle (`rect`)**  
- Format: `coords="x1,y1,x2,y2"`  
- **Example:** `coords="34,44,270,350"`  
- **Explanation:**  
  - `(x1, y1) →` Top-left corner of the rectangle  
  - `(x2, y2) →` Bottom-right corner of the rectangle  

---

### ⚪ **Circle (`circle`)**  
- Format: `coords="x,y,r"`  
- **Example:** `coords="400,200,50"`  
- **Explanation:**  
  - `(x, y) →` Center of the circle  
  - `r →` Radius of the circle  

---

### 🔺 **Polygon (`poly`)**  
- Format: `coords="x1,y1,x2,y2,x3,y3,..."`  
- **Example:** `coords="320,350,450,450,320,550"`  
- **Explanation:**  
  - A list of `(x, y)` coordinates defining each vertex of the polygon  

---

## 📷 Image Map Reference  
![Sample Image](map-image.jpg)  

Now, test different coordinate values to understand how image mapping works! 🚀  
