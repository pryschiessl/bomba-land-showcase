# Bomba Land

Bomba Land é uma experiência digital interativa da Bomba Trends. O primeiro distrito reimagina a região da Berrini e da Faria Lima, em São Paulo, como uma cidade navegável de música, arte e tecnologia.

- [Mapa da Bomba Land](https://bomba-land.pages.dev/)
- [Rich House 24H](https://bomba-land.pages.dev/rich-house-24h/)
- [Tech Polis v0.6.11](https://bomba-land.pages.dev/tech-polis/)
- [Tech Polis Showcase](https://github.com/pryschiessl/tech-polis-showcase)

A edição de outubro de 2026 integra o mapa, a Rich House e a Tech Polis. Na Rich House, o visitante encontra DJ Deck, Record Wall e BOMBAR. Na Tech Polis, pode explorar o Jardim, consultar o UNKNOWN TAROT e visitar a Leo’s House. A Teachers House aparece no mapa como espaço futuro.

## Arquitetura e publicação

O mapa usa React e TypeScript com Vite. A Rich House e a Tech Polis têm entradas HTML próprias e usam JavaScript no navegador. A edição editorial foi publicada como pacote estático validado, por envio manual ao Cloudflare Pages. A demonstração publicada reúne a distribuição completa.

Esta documentação descreve a edição de outubro. O repositório público histórico da Bomba Land ainda contém código e assets da versão de agosto. A árvore desse repositório e o pacote editorial em produção correspondem a versões diferentes.

O pacote editorial foi conferido por SHA-256 e restaurado localmente. A geração de todos os bundles a partir das fontes ainda não foi demonstrada. Esta apresentação documental não inclui o pacote necessário para executar a experiência completa.

## UX e QA

Em homologação local, foram testados desktop, tablet e mobile. Os cenários cobriram navegação, foco e teclado, hotspots, retorno ao mapa, capas, créditos, Tarot e posicionamento dos painéis da Rich House. Os destinos de links externos foram conferidos sem testar reprodução em serviços terceiros. São verificações funcionais e de responsividade, com cobertura parcial de acessibilidade.

## Créditos

Bomba Trends responde pela direção editorial e pela aprovação final. As fichas nas três rotas da demonstração registram as contribuições específicas de cada experiência e são a referência para os créditos completos.

Na Leo’s House, a concepção original e a colaboração no design da experiência são creditadas ao ChatGPT, chamado de “Leo da Bombi” no processo criativo. O protótipo foi desenvolvido com ChatGPT em colaboração com a Bomba Trends. A integração técnica e a publicação são creditadas ao OpenAI Codex, chamado de “Manodex” no processo criativo. As atribuições de ferramentas não indicam patrocínio, parceria ou endosso de seus fornecedores.
