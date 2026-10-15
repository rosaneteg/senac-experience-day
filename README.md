# Missão Dados

**Profissões do Futuro: quem você quer ser na era dos dados?**

Atividade interativa criada para o **Experience Day do Senac**. Em poucos minutos, cada participante descobre qual profissão da área de dados combina com o seu jeito. Depois, trabalha como analista de verdade, investigando as vendas de um café para ganhar pontos.

A atividade é uma página web: abre direto no navegador, sem instalar nada e sem criar conta.

---

## Para participantes

1. Abra o link que o palestrante passar: **[cole aqui o link do GitHub Pages]**
2. Digite seu nome ou apelido e clique em **Começar missão**.
3. **Missão 1 · Perfil:** responda 6 perguntas sobre você. Não existe resposta errada.
4. **Missão 2 · Detetive de dados:** analise a tabela de vendas de um café e responda 3 desafios. Cada acerto vale 100 pontos.
5. No final, mostre o seu **Cartão do Futuro** para o palestrante.

> Dica: na Missão 2, clique no nome de um produto para ver o gráfico dele.

### Os seis perfis possíveis

| Perfil | Em uma frase |
|---|---|
| Analista de Dados / BI | Transforma números em painéis e respostas |
| Cientista de Dados / IA | Cria modelos que preveem o que vai acontecer |
| Engenheiro(a) de Dados | Constrói os caminhos por onde os dados viajam |
| Especialista em Cibersegurança | Protege os dados contra ataques e vazamentos |
| Designer UX / Produto Digital | Usa dados de uso para criar apps fáceis |
| Desenvolvedor(a) de Sistemas | Programa os sistemas que geram e usam dados |

---

## Para professores e palestrantes

### Como a atividade entra na palestra

A palestra completa dura 30 minutos, e a atividade ocupa cerca de 12 deles no laboratório de informática:

| Tempo | Etapa |
|---|---|
| 0–10 min | Abertura, mercado de trabalho e as seis profissões (slides) |
| 10–22 min | **Missão Dados** nos computadores: perfil (4 min) e detetive (8 min) |
| 22–25 min | Enquete por perfil, premiação e explicação do que eles fizeram |
| 25–30 min | Caminhos no Senac e perguntas |

### Dicas de condução

- Durante a Missão 2, ajude com perguntas, não com respostas: *“Qual dia vendeu mais?”*, *“O que mudou junto com o suco?”*.
- Avise quando faltarem 4 minutos.
- Anote no quadro o nome de quem fizer 300 pontos para a premiação.
- Quem terminar cedo pode jogar de novo e tentar cair em outro perfil.

### Privacidade

A atividade não coleta nem envia nenhum dado. O nome digitado fica apenas na tela do próprio computador e some quando a página é fechada ou quando o participante clica em **Jogar de novo**.

---

## Personalizar

Todo o conteúdo fica no próprio `index.html`, dentro da tag `<script>`. Dá para editar em qualquer editor de texto, ou direto no GitHub pelo ícone de lápis.

| O que mudar | Onde procurar no código |
|---|---|
| Descrição dos perfis, ferramentas e primeiros passos | `const PROFILES` |
| Perguntas da Missão 1 | `const QUIZ` |
| Tabela de vendas e temperaturas do café | `const DATA` e `const TEMP` |
| Perguntas e explicações da Missão 2 | `const CHALLENGE` |

Se você mudar os números da tabela, revise também as respostas certas (`a:`) e as explicações (`why:`) em `CHALLENGE`.

---

## Estrutura do repositório

```
.
├── index.html     # a atividade Missão Dados
└── README.md      # este arquivo
```

---

## Créditos

Atividade desenvolvida para o **Experience Day · Senac**.
Os dados de mercado citados na palestra vêm do relatório *Future of Jobs 2025*, do Fórum Econômico Mundial.
Os dados de vendas do café são fictícios e foram criados para fins didáticos.

Responsável: **Rosanete Grassiani dos Santos** · [Senac Portão] · [rosanete.santos@docente.pr.senac.br]
