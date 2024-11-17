# 💬 Random Chat App

<div align="center">

[Vista Previa del Proyecto](https://desafio-consumo-api-rest-two.vercel.app/)

### 🌟 Una aplicación de chat que conecta dos usuarios aleatorios en tiempo real

---

## ✨ Características Principales

<div align="center">

| 🎯 Feature             | 📝 Descripción                                             |
| ---------------------- | ---------------------------------------------------------- |
| 👥 Usuarios Aleatorios | Generación automática de 2 perfiles usando Random User API |
| 🎨 Mensajes Coloridos  | Personalización del color de fondo para cada mensaje       |
| 📱 Diseño Responsive   | Adaptable a cualquier dispositivo                          |
| ⚡ Tiempo Real         | Actualización instantánea de mensajes                      |

</div>

## 🚀 Tecnologías Utilizadas

<div align="center">

![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D)
![Axios](https://img.shields.io/badge/Axios-671ddf?style=for-the-badge&logo=axios&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

</div>

## 📦 Instalación

1️⃣ **Clona el repositorio**

```bash
git clone https://github.com/FideoKojima/DesafioConsumoAPI-REST.git
```

2️⃣ **Instala las dependencias**

```bash
npm install
```

3️⃣ **Inicia el servidor de desarrollo**

```bash
npm run serve
```

## 🎯 Estructura del Proyecto

```
random-chat-app/
├── 📁 src/
│   ├── 📁 components/
│   │   ├── 📄 ChatWindow.vue
│   │   ├── 📄 MessageInput.vue
│   │   └── 📄 UserProfile.vue
│   ├── 📄 App.vue
│   └── 📄 main.js
├── 📄 package.json
└── 📄 README.md
```

## 💡 Características Detalladas

### 👥 Gestión de Usuarios

- Generación automática de perfiles
- Visualización de avatares y nombres
- Información detallada de usuarios

### 💬 Sistema de Chat

- Envío de mensajes personalizados
- Selección de colores para mensajes
- Historial de conversación
- Indicador de propietario del mensaje

## ⚙️ Requerimientos Técnicos

✅ Axios para consumo de API Random User

```javascript
axios.get("https://randomuser.me/api/").then((response) => {
  // Procesamiento de datos
});
```

✅ Ciclo de vida de componentes

```javascript
mounted() {
  this.loadRandomUsers();
}
```

## 🤝 Cómo Contribuir

1. 🍴 Fork el proyecto
2. 🔧 Crea tu rama de características
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. 💫 Commit tus cambios
   ```bash
   git commit -m '✨ Add some AmazingFeature'
   ```
4. 📤 Push a la rama
   ```bash
   git push origin feature/AmazingFeature
   ```
5. 🔄 Abre un Pull Request

**¿Te gustó este proyecto? ¡Dale una ⭐!**

</div>

---

<div align="center">

Hecho con ❤️ por [Luis Suarez]

</div>
