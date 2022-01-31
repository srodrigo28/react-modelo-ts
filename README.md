# Esse projeto segue como modelo
    * React Typescrip
    * Styled Components
    * Bootstrap
    * Twaind CSS
## Usando biblioteca Styled Components
* npm install styled-components
* npm install -D @types/styled-components
* formas para importar components styed-components
    * criar um arquivo com extensão ts ou tsx exemplo estilo.ts
        * import styled from 'styled-components';
    * import { Container, Botao, Paragravo } from './styles.css';
    * import { Container } from './styles.css';
    * import { Botao } from './styles.css';
    * import * as C from './styles.css';
## Usando Bootstrap
    * formas de instalar o bootstrap
        * npm install react-bootstrap bootstrap@5.1.3
        * npm install react-bootstrap
    * forma de usar
        * importar no arquivo principal index.js ou index.ts, ou index.tsx
        * import 'bootstrap/dist/css/bootstrap.min.css';

## Usando Twaind
    * instalação no react-app
        * link: https://tailwindcss.com/docs/guides/create-react-app
        * npm install -D tailwindcss@latest postcss@latest autoprefixer@latest
        * npx tailwindcss init -p