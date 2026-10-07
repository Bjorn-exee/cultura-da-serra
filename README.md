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

![Explorar com filtros](<img width="974" height="569" alt="01-explorar-filtros" src="https://github.com/user-attachments/assets/3e67661c-1a35-432a-a7a7-f091997ce47e" />
)

### Passaporte da Serra

![Passaporte da Serra](<img width="974" height="569" alt="03-passaporte" src="https://github.com/user-attachments/assets/8b491146-1885-4d15-89a0-015aca6445bd" />
)

### Roteiros culturais

![Roteiros culturais](<img width="974" height="569" alt="04-roteiros" src="https://github.com/user-attachments/assets/b4300d53-63b9-405b-ade4-8d7999e5d96e" />
)

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
- **Autor deste repositório:** Carlos [SOBRENOME] (Bjorn nas redes) · [LinkedIn]([carlos-eduardo-8507642b7](https://www.linkedin.com/in/carlos-eduardo-8507642b7 ))
- **Colegas de turma:** Emerson González, Gabriel Carvalho Bianchi e turma 3024/3028
- **Instrutor(a):** Gabriela Avila Zanatta
- **Mapas:** [Leaflet](https://leafletjs.com) e camadas da Esri (fonte: Esri, HERE, Garmin, FAO, NOAA e USGS)

## Aviso

Projeto educacional. O nome e a logo do SENAC pertencem ao SENAC.
