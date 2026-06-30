<div align="center">


<img width="537" height="672" alt="5  Ícone do jogo (Humanidade)" src="https://github.com/user-attachments/assets/9faf89b9-1e21-433a-b934-0f01001f9b5a" />



#  Reminiscence of Shatters

### Um metroidvania 2D em pixel art 

[![Unity](https://img.shields.io/badge/Engine-Unity-000000?style=flat-square&logo=unity)](https://unity.com/)
[![C#](https://img.shields.io/badge/Language-C%23-239120?style=flat-square&logo=c-sharp)](https://learn.microsoft.com/dotnet/csharp/)
[![Status](https://img.shields.io/badge/Status-Beta%2FConceito-yellow?style=flat-square)]()
[![License](https://img.shields.io/badge/Tipo-Projeto%20Acadêmico%20(TCC)-blue?style=flat-square)]()

</div>

---

##  Sobre o projeto

**Reminiscence of Shatters** é um jogo digital 2D, em pixel art, do subgênero **metroidvania**, desenvolvido como Trabalho de Conclusão de Curso (TCC) do Ensino Médio com Habilitação Profissional em Programação de Jogos Digitais — ETEC Parque da Juventude (Centro Estadual de Educação Tecnológica Paula Souza), 2024.

> *Uma jovem espadachim sem memórias sobre o seu passado explora uma outra realidade, buscando voltar para a realidade dos humanos e encontrar as respostas deste universo caótico.*

O projeto nasceu da popularidade crescente dos jogos indie do subgênero metroidvania com elementos *souls-like* — referências diretas a títulos como **Blasphemous** e **Hollow Knight** — e teve como meta produzir, com uma equipe pequena e sem experiência prévia em Unity, uma experiência completa de exploração, combate e progressão de atributos.

---

## 🎯 Objetivo

- Desenvolver um metroidvania 2D funcional do zero, aplicando lógica de programação e POO em C#.
- Criar uma identidade visual própria em pixel art, com paleta de cores e estilo coerentes.
- Implementar sistemas centrais do gênero: exploração não-linear, combate, progressão por atributos e mapa interativo.
- Servir como prova de conceito (*beta*) de um projeto maior, validando mecânicas antes de uma expansão futura.
- Aproximar o desenvolvimento independente do público, através de divulgação no Instagram e planejamento de lançamento gratuito.

---

## 🛠️ Tecnologias utilizadas

| Ferramenta | Função no projeto |
|---|---|
| **Unity** | Game engine principal, responsável pela lógica, física e renderização do jogo |
| **C# (Visual Studio)** | Linguagem e editor utilizados para toda a programação |
| **LibreSprite** | Criação de sprites, animações em pixel art e paletas de cor |
| **Krita** | Ilustração digital — artes conceituais de personagens e cutscene |

---

## 🧩 Principais funcionalidades implementadas

### Jogabilidade
- Movimentação, pulo (simples/duplo), dash/esquiva com imunidade a dano e ataque corpo a corpo (combo de 3 hits)
- Sistema de checkpoints com respawn
- Inimigos com IA simples de patrulha → aproximação → ataque (golem, javali, aranha) e um chefe final (Lorde)

### Progressão e RPG-lite
- **5 atributos** (Vigor, Vitalidade, Resistência, Força, Mana) evoluídos via *fragmentos* coletados ao derrotar inimigos — sistema inspirado diretamente em *Dark Souls*
- Inventário dividido em **Armas**, **Itens** e **Acessórios**, cada um alterando atributos e status do personagem
- Risco/recompensa: fragmentos ficam no local da morte e desaparecem se o jogador morrer novamente sem recuperá-los

### Exploração
- Dois cenários interligados (floresta e caverna) com layout não-linear típico de metroidvania
- Mapa que se completa conforme a exploração avança, com áreas proporcionais e coloridas conforme o cenário real (referência direta a *Blasphemous*)
- Itens colecionáveis com narrativa ambiental (cartas, baú trancado, equipamentos escondidos)

### Interface (UI/HUD)
- Barra de vida e mana, contador de poções e fragmentos
- Menus de inventário e atributos navegáveis via teclado
- Sistema de cartas/lore opcional, lido nos checkpoints

---

## 🎮 Controles (PC)

| Tecla | Ação |
|---|---|
| `A` / `D` | Andar para a esquerda / direita |
| `J` | Atacar |
| `K` | Pular |
| `L` | Esquivar (dash) |
| `I` | Tomar poção |
| `X` | Interagir com o cenário / abrir menu de atributos |
| `Esc` | Abrir inventário |
| `Shift` | Abrir mapa |
| `Z` | Ler carta (próximo a checkpoints) |

---

## 🎨 Referências e direção de arte

O projeto bebe de três fontes principais, cada uma influenciando um aspecto distinto:

- **Blasphemous** (The Game Kitchen, 2019) — referência de jogabilidade e do sistema de mapa progressivo
- **Dark Souls** (FromSoftware, 2011) — referência temática (humano frágil contra criaturas fantásticas) e do sistema de atributos/fragmentos
- **Ori and the Blind Forest** (Moon Studios, 2015) — referência de ambientação e paleta de cores do cenário de floresta

A narrativa é introduzida por uma cutscene ilustrada (Krita) que estabelece a lore do universo: uma "Era do Caos", a ascensão e queda do "Primeiro Lorde", e a fragmentação da realidade em múltiplos mundos — cada um com seu próprio Lorde e criaturas únicas.

---

## 🧪 Desenvolvimento e desafios

O projeto foi dividido em 4 fases: **planejamento** (história, personagens, cenário) → **base do jogo** (movimentação e colisão) → **mecânicas e animações** (inventário, atributos, HUD) → **finalização** (inimigos e polimento).

Principais desafios enfrentados pela equipe:
- Aprender Unity e C# do zero, sem experiência prévia, através de cursos, vídeos e testes constantes
- Redimensionar o escopo do projeto, priorizando entregar um recorte inicial completo e bem polido em vez de um jogo maior incompleto
- Organizar a divisão de tarefas entre os integrantes da equipe

---

## 📣 Marketing

A divulgação foi feita via Instagram (**@celestiaestudio_**), apresentando ao público ícones, artes conceituais e bastidores do desenvolvimento (cutscene, sprites, animações). O plano de lançamento previa disponibilizar a versão beta gratuitamente na **Steam**, coletando feedback da comunidade antes de uma versão final.

---

## 👥 Equipe

| Nome | 
|---|
| Erick Ueda Cavalcante |
| Guilherme Carvalho Venancio |
| Gustavo Reis Ramirez Lima |
| João Vitor Trindade Silva |
| Kauan Da Silva Peres |
| Marcelo Alexandre Oliveira Fernandes |
| Natan Cardoso De Oliveira |

**Instituição:** ETEC Parque da Juventude — Centro Estadual de Educação Tecnológica Paula Souza
**Curso:** Ensino Médio com Habilitação Profissional em Programação de Jogos Digitais
**Ano:** 2024

---

## 📚 Referências citadas no relatório técnico

- BLASPHEMOUS. The Game Kitchen, 2019.
- DARK Souls. FromSoftware, 2011.
- ORI and the Blind Forest. Moon Studios, 2015.
- Tutoriais e cursos sobre Unity, pixel art e animação de sprites (lista completa disponível no relatório técnico em PDF).

---

<div align="center">

*Este repositório documenta o desenvolvimento acadêmico do jogo, com foco em conceitos de game design, programação orientada a objetos e produção de arte 2D.*

</div>
