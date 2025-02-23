### Oi, eu sou Vitor! ☕

<div>
  <button onclick="toggleLanguage()" style="background-color: #0077b5; color: white; border: none; padding: 10px 20px; border-radius: 5px; cursor: pointer;">
    switch language
  </button>
</div>
<br>
<div id="english-text" style="display: block;">
  - 🤖 I currently work with IoT, Robotics, Computer Vision and Automation. <br>
  - 🧠 Currently studying Computer Vision with C++. <br>
  - 💻 I can collaborate on AI and Machine Learning projects. <br>
  - 🤜🤛 I accept help with OpenCV and YOLO. <br>
  - 🛰 I answer questions about Robotics, Embedded Systems, and some about Satellites. <br>
  - 📺 https://instagram.com/shaftrobotica <br>
  - 💼 https://www.linkedin.com/in/vitor-domingues-4852a62a8/ <br>
 <br>
</div>

<div id="portuguese-text" style="display: none;">
  - 🤖 Trabalho atualmente com IoT, Robótica, Visão Computacional e Automação. <br>
  - 🧠 Atualmente estudando Visão Computacional com C++. <br>
  - 💻 Posso colaborar em projetos de I.A. e Machine Learning. <br>
  - 🤜🤛 Aceito ajudas com OpenCV e YOLO. <br>
  - 🛰 Respondo dúvidas sobre Robótica, Sistemas Embarcados e algumas sobre Satélites. <br>
  - 📺 https://instagram.com/shaftrobotica <br>
  - 💼 https://www.linkedin.com/in/vitor-domingues-4852a62a8/ <br>
   <br>
</div>

<div style="display: flex; justify-content: center; margin-top: 20px;">
  <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px;">
    <img src="midia\kalmanTracker.gif" alt="Projeto 1" style="width: 100%; border-radius: 10px;">
    <img src="midia\Arduino3DLED.gif" alt="Projeto 2" style="width: 100%; border-radius: 10px;">
    <img src="midia\VisualServoing.gif" alt="Projeto 3" style="width: 100%; border-radius: 10px;">
  </div>
</div>

<div style="display: inline_block"><br>
  <img align="center" alt="Vitor-Py" height="35" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg">
  <img align="center" alt="Vitor-CPP" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-plain.svg">
  <img align="center" alt="Vitor-Arduino" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/arduino/arduino-original-wordmark.svg">
  <img align="center" alt="Vitor-ESP" height="30" src="https://static-00.iconduck.com/assets.00/espressif-icon-256x256-tjrijzih.png">
  <img align="center" alt="Vitor-MQTT" height="35" src="https://www.esegece.com/images/easyblog_articles/128/b2ap3_icon_mqtt.png">
  <img align="center" alt="Vitor-OpenCV" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/opencv/opencv-original.svg">
  <img align="center" alt="Vitor-YOLO" height="30" src="https://banner2.cleanpng.com/20180331/kew/avh5ccwbd.webp">
  <img align="center" alt="Vitor-ROS" height="21" width="80" src="https://www.ros.org/imgs/logo-white.png">
  <img align="center" alt="Vitor-Docker" height="30" src="https://media.licdn.com/dms/image/v2/D4E0BAQFWt4Tl53wjZQ/company-logo_200_200/company-logo_200_200/0/1705960989383/docker_logo?e=1748476800&v=beta&t=D0xDT0ol14XlmpQNYlLzRshN73uCkcHMyIJscKsD_eA">
</div><br>

<script>
  function toggleLanguage() {
    const englishText = document.getElementById('english-text');
    const portugueseText = document.getElementById('portuguese-text');
    const button = document.querySelector('button');

    if (englishText.style.display === 'block') {
      englishText.style.display = 'none';
      portugueseText.style.display = 'block';
      button.textContent = 'Switch to English | Alternar para Inglês';
    } else {
      englishText.style.display = 'block';
      portugueseText.style.display = 'none';
      button.textContent = 'Switch to Portuguese | Alternar para Português';
    }
  }
</script>