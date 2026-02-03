
# Seja bem-vindo(a) 👋🏼

Nesse repertório você encontrará diversos programas básicos que fiz enquanto estava estudando para minha faculdade. Alguns simples, outros complexos! Porém, sempre procuro estar em harmonia com o conhecimento, buscando assim, o a felicidade com o meu progressso.




## 🖥️ Uso/Exemplos (ambos usam console.log)

Script simples que faz médias para alunos, (personalizável de acordo com a quantidade de notas):

```javascript
<script>
        const quantidade = prompt("Quantas notas?")
        let nota = 0
        let soma = 0

        for(let contador = 1; contador <= quantidade; contador++){
            nota = Number(prompt("Digite a nota " + contador))
            soma = soma + nota
        }

        const media = soma / quantidade
        console.log("A média final é: " + media)
    </script>
```

Script "complexo" que fiz. Uma calculadora usando as 4 operações essenciais do dia a dia:



```javascript
    <script type="text/Javascript" src="funcoes.js"></script>
</head>
<body>
    
    <form action="">
        N1: <input type="number" id="n1" />
        N2: <input type="number" id="n2" /> <br>

        <input type="button" value="Somar" onclick="calcular('+')"> <br>
        <input type="button" value="Subtrair" onclick="calcular('-')"> <br>
        <input type="button" value="Multiplicar" onclick="calcular('*')"> <br>
        <input type="button" value="Dividir" onclick="calcular('/')"> <br>

        <h1 id="resultado">O resultado da operação é </h1>
    </form>
</body>
</html>

=================================== JAVASCRIPT ===================================

        function calcular(operacao){
        const n1 = document.getElementById('n1').value
        const n2 = document.getElementById('n2').value
       
        let resultado
        switch(operacao){
            case '+': resultado = Somar(n1, n2); break;
            case '-': resultado = Subtrair(n1, n2); break;
            case '*': resultado = Multiplicar(n1, n2); break;
            case '/': resultado = Dividir(n1, n2); break;
        }

        document.getElementById('resultado').innerHTML = "O resultado é " + resultado
    } 

    function Somar(n1, n2){
        return Number(n1) + Number(n2)
    }
    
    function Subtrair(n1, n2){
        return Number(n1) - Number(n2)
    }
    
    function Multiplicar(n1, n2){
        return Number(n1) * Number(n2)
    }
    
    function Dividir(n1, n2){
        if(n2 == 0){
            console.log("não é possível calcular com 0")
            return null
        } else {
            return Number(n1) / Number(n2)
        }
    }
```
É possivel notar que ambos os sistemas possuem uma certa facilidade quando trata-se da compreensão, tornando meus programas algo que seja de fácil acesso para todos!

## Nota Importante: 💭

Como primeiro portfólio, tudo aqui listado é um documento totalmente válido para primeiras impressões. A finalidade desse documento é fixar o conteúdo que fora aprendido por mim durante minha trajetória no ensino superior. Logo, qualquer erro que esteja aqui, pode  ser comentável para aprendizado mútuo, servindo também para apoiar pessoas novas com intuito de ramificar o sistema. 
<br> 
Muito obrigado a todos que me apoiam a cada dia, Deus abençoe! 


