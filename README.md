# Cultura da Serra

**Um mapa cultural vivo da Serra Gaúcha.** Descubra, visite e registre a cultura de Gramado, Canela e Nova Petrópolis.

**[Ver o site no ar](https://culturadaserra.netlify.app)** · [Assistir ao vídeo de demonstração](docs/cultura-da-serra.mp4)

![Demonstração do Cultura da Serra](docs/demo.gif)

## Sobre o projeto

O Cultura da Serra reúne lugares, histórias, patrimônio e experiências culturais de Gramado, Canela e Nova Petrópolis em um mapa interativo. A ideia é descobrir a cultura da Serra, ver onde ela está, entender o que cada lugar representa e registrar o que você já viveu.

O projeto foi desenvolvido, em poucos dias, pela turma do curso profissionalizante de Jovem Aprendiz do SENAC Gramado.

## Funcionalidades

- **Mapa interativo** com os lugares e a sua posição ("Você está aqui").
- **Filtros** por cidade (Gramado, Canela e Nova Petrópolis), por categoria (Patrimônio, Museus & Memória, Arte & Cultura, Cultura & Natureza e Tradições) e filtros rápidos (Aberto agora, Gratuito, Perto de mim e Ainda não visitei).
- **Para você hoje:** sugestões de lugares para visitar.
- **Página de cada lugar:** fotos, história, distância, se está aberto agora, se é gratuito, indicação de acessibilidade e atalho para abrir no Google Maps.
- **Passaporte da Serra:** registre suas visitas, ganhe carimbos e conquistas (como "Primeira Descoberta") e acompanhe quantos dos lugares cadastrados você já descobriu (hoje são 31).
- **Roteiros culturais:** monte um roteiro de acordo com as cidades, os interesses, o tempo disponível (meio dia, um dia ou fim de semana) e o ritmo que você prefere.
- **Sem senha e sem cadastro obrigatório:** dá para explorar sem criar perfil, e os dados do passaporte ficam salvos apenas no navegador.

## Telas

### Explorar com filtros

![Explorar com filtros](docs/01-explorar-filtros.png)

### Detalhes de um lugar

![Detalhes de um lugar](docs/02-detalhe-do-lugar.png)

### Passaporte da Serra

![Passaporte da Serra](docs/03-passaporte.png)

### Roteiros culturais

![Roteiros culturais](docs/04-roteiros.png)

## Tecnologias

- HTML, CSS e JavaScript
- [Leaflet](https://leafletjs.com) para o mapa interativo, com camadas da Esri
- [Netlify](https://www.netlify.com) para a hospedagem: o site fica no ar 24 horas por dia

## Como rodar no seu computador

```bash
git clone https://github.com/SEU-USUARIO/cultura-da-serra.git
cd cultura-da-serra
python -m http.server 8000
```

Depois, abra http://localhost:8000 no navegador. Usar um servidor local, em vez de abrir o `index.html` direto, evita problemas com alguns recursos do navegador.

## O que eu aprendi

- Como é, na prática, colocar um site no ar e deixá-lo funcionando 24 horas por dia.
- Como gerenciar o tempo e as demandas de um projeto feito em poucos dias.
- Ampliei meus conhecimentos em programação.

## Equipe e créditos

- **Desenvolvimento:** turma do curso profissionalizante de Jovem Aprendiz do SENAC Gramado.
- **Autor deste repositório:** Carlos [SOBRENOME] (Bjorn nas redes) · [LinkedIn](LINK-DO-SEU-LINKEDIN)
- **Colegas de turma:** [NOMES, com o ok de cada um]
- **Instrutor(a):** [NOME, com o ok]
- **Mapas:** [Leaflet](https://leafletjs.com) e camadas da Esri (fonte: Esri, HERE, Garmin, FAO, NOAA e USGS)
- **Fotos e dados dos lugares:** [FONTES E CRÉDITOS]

## Aviso

Projeto educacional. O nome e a logo do SENAC pertencem ao SENAC.
