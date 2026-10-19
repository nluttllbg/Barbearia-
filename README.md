# Barbearia - Brutus Barbershop

Website estático institucional de alta performance e elegância para a **Barbearia - Brutus Barbershop**, desenvolvido com foco em conversão para agendamentos via WhatsApp, design responsivo de alto padrão e compatibilidade nativa para hospedagem direta no **GitHub Pages** (ou qualquer servidor estático), sem depender de Node.js, compilação ou processos de build.

---

## 📋 Sumário do Projeto

- **Nome da Empresa**: Barbearia - Brutus Barbershop
- **Telefone / WhatsApp**: `+55 66 9987-6380` (string de configuração: `"556699876380"`)
- **Localização no Google Maps**: [https://maps.app.goo.gl/J3BLhVqvatXLP7iV7](https://maps.app.goo.gl/J3BLhVqvatXLP7iV7)
- **Idioma do Documento**: Português do Brasil (`pt-BR`)
- **Tecnologias Utilizadas**: HTML5 Semântico, CSS3 (Tailwind CSS via CDN), Vanilla JavaScript leve.

> ⚠️ **Nota Importante**: O número de telefone informado (`+55 66 9987-6380`) foi preservado com exatidão em todos os links e botões de chamada para ação (CTA). Antes da divulgação comercial pública, confirme o número final junto aos proprietários. As informações de endereço postal exato, horários de funcionamento específicos e tabela de preços detalhada permanecem configuradas para consulta direta pelo atendimento no WhatsApp.

---

## 📸 Fotografias Reais Utilizadas

Conforme as diretrizes obrigatórias do projeto, **nenhuma imagem foi gerada por IA e nenhuma foto de banco genérico (stock) foi utilizada**. Foram empregadas exclusivamente as fotografias reais fornecidas do espaço, equipe e produtos:

1. **Seção Hero (Destaque Principal)**:
   - *Foto*: Lounge e recepção com sofás Chesterfield escuros, balcão de atendimento e iluminação cênica.
   - *Finalidade*: Impacto visual imediato transmitindo sofisticação, conforto e exclusividade.
2. **Seção A Barbearia (Sobre nós)**:
   - *Foto*: Mestres barbeiros atuando em atendimento nas bancadas e espelhos iluminados.
   - *Finalidade*: Demonstrar profissionalismo, técnica artesanal e precisão em cada corte.
3. **Seção Galeria (6 Registros Autênticos)**:
   - *Foto 1*: Lounge de espera e recepção com sofás Chesterfield.
   - *Foto 2*: Café Brutus com cafeteira moderna, café espresso e iluminação neon da marca.
   - *Foto 3*: Estações de corte e atendimento com cadeiras de barbeiro profissionais.
   - *Foto 4*: Espaço de convivência e poltronas Chesterfield com bandeira decorativa.
   - *Foto 5*: Linha de cuidados masculinos com shampoos e tônicos esfoliantes capilares de uso profissional.
   - *Foto 6*: Produtos e finalizadores capilares premium da linha Keune 1922.

---

## 🎨 Fidelidade Visual ao Design Stitch

O site preserva com fidelidade absoluta:
- **Paleta de Cores**:
  - Dourado / Âmbar Principal (`#e9c176` / `primary`)
  - Fundo Preto Carvão Profundo (`#111317` / `background`)
  - Superfícies em Camadas (`#1e2024`, `#282a2e`, `#0c0e12`)
  - Destaques Secundários (`#e7c17a`, `#5c4304`)
  - Tipografia Clara de Alto Contraste (`#e2e2e8`, `#d1c5b4`)
- **Tipografia**:
  - Títulos e Destaques: `Outfit` (pesos 300, 400, 500, 600)
  - Corpo de Texto e Legendas: `Inter` (pesos 400, 500, 600)
  - Ícones: `Material Symbols Outlined`
- **Hierarquia de Seções**:
  1. *Cabeçalho Fixo* com navegação fluida e botão de agendamento rápido
  2. *Hero Section* com chamada de presença marcante e vitrine visual
  3. *A Barbearia* com diferenciais (atendimento personalizado, climatização e café)
  4. *Banner de Agendamento & Consultoria* com foco em contato direto
  5. *Galeria de Fotos* em grade responsiva com visualizador ampliado (*lightbox*)
  6. *Localização* com link oficial do Google Maps e visualização estilizada
  7. *Chamada Final (CTA)* reforçando agendamento
  8. *Rodapé Institucional* e botão flutuante permanente do WhatsApp

---

## 🚀 Como Publicar no GitHub Pages

Este projeto foi construído para ser **100% estático**. Você não precisa instalar Node.js, nem executar `npm install`, nem gerar compilações.

### Passo a passo para publicação:
1. Crie ou acesse o repositório no GitHub (ex: `usuario/brutus-barbershop`).
2. Faça o envio (upload ou push via Git) do arquivo `index.html` e deste `README.md` diretamente para o ramo principal (`main` ou `master`).
3. No repositório no GitHub, clique na aba **Settings** (Configurações).
4. No menu lateral esquerdo, selecione **Pages**.
5. Em **Build and deployment**:
   - **Source**: selecione `Deploy from a branch`.
   - **Branch**: selecione `main` (ou `master`) e a pasta raiz `/(root)`.
   - Clique em **Save**.
6. Aguarde cerca de 1 minuto: o GitHub Pages fornecerá a URL pública do seu site (ex: `https://usuario.github.io/brutus-barbershop/`).

---

## ✨ Recursos de Interatividade & Acessibilidade

- **Menu Mobile Adaptativo**: Abertura e fechamento com transição suave, suporte a fechamento ao clicar fora e atributos `aria-expanded` para acessibilidade.
- **Visualizador de Imagens (Lightbox)**: Ao clicar em qualquer fotografia da galeria ou vitrine, ela se expande em alta definição com descrição detalhada e suporte para fechar com a tecla `Esc` ou clique externo.
- **Rastreamento de Navegação no Scroll**: O menu destaca automaticamente a seção visível na tela conforme o visitante rola a página.
- **Link Direto do WhatsApp Formatado**: Mensagem pré-formatada em português:
  > *"Olá, equipe Brutus Barbershop! Vim pelo site e gostaria de agendar um horário. Quais são os serviços, valores e horários disponíveis?"*
- **SEO & OpenGraph Completos**: Tags OpenGraph (Facebook, WhatsApp, LinkedIn), Twitter Cards e Schema.org com JSON-LD para barbearias locais (`LocalBusiness/Barbershop`).
