# leituras-engenharia
leitura do livro código limpo
# Código Limpo — capítulos 2, 4 e 5: resumo e por que importam

> Notas de um estudante do 1º semestre de Engenharia de Software.
> Foco nos conceitos e no motivo de cada um deles fazer diferença na prática.

---

## Cap. 2 — Nomes com significado

**O que é:** todo identificador no código — variável, função, classe — deve revelar sua intenção sem precisar de explicação extra.

```java
// ruim — o que é d?
int d;

// bom — agora está claro
int diasDesdeUltimaModificacao;
```

**Por que importa:** código é lido muito mais do que escrito. Um nome ruim força quem lê a parar e deduzir o que aquilo representa. Multiplicado por centenas de variáveis num projeto, isso vira ruído constante.

A regra prática do Martin: se o nome precisa de comentário pra ser entendido, reescreve o nome.

---

## Cap. 4 — Comentários

**O que é:** comentário é uma compensação por código que não se explica sozinho — não uma virtude.

**Por que importa:** comentários envelhecem. O código muda, o comentário fica parado. Com o tempo, ele passa a descrever algo que não existe mais — e um comentário errado é mais danoso do que nenhum comentário.

Quando comentários fazem sentido:
- Explicar o *porquê* de uma decisão (não o *o quê*)
- Alertar sobre comportamento não óbvio
- Documentar APIs públicas

O objetivo, segundo Martin, é escrever código tão claro que comentários se tornem exceção.

---

## Cap. 5 — Formatação

**O que é:** a organização visual do código — espaçamento, tamanho de linha, proximidade entre funções relacionadas — afeta diretamente a leitura.

**Por que importa:** num time, todo mundo lê o código de todo mundo. Formatação ruim força o leitor a montar o quebra-cabeça antes de entender a lógica. É um custo desnecessário que se acumula.

Pontos principais:
- Separe conceitos distintos com linhas em branco
- Mantenha funções relacionadas próximas umas das outras
- Linhas curtas são mais fáceis de acompanhar

---

**Referência:** MARTIN, Robert C. *Código Limpo*. Pearson, 2009.

#cleancode #java #softwaredevelopment #beginners
