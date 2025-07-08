# Product Table
## Date:08-07-2025
## Sachin B
## 212222060207

## Objective:

To create a structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes.

## Tasks:

### 1. Set Up the Basic HTML Structure:

Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document layout.

Include a ```<title>``` such as "Product Table".

### 2. Create a Table Element:

Use the ```<table>``` tag to begin the product table.

### 3. Add a Table Header:

Use the ```<thead>``` section with a ```<tr>``` row and three ```<th>``` elements:

Product Name

Product Price

Description

### 4. Insert Table Body Rows:

Use the ```<tbody>``` section with multiple ```<tr>``` rows.

In each row, use three ```<td>``` cells for:

The name of the product (e.g., Laptop, Phone)

The price (e.g., ₹45,000, $499)

A short description (e.g., "High-speed performance", "Budget-friendly")

### 5. Ensure Semantic Structure:

Include ```<caption>``` if needed to describe the table purpose.

Use meaningful text inside the table for clarity.

### 6. No CSS or JavaScript:

Keep the table design strictly in HTML for simplicity.
## HTML Code:
```
<!DOCTYPE html>
<html>
<head>
    <title>Product Table</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <table>
        <caption>Available Products</caption>
        <thead>
            <tr>
                <th>Product Name</th>
                <th>Product Price</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Laptop</td>
                <td>₹45,000</td>
                <td>High-speed performance for work and play</td>
            </tr>
            <tr>
                <td>Smartphone</td>
                <td>$499</td>
                <td>Budget-friendly with a crisp display</td>
            </tr>
            <tr>
                <td>Wireless Headphones</td>
                <td>₹3,200</td>
                <td>Comfortable fit and long battery life</td>
            </tr>
            <tr>
                <td>Smartwatch</td>
                <td>$99</td>
                <td>Track your fitness and stay connected</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
```

## Output:

![Screenshot 2025-07-08 131525](https://github.com/user-attachments/assets/cf749889-cdfa-4843-b882-c2372b1733b5)

## Css Code:
```
body {
    background-color: #f9f9f9;
    font-family: 'Segoe UI', Arial, sans-serif;
    margin: 0;
    padding: 0;
}

table {
    border-collapse: collapse;
    width: 80%;
    margin: 40px auto;
    background: #fff;
    box-shadow: 0 2px 8px rgba(0,0,0,0.06);
}

caption {
    caption-side: top;
    font-size: 1.5em;
    font-weight: bold;
    margin-bottom: 16px;
    color: #333;
    letter-spacing: 1px;
}

thead th {
    background-color: #4CAF50;
    color: white;
    padding: 14px 10px;
    text-align: left;
    font-size: 1.1em;
}

td {
    border: 1px solid #ddd;
    padding: 12px 10px;
    font-size: 1em;
    color: #333;
}

th {
    border: 1px solid #ddd;
}

tbody tr:nth-child(even) {
    background-color: #f2f2f2;
}

tbody tr:hover {
    background-color: #e0f7fa;
    transition: background 0.2s;
}
```


## Result:
A structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes is created successfully.
