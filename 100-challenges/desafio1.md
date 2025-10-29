### 1. Calcule a média de três números fornecidos pelo usuário.
<details>
    <summary> Code: </summary>

```javascript
    let num1 = prompt("Primeiro número:");
    let num2 = prompt("Segundo número:");
    let num3 = prompt("Terceiro número:");

    function somar(a, b, c) {
    return a + b + c / 3;
}
    let resultado = somar(Number(num1), Number(num2), Number(num3));
    console.log(resultado);
```