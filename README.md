# Alejandro.js

```javascript
// Nombre: Alejandro
// Origen: Argentina
// Lenguajes principales: JavaScript, TypeScript, PHP
// Aprendiendo: Java, Python
// Intereses: Desarrollo web, IA, videojuegos

const aboutMe = {
    name: "Alejandro",
    location: "Argentina",
    languages: ["JavaScript", "TypeScript", "PHP"],
    learning: ["Java", "Python"],
    hobbies: ["Desarrollo web", "Inteligencia Artificial", "Videojuegos"],
    contact: {
        email: "alejandro@example.com",
        github: "https://github.com/tu-usuario",
        linkedin: "https://linkedin.com/in/tu-usuario"
    }
};

function greet() {
    console.log(`Hola, soy ${aboutMe.name} de ${aboutMe.location}.`);
    console.log(`Mis lenguajes principales son: ${aboutMe.languages.join(", ")}.`);
    console.log(`Actualmente estoy aprendiendo: ${aboutMe.learning.join(", ")}.`);
    console.log(`Mis intereses incluyen: ${aboutMe.hobbies.join(", ")}.`);
    console.log("¡No dudes en contactarme!");
}

greet();
