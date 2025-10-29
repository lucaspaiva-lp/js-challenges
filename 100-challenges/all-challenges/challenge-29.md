### 29. Crie um cronômetro simples que conte até 10.
<details>
    <summary> Result: </summary>

```javascript
/*
    - Exibe números de 1 a 10 com intervalo de 1000 milisegundos.
    - Usa recursão com setTimeout para controlar o tempo.
    - A cada iteração, o código exibe o valor atual, incrementa o contador em +1 
    e repete o processo até atingir a condição final, quando então exibe "Fim!".
 */
let contador = 1;

function contar() {
    console.log(contador);
    contador++; 

    if (contador <= 10) { 
        setTimeout(contar, 1000); segundo.
    } else {
        console.log("Fim!");
    }
}

contar();
```

