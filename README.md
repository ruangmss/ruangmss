# Olá, eu sou o Ruan Gomes! 👋

```jsx
import {
  React,
  JavaScript,
  TailwindCSS,
  UIUX,
} from './skills';

import { UNIVALI, SETEC } from './experience';

const RuanGomes = () => {
  const role = 'Desenvolvedor Front-end';

  const technologies = {
    frontend: ['HTML', 'CSS', 'JavaScript', 'React', 'Tailwind CSS'],
    tools: ['Git', 'GitHub', 'Vite', 'VS Code'],
  };

  const currentlyLearning = [
    'React',
    'JavaScript',
    'Tailwind CSS',
    'Arquitetura Front-end',
    'UI/UX',
    'Acessibilidade',
    'Design Systems',
  ];

  return (
    <Developer
      name="Ruan Gomes"
      role={role}
      university={UNIVALI}
      workplace={SETEC}
      technologies={technologies}
      learning={currentlyLearning}
    />
  );
};

export default RuanGomes;
```

### `about.jsx`

```jsx
const About = () => {
  return (
    <section>
      <h2>Sobre mim</h2>

      <p>
        Sou estudante de Sistemas para Internet na UNIVALI e atuo como
        estagiário de desenvolvimento na Secretaria Municipal de Tecnologia
        de Itajaí (SETEC).
      </p>

      <p>
        Meu foco é desenvolvimento front-end, buscando criar interfaces
        bem estruturadas, responsivas, acessíveis e com uma boa experiência
        de usuário.
      </p>

      <p>
        Atualmente, estou aprofundando meus conhecimentos em React,
        JavaScript, Tailwind CSS e UI/UX.
      </p>
    </section>
  );
};
```

## 🛠️ `technologies.js`

### Front-end

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### Ferramentas

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

## 💻 `development.jsx`

```jsx
const Development = () => {
  const knowledge = [
    'Componentização e reutilização de interfaces com React',
    'Gerenciamento de estado com Hooks e Context API',
    'Criação de Custom Hooks',
    'Navegação com React Router',
    'Consumo e integração de APIs REST',
    'JavaScript moderno (ES6+)',
    'HTML semântico e acessibilidade',
    'Layouts responsivos com Flexbox, Grid e Tailwind CSS',
    'Organização e manutenção de código front-end',
    'Fundamentos de UI/UX e Design de Interfaces',
    'Versionamento com Git e GitHub',
  ];

  return (
    <section>
      <h2>Sobre meu desenvolvimento</h2>

      {knowledge.map((skill) => (
        <Skill key={skill}>{skill}</Skill>
      ))}
    </section>
  );
};
```

## 🎯 `goals.js`

```js
export const goal = {
  area: 'Desenvolvimento Front-end',

  mission:
    'Combinar engenharia e design para construir interfaces funcionais, intuitivas e visualmente bem elaboradas.',

  focus: [
    'React',
    'JavaScript',
    'Tailwind CSS',
    'Arquitetura Front-end',
    'UI/UX',
    'Acessibilidade',
    'Design Systems',
  ],
};
```

## 📫 `contact.js`

```js
export const contact = {
  github: 'github.com/ruangmss',
  email: 'ruan.gmss@outlook.com',
};
```

[![GitHub](https://img.shields.io/badge/GitHub-ruangmss-181717?style=for-the-badge&logo=github)](https://github.com/ruangmss)
[![E-mail](https://img.shields.io/badge/Email-ruan.gmss%40outlook.com-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white)](mailto:ruan.gmss@outlook.com)

```jsx
while (true) {
  learn();
  build();
  improve();
  commit();
}
```

<p align="center">
  <i>Em constante evolução, um commit de cada vez.</i>
</p>
