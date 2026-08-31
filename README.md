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
- [x] Texto de apresentação — no site como veio, com um único ajuste de
      concordância ("às doenças de retina, **ao** envelhecimento das pálpebras")
- [x] Graduação: Faculdade de Medicina de Petrópolis
- [x] Residência médica: Instituto Suel Abujamra
- [x] Especializações: Oftalmologia, Retina e Cirurgia Plástica Ocular —
      Instituto Suel Abujamra, USP e UPO
- [ ] Títulos e associações (CBO, SBCPO, SBO…)
- [ ] Hospitais/centros cirúrgicos onde opera
- [ ] **Retina entra no topo do site?** O texto dela diz "especialista em
      cirurgia plástica ocular, retina e oftalmologia geral", mas o cabeçalho,
      o menu e as duas frentes falam só de oftalmologia e blefaroplastia,
      porque foram montados a partir da lista de procedimentos enviada antes.
      Decidir se retina vira uma terceira frente e entra na assinatura

### Contato
- [x] WhatsApp / telefone (11) 93045-5259 — os botões "Agendar" e a seção de
      contato abrem a conversa no WhatsApp com mensagem pronta
- [x] E-mail: inaraoftalmogia@gmail.com
- [x] Instagram: [@drainaracontin](https://www.instagram.com/drainaracontin/)
- [ ] **Conferir a grafia do e-mail.** Está no site exatamente como veio:
      `inaraoftalmogia@gmail.com`. Repare que falta o "lo" de oftalmo**lo**gia —
      pode ser o endereço real, mas se for engano o contato se perde calado

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
- [ ] Resposta sobre convênios na seção de dúvidas
- [ ] O bloco "Aparelhos do consultório" saiu a pedido do cliente. O parágrafo
      de Oftalmologia ainda cita tomografia de coerência óptica e microscopia;
      dizer se essa menção fica ou sai também

### Capa
- [ ] **Trocar a foto de capa.** O arquivo `Foto Site Entrada.HEIC` foi enviado,
      mas o macOS bloqueia o acesso do terminal à pasta Downloads (TCC), então
      não consegui ler nem converter. Basta mover o arquivo para dentro do
      projeto que eu sigo. Hoje a capa usa a `exames.jpg`, de 1280 px, esticada
      em tela cheia sob um véu escuro

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
