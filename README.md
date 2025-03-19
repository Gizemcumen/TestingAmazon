# TestingAmazon
# Amazon.com.tr Automation Test (POM - Python + Selenium)

##  Project Overview
This project automates a test scenario for Amazon Turkey (https://www.amazon.com.tr/) using **Python** and **Selenium** with the **Page Object Model (POM)** design pattern.

The test covers the following user flow:
1. Searching for a product (Samsung)
2. Navigating to search results pages
3. Adding a product to the cart
4. Verifying cart functionality
5. Removing the product from the cart
6. Returning to the home page


---


## 🚀 Running the Test

From the root directory, execute the test with:

```bash
python -m unittest tests/test_amazon_flow.py
```

---

## 🧹 Features Implemented
✅ Home page verification  
✅ Search functionality  
✅ Pagination navigation (to page 2)  
✅ Product selection (3rd product)  
✅ Product detail page validation  
✅ Add to cart & success verification  
✅ Cart page validation  
✅ Remove item from cart  
✅ Return to home page verification  

---

##  Notes
- This automation does **NOT** use BDD frameworks (such as Cucumber or Behave).
- The automation strictly follows the **POM (Page Object Model)** best practices.
- The tests are designed for **Amazon Turkey site (https://www.amazon.com.tr/)**.



##  Author
- **Gizem Çümen**  


