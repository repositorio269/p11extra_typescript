# Proyecto React con TypeScript

## Generación proyecto

Existen varias opciones de implementación de TypeScript en React pero quizás la más sencilla es crear el proyecto mediante la herramienta [Vite](https://vitejs.dev/)

El comando para generar un proyecto mediante Vite es:

```
npm init @vitejs/app <nombre-proyecto>
```

Una vez inicializado seleccionar react y typescript y se crea el proyecto, la estructura es prácticamente similar a la creada con Create-react-app con la diferencia que los archivos serán tsx (de TypeScript y JSX).

No es necesario realizar configuración adicional para la transpilación de TypeScript, se encarga el compilador, solamente cambia el script en dev:

```
npm run dev
```

## Uso de TypeScript

Una vez instalado podemos hacer uso de toda la capa de tipado fuerte que proporciona [TypeScript](https://www.typescriptlang.org/docs/handbook/intro.html)

Los básicos son el empleo de Interfaces como tipo de dato propio, ver archivo UserInterface.ts, y su implementación en los estados con el operador diamante, por ejemplo ver archivo App.tsx:

```
...
  const [user, setUser] = useState<User>(
...
```

pjimenez@corenetworks.es

