- 👋 Hi, I’m @mustafa0087
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
mustafa0087/mustafa0087 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
const elementsToClick = document.querySelectorAll('.d-flex.height-100.width-100.click-area');

const clickElement = (element) => {
  const event = new MouseEvent('click', {
    view: window,
    bubbles: true,
    cancelable: true
  });
  element.dispatchEvent(event);
};

elementsToClick.forEach(clickElement);
