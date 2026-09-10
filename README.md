# Radiestesia SOLAR — formulário

Aplicação estática em HTML/CSS/JavaScript. Não exige servidor, banco de dados ou processo de build.

## Publicar no GitHub Pages
1. Crie ou abra o repositório desejado no GitHub.
2. Envie `index.html` e a pasta `assets` mantendo a mesma estrutura.
3. Em **Settings > Pages**, em **Build and deployment**, escolha **Deploy from a branch**.
4. Selecione a branch `main` e a pasta `/ (root)` e salve.

## Estrutura
```
index.html
assets/
  basico.png
  sacral.png
  plexo-solar.png
  cardiaco.png
  laringeo.png
  frontal.png
  coronario.png
```

## Relatório
O relatório é configurado para A4, Arial Narrow 11 pt (com fallback Arial), sem cores na impressão e com regras para evitar a quebra interna de seções/tabelas sempre que o navegador conseguir respeitá-las.

Os dados do atendimento são salvos automaticamente no `localStorage` do navegador utilizado.
