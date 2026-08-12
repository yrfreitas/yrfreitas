# Giovanni Kalebe

Sócio da **Porto Tec Assistência Técnica**, em São Paulo — assistência autorizada
Panasonic. Construo software para resolver os problemas da própria operação:
os sistemas que estão aqui rodam em produção e são usados todos os dias pela
equipe.

Estudo **Análise e Desenvolvimento de Sistemas** e **Ciências Contábeis**, e sou
formado em Marketing. Essa mistura acabou virando meu jeito de trabalhar: eu
conheço a operação por dentro, entendo o custo de cada decisão e construo com
isso em mente.

---

### O que estou construindo

**[Portotec Roteiros](https://github.com/yrfreitas/portote_roteiros)** · Python · Flask · PostgreSQL

Sistema de roteirização e gestão de atendimentos técnicos, em produção.

Um técnico atende de 6 a 10 clientes por dia espalhados pela cidade — a ordem
das visitas muda a quilometragem, o tempo em trânsito e quantos atendimentos
cabem no dia. O sistema monta a rota, acompanha a execução em campo e fecha o
ciclo administrativo depois.

- Otimização de rota com Nearest Neighbor e refinamento 2-opt
- PWA instalável, com link individual para cada técnico
- Notificações push quando uma rota é atribuída
- Conciliação automática dos atendimentos com a planilha de compras
- Leitura das peças direto do XML da NF-e recebida por e-mail

---

### Como eu penso sobre software

O que me interessa não é a tecnologia mais nova, é a decisão certa para o
problema. Algumas que tomei nesse projeto:

- O app funciona offline, mas **nunca** entrega dado de rota vindo de cache —
  mostrar rota velha para quem está na rua é pior que não funcionar
- O link do técnico não tem senha, porque exigir login de quem está de moto
  entre um atendimento e outro cria atrito diário para proteger contra um
  cenário que não é o real
- Frontend sem framework: seis telas e nenhum estado compartilhado complexo
  não pagam o custo de build e manutenção

---

### Stack

`Python` `Flask` `PostgreSQL` `SQLite` `JavaScript` `PWA / Service Workers`
`Google Sheets API` `Web Push` `IMAP` `Leaflet` `Railway`

---

### Contato

[![Email](https://img.shields.io/badge/email-giovannikalebe690%40gmail.com-informational?style=flat-square)](mailto:giovannikalebe690@gmail.com)
