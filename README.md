# Gustha Tech

Site institucional estático, em português, para divulgar os serviços de elétrica, automação industrial, segurança eletrônica e redes da Gustha Tech.

## Abrir no VS Code

1. Extraia o ZIP e abra a pasta `gusthatech` no VS Code.
2. Abra `dist/index.html` e clique com o botão direito no arquivo.
3. Selecione **Open with Live Server**. A página abre com os estilos, as imagens e o JavaScript, usando os caminhos relativos ao arquivo HTML.

## Arquivos
- `dist/index.html`: conteúdo, estrutura e metadados.
- `dist/styles.css`: identidade visual, layouts responsivos e animações.
- `dist/app.js`: abas de serviços, menu mobile, galeria, perguntas frequentes e formulário para WhatsApp.
- `dist/assets/`: fotos e logotipo recuperados da apresentação original, com fontes locais.
- `vercel.json`: configuração de publicação estática na Vercel.

Não há etapa de compilação, banco de dados ou dependência de execução. O diretório publicado é `dist`.

## Contatos verificados na apresentação original
WhatsApp: +55 11 99495-0026
Instagram: https://www.instagram.com/gustha.tech/
Fonte: https://www.gusthatech.com.br/ e suas páginas internas, consultadas em 28/10/2026.

O formulário prepara uma mensagem para o WhatsApp. O visitante revisa e envia a mensagem no WhatsApp; o site não a envia automaticamente e não armazena os dados do formulário.

A região de atendimento, os horários, as certificações e os preços não foram informados na fonte. O site orienta confirmar a disponibilidade pelo WhatsApp. Não foram criados depoimentos ou estatísticas.

## Alterar o contato
O número está em links no HTML e em `dist/app.js`. Atualize ambos quando necessário. O seletor de serviços é conectado aos links pelo atributo `data-service`.

## Acessibilidade e movimento
Abas navegáveis por teclado, foco visível, modal com fechamento por Escape, labels no formulário e respeito a `prefers-reduced-motion`.

## Publicação
Projeto `gusthatech` da equipe VITAIS na Vercel. Não foi alterado o DNS do domínio existente.

Site publicado: https://gusthatech.vercel.app/
Verificação: publicação READY na Vercel, carregamento público confirmado, menu em tela de 390px, abas, FAQ, galeria e formulário com mensagem preparada para WhatsApp testados.

## Identidade visual — versão 3
A versão atual retoma a marca original: engrenagem, G central e raio. O fundo branco foi removido; o azul foi suavizado para um tom dessaturado, com cinza fosco e branco suave. Aplicada ao cabeçalho, rodapé e favicon. O original da edição está preservado em `branding/gustha-original-adaptado-v3.png`; a página carrega uma cópia WebP otimizada com transparência. As versões anteriores estão preservadas em `branding/`.
