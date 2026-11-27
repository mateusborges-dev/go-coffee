# GO COFFEE

Site de uma página da cafeteria **GO COFFEE** — Av. Juscelino Kubitscheck, 2412, Centro, Luís Eduardo Magalhães – BA.

## O que tem

- **Hero** com o título de chocolate animado (letras caem derretendo) e o frappé sendo montado conforme o scroll.
- **Nossos favoritos**: carrossel com os 10 frappés da casa (cards caem do céu; no hover o copo gira).
- **Cardápio completo** em abas, com os preços do cardápio de março/2025.
- **Horários** com aviso de aberto/fechado no horário da Bahia, mapa e rota.
- **WhatsApp** e telefone para contato.

É HTML, CSS e JavaScript puros, num único `index.html`, sem build.

## Como ver

As imagens são carregadas da pasta `assets/`, então abra por um servidor local (não pela prévia de arquivo):

```powershell
py -m http.server 5173
```

Depois acesse http://localhost:5173/.

## Estrutura

```
index.html          página inteira (estilos e scripts inline)
assets/img/         fotos do cardápio e dos frappés favoritos
assets/frappe/      120 quadros do frappé sendo montado (animação do hero)
assets/titulo/      letras do título de chocolate
assets/titulo.json  posição de cada letra
```
