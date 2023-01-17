# Typescript-tutorial

Vamos a aprender typescript.


* Instalar node
* Instalar Vscode
* Instalar Typescript de manera global
<code>npm i -g typescript</code> 

Verificamos que esta bien instalado
<code>typescript -v</code>

Abrimos VS Code

Creamos un index.ts, la extension de typescript

---

Vamos con nuestro primer hola mundo

```typescript
  const userName = 'Radif'
  const age = 33
  console.log(`Hello world! My name is ${userName} and Im {age} years old`)
```

Ahora podemos compilar nuestro código typescript:

<code> tsc index.ts</code>

Si abrimos nuestro navegador de archivos, veremos que ha transpilado, y tenemos un archivo index.js creado por typescript.

> 
NOTA: Typescript compila a ES5, asique no veremos `bactics` y podemos ver variables creadas con 'var', esto lo hace porque es una version mas estable y compatible.

