# FollowMouse App

Este es un componente React que permite activar o desactivar el seguimiento del puntero del mouse.

## Descripción

El componente `FollowMouse` permite activar o desactivar el seguimiento del puntero del mouse dentro de un área específica. Cuando se activa, un círculo semi-transparente sigue la posición del puntero del mouse. 

## Uso

Para utilizar este componente, sigue estos pasos:

1. Integra el componente `FollowMouse` en tu aplicación React.
2. Haz clic en el botón "Activar" para permitir que el círculo siga el puntero del mouse.
3. Haz clic en el botón "Desactivar" para detener el seguimiento del puntero del mouse.

## Funcionalidades

- **Seguimiento del Mouse**: El círculo semi-transparente sigue la posición del puntero del mouse cuando la función está habilitada.
- **Activar/Desactivar**: El usuario puede activar o desactivar el seguimiento del puntero del mouse haciendo clic en el botón correspondiente.

## Componentes

- **FollowMouse**: Componente principal que gestiona el seguimiento del puntero del mouse.
- **App**: Componente principal que integra el componente `FollowMouse` en la aplicación.

## Notas

- El componente utiliza React Hooks (`useState` y `useEffect`) para gestionar el estado y el ciclo de vida.
- Se aplican estilos CSS en línea para el círculo semi-transparente que sigue el puntero del mouse.

## Ejemplo de Uso

```jsx
import React from 'react';

const FollowMouse = () => {
  // Código del componente FollowMouse ...
};

function App() {
  return (
    <main>
      <FollowMouse />
    </main>
  );
}

export default App;
```




© 2024 Desarrollado por [Tu Nombre o Equipo]
