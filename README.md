### **Release Title:**
`Shopify Payment Icons Integration v1.0.0`

### **Tag Version:**
`v1.0.0`, `Shopify`

---

## **📢 Introduction**

We are pleased to announce the **first official release** of the **Shopify Payment Icons Integration**. This feature allows you to easily display supported payment methods on your Shopify product pages, enhancing trust and improving the shopping experience for your customers.

---

## **✨ Key Features**

- **Display Supported Payment Methods:** Show which payment methods are accepted on your product pages.
- **Simple Integration:** Easily add to existing Shopify themes.
- **Responsive Design:** Works seamlessly on both desktop and mobile devices.

---

## **🖼️ Visual Preview**

So sehen die Payment Icons auf Ihrer Produktseite aus:

![Payment Icons Preview](https://i.ibb.co/rsRkTFT/payment-icons-preview.png)

---

## **🔧 Installation Instructions**

### **Step 1: Create a New Snippet**
1. Navigate to **"Online Store" > "Themes"** in your Shopify Admin.
2. Click **"Actions" > "Edit code"**.
3. In the **"Snippets"** directory, click **"Add a new snippet"**.
4. Name the snippet `payment-icons.liquid`.
5. Copy the content from the `payment-icons.liquid` file in this repository and paste it into the new snippet.
6. **Save** the snippet.

### **Step 2: Update the `main-product.liquid` File**
1. Open the file `sections/main-product.liquid`.
2. Locate the `buy_buttons` block.
3. Add the following code directly after the `buy_buttons` block:

   ```liquid
   <div class="product-form__payment-icons">
     {% render 'payment-icons' %}
   </div>
### **Step 3: Save and Test**
1. **Save** all changes.
2. Review your product page in the theme editor or on the live store to ensure everything displays correctly.

---

## **🛠️ Customizations**

- You can modify the appearance of the icons by adjusting the CSS within the `payment-icons.liquid` snippet.
- To add additional static icons, insert them within the `<ul>` element in the snippet.

---

## **💬 Support**

If you need assistance with integration or customization, please open an issue in this repository.

---

## **🤝 Contribution**

Contributions to improve this snippet are welcome. Please fork the repository and submit a pull request with your changes.

---

## **📄 License**

This project is licensed under the **MIT License**. For more details, please refer to the [LICENSE](https://github.com/Onur-Cloud/LICENSE/blob/main/LICENSE) file.
