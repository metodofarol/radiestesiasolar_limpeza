# Radiestesia SOLAR — formulário

Aplicação estática em HTML/CSS/JavaScript. Não exige servidor nem processo de build.

## Publicar no GitHub Pages
1. Abra o repositório desejado no GitHub.
2. Envie `index.html` e `README.md` para a raiz do repositório.
3. Em **Settings > Pages**, em **Build and deployment**, escolha **Deploy from a branch**.
4. Selecione a branch `main` e a pasta `/ (root)` e salve.

## Estrutura
```text
index.html
README.md
```

Os bancos de dados e a lógica do formulário permanecem incorporados no `index.html`.

## Organização do formulário
Os três protocolos aparecem como títulos de nível principal. Dentro de cada protocolo, os eixos e subeixos são apresentados em blocos expansíveis independentes, com fundos suaves diferentes para facilitar a leitura e reduzir a extensão visual da página.

No Protocolo 3 — Rodrigo Bittencourt, **Causas**, **Sentimentos**, **Tratamentos energéticos** e **Leitura Oracular Integrada** pertencem ao mesmo protocolo. Cada tratamento e cada eixo oracular aparece como bloco expansível próprio.

## Relatório
O relatório permanece configurado para A4, Arial Narrow 11 pt (com fallback Arial), texto preto sobre fundo branco e regras para evitar a quebra interna de seções, tabelas, linhas e títulos sempre que o navegador conseguir respeitá-las.

Os dados do atendimento são salvos automaticamente no `localStorage` do navegador utilizado.
