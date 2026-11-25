# Exercícios de Estrutura Condicional em Java ☕

Projeto com a implementação completa dos **45 exercícios** sobre estruturas condicionais em Java (`if`, `if/else`, `else if`, operador ternário e desafios práticos).

---

## 📁 Estrutura do Projeto

Os exercícios estão organizados em pacotes temáticos dentro da pasta `src/`:

```text
src/
├── parte1/                   # Exercícios com 'if' simples
│   ├── Exer1.java            # 1. Verificar maioridade
│   ├── Exer2.java            # 2. Verificar saldo positivo
│   ├── Exer3.java            # 3. Verificar nota mínima
│   ├── Exer4.java            # 4. Verificar temperatura alta
│   ├── Exer5.java            # 5. Verificar desconto
│   ├── Exer6.java            # 6. Verificar login
│   ├── Exer7.java            # 7. Verificar estoque
│   ├── Exer8.java            # 8. Verificar velocidade
│   ├── Exer9.java            # 9. Verificar presença
│   └── Exer10.java           # 10. Verificar idade para entrada
├── parte2/                   # Exercícios com 'if/else'
│   ├── Exer11.java           # 11. Maior ou menor de idade
│   ├── Exer12.java           # 12. Aprovado ou reprovado
│   ├── Exer13.java           # 13. Saldo para compra
│   ├── Exer14.java           # 14. Login no sistema
│   ├── Exer15.java           # 15. Número positivo ou negativo
│   ├── Exer16.java           # 16. Produto com desconto
│   ├── Exer17.java           # 17. Verificar CNH
│   ├── Exer18.java           # 18. Par ou ímpar
│   ├── Exer19.java           # 19. Frete grátis
│   └── Exer20.java           # 20. Verificar acesso
├── parte3/                   # Exercícios com 'else if'
│   ├── Exer21.java           # 21. Classificação por idade
│   ├── Exer22.java           # 22. Conceito da nota
│   ├── Exer23.java           # 23. Faixa salarial
│   ├── Exer24.java           # 24. Temperatura do dia
│   ├── Exer25.java           # 25. Nível do jogador
│   ├── Exer26.java           # 26. Status do pedido
│   ├── Exer27.java           # 27. Categoria de produto
│   ├── Exer28.java           # 28. Plano de assinatura
│   ├── Exer29.java           # 29. IMC simplificado
│   └── Exer30.java           # 30. Desconto por tipo de cliente
├── parte4/                   # Exercícios com operador ternário
│   ├── Exer31.java           # 31. Maioridade com ternário
│   ├── Exer32.java           # 32. Aprovação com ternário
│   ├── Exer33.java           # 33. Saldo suficiente
│   ├── Exer34.java           # 34. Número par ou ímpar
│   ├── Exer35.java           # 35. Verificar desconto
│   ├── Exer36.java           # 36. Verificar login
│   ├── Exer37.java           # 37. Verificar permissão
│   ├── Exer38.java           # 38. Temperatura
│   ├── Exer39.java           # 39. Frete
│   └── Exer40.java           # 40. Bônus salarial
└── parte5/                   # Desafios mistos
    ├── Exer41.java           # 41. Sistema de aprovação completo
    ├── Exer42.java           # 42. Sistema de compra
    ├── Exer43.java           # 43. Sistema de cinema
    ├── Exer44.java           # 44. Sistema de login
    └── Exer45.java           # 45. Sistema de desconto progressivo
```

---

## 🚀 Como Executar

### Opção 1: Pelo IntelliJ IDEA
Cada classe possui seu próprio método `public static void main(String[] args)`.
1. Abra o arquivo desejado (por exemplo, `Exer1.java`).
2. Clique na **seta verde de Run (▶️)** na margem esquerda (ao lado de `public class` ou do método `main`).
3. O resultado será exibido no console do IntelliJ.

### Opção 2: Pelo Terminal / Linha de Comando (PowerShell)
```powershell
# Compilar todos os arquivos do projeto
javac -encoding UTF-8 -d out (Get-ChildItem -Recurse -Filter *.java src).FullName

# Executar qualquer exercício (exemplos):
java -cp out parte1.Exer1
java -cp out parte2.Exer16
java -cp out parte3.Exer25
java -cp out parte4.Exer34
java -cp out parte5.Exer45
```

---

## 📝 Conteúdos Abordados

1. **`if` Simples (1 a 10):** Tomada de decisão unária com condições (`>=`, `>`, `boolean`).
2. **`if / else` (11 a 20):** Estrutura condicional binária para caminhos alternativos e operadores lógicos (`&&`, `||`, `%`).
3. **`else if` Encadeado (21 a 30):** Classificação em faixas de valores (idade, notas, salários, IMC, códigos de menu).
4. **Operador Ternário (31 a 40):** Expressões concisas (`condicao ? valorSeVerdadeiro : valorSeFalso`).
5. **Desafios Mistos (41 a 45):** Regras de negócio combinadas, precedência de validações e cálculos progressivos.
