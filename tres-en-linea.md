# Tres en linea

### Resumen del Proyecto en Markdown

#### Square Component
El componente `Square` representa un cuadrado en el tablero del juego. Recibe dos propiedades (`value` y `onSquareClick`). El valor del cuadrado se muestra en un botón y se actualiza al hacer clic en él.

```jsx
function Square({ value, onSquareClick }) {
  return (
    <button className="square" onClick={onSquareClick}>
      {value}
    </button>
  );
}
```

#### Board Component
El componente `Board` representa el tablero del juego. Contiene una matriz de cuadrados y maneja los clics en los cuadrados. Muestra el estado actual del juego y el mensaje de ganador si hay uno.

```jsx
function Board({ xIsNext, squares, onPlay }) {
  // ... (código para manejar clics, verificar ganador, etc.)
  return (
    <>
      <div className="status">{status}</div>
      {/* Renderiza los cuadrados usando el componente Square */}
      {/* Cada cuadrado tiene su propio manejador de clics */}
      <div className="board-row">
        {/* ... (renderización de los primeros tres cuadrados) */}
      </div>
      {/* ... (renderización de los siguientes dos conjuntos de tres cuadrados) */}
    </>
  );
}
```

#### Game Component
El componente `Game` es el componente principal que representa el juego. Maneja el historial de movimientos, el estado actual y las funciones para jugar y retroceder en la historia del juego.

```jsx
export default function Game() {
  // ... (estado y funciones para gestionar el historial y el estado actual)
  return (
    <div className="game">
      <div className="game-board">
        {/* Renderiza el tablero usando el componente Board */}
        <Board xIsNext={xIsNext} squares={currentSquares} onPlay={handlePlay} />
      </div>
      {/* Renderiza la información del juego, como la lista de movimientos */}
      <div className="game-info">
        <ol>{moves}</ol>
      </div>
    </div>
  );
}
```

#### calculateWinner Function
La función `calculateWinner` determina si hay un ganador en el juego. Recibe la matriz de cuadrados y verifica si hay una línea ganadora.

```jsx
function calculateWinner(squares) {
  // ... (código para verificar líneas ganadoras)
  return null;
}
```

Este proyecto es una implementación básica del juego Tic Tac Toe (Tres en línea) en React, con componentes bien estructurados que gestionan el estado y la presentación del juego.
