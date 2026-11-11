# Atividade A2 — Site Pessoal / Portfólio (instruções)

Valor: 2,0 pontos (4 checkpoints de 0,5). Individual. Entrega no Blackboard.

| CP | Entrega | Foco |
|----|---------|------|
| CP1 | 15/09 | HTML semântico + CSS básico |
| CP2 | 29/09 | Flexbox, Grid, media queries |
| CP3 | 10/11 | Git, deploy, JavaScript |
| CP4 | 17/11 | Versão final + vídeo de 2 min (**obrigatório**) |

Regra crítica: sem o vídeo do CP4, todo o trabalho individual vale zero. Não apague etapas anteriores.

## 0. Preparar
1. Descompacte `meu-portfolio.zip`.
2. Abra a pasta no VS Code; teste com a extensão Live Server ou abrindo `index.html`.
3. **Troque todo texto entre [colchetes]** e o texto de apresentação por conteúdo seu (nada de texto genérico). Troque `img/avatar.svg` por sua foto, se quiser.

## CP1 — Estrutura e CSS
- [ ] 5 páginas com o mesmo menu: index, curriculo, formulario, multimidia, graficos
- [ ] Tags semânticas (`header`, `nav`, `main`, `section`, `article`, `footer`)
- [ ] Um único `css/estilos.css`; caminhos relativos (nada de `C:\Users\...`)
- [ ] Currículo com listas e tabela; formulário com nome, e-mail, assunto, mensagem
- [ ] Multimídia com `video`/`audio` e `iframe`; gráficos com `canvas` e SVG
- [ ] Validar em https://validator.w3.org (HTML) e https://jigsaw.w3.org/css-validator/ (CSS)
- Entrega: zip `CP1_Nome_Sobrenome_Turma.zip` no Blackboard.

## CP2 — Responsivo
- [ ] Flexbox no menu e nos cartões · [ ] Grid no currículo
- [ ] Media queries mobile-first (`min-width`)
- [ ] Teste: F12 → modo dispositivo, larguras 360, 768 e 1280 px
- Entrega: `CP2_Nome_Sobrenome_Turma.zip`.

## CP3 — Git, deploy e JavaScript
```bash
cd meu-portfolio
git init
git add .
git commit -m "feat: estrutura inicial do portfólio"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/meu-portfolio.git
git push -u origin main
```
Faça commits pequenos e descritivos (o histórico é avaliado). Deploy: no GitHub, Settings → Pages → Branch `main` → Save; o link (HTTPS) sai em ~1 min. O tema claro/escuro com `localStorage` já está em `js/scripts.js`; teste recarregando a página.
- Entrega: link do repositório + link do site no ar.

## CP4 — Versão final e vídeo
- [ ] Console (F12) sem erros · [ ] README com autor, link do deploy e instruções
- [ ] Vídeo de 2 min mostrando o site e **explicando o seu código** (você deve saber explicar cada trecho, inclusive os gerados por IA)
- Roteiro: 0:00 apresentação · 0:20 HTML semântico · 0:50 CSS/responsividade · 1:20 JS + localStorage · 1:45 Git/deploy.

## Checklist final
Caminhos relativos · sem texto genérico · repositório com histórico · site em HTTPS · vídeo enviado.
