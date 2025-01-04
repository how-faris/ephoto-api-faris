
# Photo360 API - ePhoto360 Integration 🌈

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Charm&duration=2000&pause=1000&color=00FFFF&background=000000&center=true&vCenter=true&width=435&lines=Created+With+%F0%9F%A4%8D+By+Faris+Ali+%E2%86%92;It's+Not+Just+a+Name+Bro+%E2%86%90;It's+a+Brand+%E2%86%92+%F0%9F%A5%87)](https://github.com/how-faris/ephoto-api-faris)

**Photo360** is a Node.js package developed by **Faris Ali** for interacting with the ePhoto360 API. It enables developers to easily generate custom image effects, like handwritten text on foggy glass, directly from their applications. 🚀

---

## 📥 Installation

Install the package using npm:

```bash
npm install ephoto-api-faris
```

---

## 🚀 Usage

### Example Code:

```javascript
const Photo360 = require('ephoto-api-faris');

(async (name) => {
    const photo360 = new Photo360("https://en.ephoto360.com/handwritten-text-on-foggy-glass-online-680.html");
    photo360.setName(name);
    const imgUrl = await photo360.execute();
    console.log(`Image URL: ${imgUrl.imageUrl}`);
})("Faris Ali");
```

### Steps:
1. 🛠 **Require the package**: Import the `Photo360` class from the package.
2. 🌐 **Initialize the API**: Provide the ePhoto360 URL of the desired effect.
3. ✍️ **Set the name**: Use the `setName` method to define the custom text or name.
4. 🌟 **Generate the image**: Call the `execute` method to get the image URL.

---

## 📋 Parameters

- **URL**: Provide the effect's URL from the ePhoto360 website.
- **Name**: The text or name to be displayed in the image effect.

---

## 📤 Output

- The package returns an object containing the image URL:

```javascript
{
    imageUrl: "<generated-image-url>"
}
```

---

## 🌟 Features

- Easy integration with the ePhoto360 API.
- Supports dynamic text for creative image effects.
- Simple and intuitive API for developers.

---

## 📈 Package Stats

![npm](https://img.shields.io/npm/v/ephoto-api-faris)
![downloads](https://img.shields.io/npm/dt/ephoto-api-faris)
![license](https://img.shields.io/npm/l/ephoto-api-faris)

---

## 🙌 Support the Project

If you find this package helpful, please consider giving it a ⭐ on [GitHub](https://github.com/how-faris/ephoto-api-faris)!

---

## 👨‍💻 Author

Developed by **Faris Ali**.

For feedback and support, please reach out via the [GitHub repository](https://github.com/how-faris/ephoto-api-faris).

---

## 📝 License

This package is licensed under the MIT License. Feel free to use, modify, and distribute it.

---

## 🤝 Contributions

The core logic of the Photo360 package is encrypted to ensure security and integrity. While direct contributions to the core code are not possible, you are welcome to contribute in the following ways:

- 💡 **Feature Suggestions**: Propose new features or enhancements by creating an issue on the [GitHub repository](https://github.com/how-faris/ephoto-api-faris).
- 🖋️ **Documentation Improvements**: Help improve or extend the documentation for better usability.
- 🐛 **Bug Reporting**: If you encounter issues, please report them with detailed steps to reproduce the problem.
- 🎨 **Ideas for New Effects**: Suggest new image effects or use cases for future development.

---

Thank you for supporting the project! 💖
