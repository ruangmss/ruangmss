```jsx id="kwj5rm"
import React from 'react';

import {
  HTML,
  CSS,
  JavaScript,
  ReactJS,
  TailwindCSS,
} from './technologies';

import {
  Git,
  GitHub,
  Vite,
  VSCode,
} from './tools';

const RuanGomes = () => {
  const developer = {
    name: 'Ruan Gomes',
    role: 'Desenvolvedor Front-end',
    education: 'Sistemas para Internet — UNIVALI',
    work: 'Secretaria Municipal de Tecnologia de Itajaí — SETEC',
  };

  const technologies = [
    HTML,
    CSS,
    JavaScript,
    ReactJS,
    TailwindCSS,
  ];

  const tools = [
    Git,
    GitHub,
    Vite,
    VSCode,
  ];

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

  const focus = [
    'React',
    'JavaScript',
    'Tailwind CSS',
    'Arquitetura Front-end',
    'UI/UX',
    'Acessibilidade',
    'Design Systems',
  ];

  return (
    <Developer name={developer.name} role={developer.role}>
      <About>
        <p>
          Sou estudante de {developer.education} e atuo como estagiário de
          desenvolvimento na {developer.work}.
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
      </About>

      <Stack>
        <Technologies items={technologies} />
        <Tools items={tools} />
      </Stack>

      <Development>
        {knowledge.map((item) => (
          <Skill key={item}>{item}</Skill>
        ))}
      </Development>

      <Goals>
        <p>
          Busco me especializar em desenvolvimento front-end, combinando
          engenharia e design para construir interfaces funcionais,
          intuitivas e visualmente bem elaboradas.
        </p>

        <Focus technologies={focus} />
      </Goals>

      <Contact
        github="github.com/ruangmss"
        email="ruan.gmss@outlook.com"
      />

      <Footer>
        Em constante evolução, um commit de cada vez.
      </Footer>
    </Developer>
  );
};

export default RuanGomes;
```
