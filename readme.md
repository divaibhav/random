# Fruit Gallery Website 

### Problem Statement 

You are given:
- A folder named `images/` containing 10 fruit images:
  ```
  apple.jpg, banana.jpg, mango.jpg, strawberry.jpg, orange.jpg,
  pineapple.jpg, watermelon.jpg, grape.jpg, kiwi.jpg, avocado.jpg
  ```
- A file named `content.txt` that contains exactly 10 lines. Each line has the format:  
  `Fruit Name::Description text here`

Example content.txt:
```
Apple::Crisp, juicy fruit with a sweet-to-tart flavor depending on the variety...
Banana::Soft, creamy flesh with a sweet, slightly starchy taste...
Mango::Known as the “king of fruits.” Juicy, sweet, and slightly tangy...
...
```

### Your Task

Create an `index.html` file (and optional `style.css`) that displays a beautiful fruit gallery with the following requirements:

1. Use semantic HTML5
2. Display all 10 fruits in a responsive grid (2–4 columns depending on screen size)
3. For each fruit you must display:
   - A heading (`<h2>` or `<h3>`) with the fruit name
   - The exact description from `content.txt`
   - The corresponding image from the `images/` folder
4. Every fruit div must have the class name 
5. Add appropriate alt text to each image
6. Make sure the page looks good on both desktop and mobile

### Project Structure (what your repo should look like)
```
fruit-gallery/
│
├── index.html
├── style.css              (optional, but recommended)
├── content.txt            (already provided)
└── images/
    ├── apple.jpg
    ├── banana.jpg
    ├── mango.jpg
    ├── strawberry.jpg
    ├── orange.jpg
    ├── pineapple.jpg
    ├── watermelon.jpg
    ├── grape.jpg
    ├── kiwi.jpg
    └── avocado.jpg
```



### Tips
- You can read `content.txt` manually (since this is a static site) or just copy-paste the data into your HTML
- Use relative paths: `src="images/apple.jpg"`

```

