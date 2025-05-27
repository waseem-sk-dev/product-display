# Angular Product Showcase App

A modern Angular application that consumes data from [FakeStoreAPI](https://fakestoreapi.com/) to display products in a responsive, user-friendly interface. This project demonstrates real-world Angular development practices, ideal for e-commerce front-end architecture demos, learning API consumption, and UI presentation.


## Tech Stack

* **Angular 16+**
* **TypeScript**
* **RxJS**
* **HTML5 + CSS3 (Flex/Grid Layout)**
* **FakeStoreAPI (public REST API)**
  

## Features

* **Fetches products dynamically** via Angular service
* **Displays product cards** with title, price, image, and rating
* **Responsive design** optimized for desktop and mobile
* **Error handling** for API and network issues
* **Clean component structure** with modular SCSS and service layers

---

## Screenshots

 Product Grid View                               
![image](https://github.com/user-attachments/assets/904eacc0-d580-422f-961a-2024b56be5f0)
----------------------------------------------
Responsive Mobile View                         
![image](https://github.com/user-attachments/assets/26a11c82-5cc6-457c-a13c-ac1034c1e169)
---

## Setup & Installation

1. **Clone the repo:**

   ```bash
   git clone https://github.com/waseem-sk-dev/product-display.git
   cd product-display
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Run locally:**

   ```bash
   ng serve
   ```

4. **Visit:**

   ```
   http://localhost:4200
   ```

---

##  Project Structure

```bash
src/
├── app/
│   ├── components/
│   │   └── product-list/
│   ├── services/
│   │   └── product.service.ts
│   ├── app.module.ts
│   └── app.component.ts
├── assets/
└── styles/
```

---

## 📱 API Source

* [FakeStoreAPI](https://fakestoreapi.com/) — REST API for e-commerce testing

---

## Future Improvements

*  Add to Cart feature
*  Product filtering by category
*  Pagination or infinite scroll
*  Unit tests (Karma + Jasmine)

---

##  Contribution

Pull requests are welcome. For major changes, please open an issue first to discuss what you’d like to change.

---

##  License

This project is open-source under the [MIT License](LICENSE).

---

## Contact
Created by<a href="https://github.com/waseem-sk-dev"> Waseem SK </a> – feel free to reach out!<br>
Let me know if you’d like to include [API error handling](f), [pagination](f), or [UI styling tips](f) to enhance your project.
