# 🍀 Projeto Lucky Number

> Jogo desenvolvido para a **[Official 2026 Unity Game Jam](https://itch.io/jam/official-unity-game-jam-2026)** no itch.io.
> **Tema: _Lucky Number_** — "um número que uma pessoa acredita trazer boa sorte" ou "um número com significado cultural, religioso ou simbólico positivo".

<!-- Substitua pelo link da página do jogo no itch.io quando estiver publicada -->
**▶ Jogar no navegador:** _em breve_ · **Página do jogo:** _em breve_

---

## 📅 Cronograma da Jam

| Marco | Data |
|---|---|
| Kickoff / revelação do tema | 05/11/2026 |
| Submissões abertas | 05/11/2026 — 15:30 |
| **Meta interna: jogo "feature complete"** | Fim do 7º dia (≈ 12/11/2026) |
| Período "The Buffer™" (só build, página e bugfix) | 12/11 → 14/11 |
| **Prazo final de submissão (sem atrasos!)** | **14/11/2026 — 09:00** |
| Votação da comunidade | 7 dias após o prazo |

> ⚠️ Confira o horário exato no seu fuso na página da jam. **Não há submissão atrasada.**
> Durante a votação **não é permitido atualizar os arquivos do jogo** — só a página (descrição, screenshots).

---

## 🎲 Conceito

<!-- Preencha durante o brainstorm -->
- **Pitch (1 frase):** _..._
- **Gênero:** _..._
- **Como o tema aparece:**
  - Mecânica: _(ex.: sorte, destino, superstição, números da sorte)_
  - Arte: _..._
  - Som: _..._
- **Loop principal:** _..._
- **Plataforma alvo:** WebGL (obrigatório para concorrer aos prêmios) + Windows

---

## 🕹️ Controles

| Ação | Teclado/Mouse | Gamepad |
|---|---|---|
| Mover | WASD / Setas | Analógico esquerdo |
| Ação | Espaço / Clique | A |
| Pausar | Esc | Start |

---

## 👥 Equipe (1–5 pessoas)

| Nome | Função | itch.io / contato |
|---|---|---|
| Hugo Novo Gouvea | _..._ | _..._ |
| _..._ | _..._ | _..._ |

---

## 🛠️ Tecnologia

- **Engine:** Unity `6000.x LTS` <!-- ajuste para a versão exata usada por toda a equipe -->
- **Render Pipeline:** URP <!-- ou Built-in -->
- **Input:** New Input System
- **Controle de versão:** Git + GitHub

### Como abrir o projeto

1. Instale o **Unity Hub** e a **mesma versão da Unity** listada acima (todos da equipe precisam usar a mesma).
2. Clone o repositório:
   ```bash
   git clone https://github.com/<usuario>/Game-ProjetoLuckyNumber.git
   ```
3. No Unity Hub: **Add → Add project from disk** e selecione a pasta clonada.
4. Abra a cena principal em `Assets/_Project/Scenes/`.

---

## 📁 Estrutura de pastas

```
Assets/
└── _Project/            # Tudo que é nosso fica aqui (separado de assets de terceiros)
    ├── Art/
    │   ├── Sprites/
    │   ├── Models/
    │   ├── Materials/
    │   └── Animations/
    ├── Audio/
    │   ├── Music/
    │   └── SFX/
    ├── Prefabs/
    ├── Scenes/
    ├── Scripts/
    │   ├── Core/        # GameManager, estados, utilidades
    │   ├── Gameplay/    # Mecânicas do jogo (sorte, números, etc.)
    │   └── UI/
    ├── ScriptableObjects/
    └── UI/
Assets/ThirdParty/       # Assets da Asset Store / externos (creditar abaixo!)
```

---

## 🌿 Fluxo de trabalho Git

- `main` → sempre jogável / buildável.
- Branches curtas por feature: `feature/nome-da-feature`, `fix/descricao`.
- **Evitem editar a mesma cena ao mesmo tempo** — prefiram trabalhar em prefabs ou combinar quem mexe em qual cena.
- Configuração recomendada da Unity (*Edit → Project Settings → Editor*):
  - **Version Control:** Visible Meta Files
  - **Asset Serialization:** Force Text
- Commits pequenos e frequentes; dê `git pull` antes de começar a trabalhar.

---

## ✅ Checklist de submissão

Requisitos da página da jam:

- [ ] Jogo feito na Unity
- [ ] **Build WebGL** enviado e marcado como *"This file will be played in the browser"* (obrigatório para prêmios)
- [ ] Build Windows (e/ou Mac) em `.zip` — se tiver build Linux, precisa de Windows ou Mac também
- [ ] Tamanho total < 1 GB
- [ ] Descrição curta do jogo
- [ ] Controles listados
- [ ] Lista de créditos de **todos** os assets externos
- [ ] Membros da equipe listados
- [ ] **Declaração de uso de IA generativa** (se houver) — explicar como foi usada
- [ ] Todos os arquivos necessários estão na página do itch (nada de downloads externos)
- [ ] Submeter **cedo** e atualizar depois — não esperar o último minuto

---

## 🎨 Créditos de assets

| Asset | Autor | Licença | Link |
|---|---|---|---|
| _..._ | _..._ | _..._ | _..._ |

---

## 🤖 Uso de IA generativa

<!-- Obrigatório declarar na página de submissão se houver qualquer uso. -->
_Descreva aqui se e como IA generativa foi usada (código, arte, áudio, texto...)._

---

## 🏆 Categorias de avaliação

**Comunidade:** Fun Factor · Art · Sound Design · Uniqueness/Creativity · Narrative Design
**Prêmios (júri Unity):** Unity Choice Awards (1º, 2º e 3º) · Best Student Game

---

## 🔗 Links úteis

- [Página da Jam](https://itch.io/jam/official-unity-game-jam-2026)
- Discord oficial da Unity — canais `#jam26-*` (link na página da jam)
- [Unity Learn — Get Started with Game Jams](https://learn.unity.com/)
- [Unity Asset Store](https://assetstore.unity.com/)
