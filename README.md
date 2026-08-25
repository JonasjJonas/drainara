# Site — Dra. Inara Contin Rassi

Oftalmologia e blefaroplastia. Site institucional de página única, em HTML,
CSS e JavaScript puros, sem build: o que está no repositório é exatamente o
que vai pro ar.

    index.html              a página inteira
    assets/css/site.css     toda a folha de estilo
    assets/js/site.js       menu, lacunas e entrada em cena
    assets/img/             fotos e arte (ver assets/img/LEIA-ME.txt)

Publicado no GitHub Pages pelo workflow `.github/workflows/deploy.yml`, que
dispara a cada push na branch `main`.

Para ver localmente:

    python3 -m http.server 8123

e abrir <http://127.0.0.1:8123>.

---

## O que ainda falta

Cada item abaixo aparece na página como uma etiqueta tracejada **◇ FALTA**, no
lugar exato onde o conteúdo entra. Elas somem sozinhas quando o dado é
preenchido — não precisa caçar no código.

### Dados de registro
- [x] CRM 136.284
- [x] RQE 77580
- [ ] Confirmar a **UF do CRM** — a publicidade médica exige o estado junto
      do número, e eu não quis chutar

### Sobre ela
- [ ] Parágrafo de apresentação, escrito na voz dela
- [ ] Graduação — faculdade e ano
- [ ] Residência em oftalmologia — serviço e período
- [ ] Especialização em oculoplástica — fellowship/curso, instituição e ano
- [ ] Títulos e associações (CBO, SBCPO, SBO…)
- [ ] Hospitais/centros cirúrgicos onde opera

### Contato
- [x] WhatsApp / telefone (11) 93045-5259 — os botões "Agendar" e a seção de
      contato abrem a conversa no WhatsApp com mensagem pronta
- [ ] E-mail
- [ ] Instagram

### Consultório
- [x] Endereço: Rua Maria Figueiredo, 595 — conjunto 83, Paraíso, São Paulo/SP
- [x] Mapa do Google incorporado na página
- [ ] Conferir o **CEP 04002-003** — veio da geolocalização do Google, não de você
- [ ] Dias e horários de atendimento — a lista de informações práticas
      (convênios, estacionamento, acessibilidade, metrô) saiu da página a
      pedido do cliente. Quando esses dados chegarem, vale reintroduzir só
      os que estiverem preenchidos

### Conteúdo clínico
- [x] Lista de procedimentos — agora é exatamente a que você mandou
- [ ] "Microscopia": especular ou confocal?
- [ ] Completar a lista de aparelhos (o "entre outros")
- [ ] Resposta sobre convênios na seção de dúvidas

### Capa
- [ ] **Foto de capa em alta resolução.** Hoje a capa usa a `exames.jpg`, de
      1280 px, esticada em tela cheia sob um véu escuro. Funciona, mas fica
      macia em tela grande. Ideal: uma foto larga (2400 px+) da sala de
      espera ou da recepção

### Fotos
- [x] Retrato da Dra. Inara na capa (IMG_4739)
- [x] Foto dela no consultório, seção "Sobre" (IMG_4702)
- [x] Galeria: sala de exames vazia (lote antigo) e sala de imagem com ela
      (IMG_4796)
- [x] Ilustrações removidas a pedido dela (visual mais limpo)
- [ ] `exames.jpg`, `lounge.jpg` e `recepcao.jpg` são as versões reduzidas que
      vieram pelo chat. A da sala de exames é a maior da página e a de menor
      resolução: uma tomada nova da sala vazia resolveria (nas 136 fotos da
      sessão não há nenhuma sem a Dra. Inara)
- [ ] Decidir se a foto da recepção pode mostrar a placa "Lavezzo & Takigami"
      — hoje ela está cortada fora do quadro

### Antes de publicar de verdade
- [ ] Remover a linha `<meta name="robots" content="noindex, nofollow">` do
      `index.html` — enquanto ela estiver lá, o site não é indexado pelo Google
- [ ] Revisar o texto do rodapé sobre publicidade médica. Blefaroplastia tem
      componente estético, e as normas do CFM são rígidas: nada de antes e
      depois, depoimento de paciente ou promessa de resultado
