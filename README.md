# MiniAds - Sistema simples de Cartões de Anúncios para sites parceiros - em desenvolvimento

Projeto desenvolvido para criar e exibir anúncios em formato de cartão digital, que podem ser embutidos em sites parceiros via iframe ou script. Os anunciantes criam seus cartões (com nome, descrição, contato e imagem) e pagam para aparecer nos sites.

# Funcionalidades MVP

- Cartão visual responsivo e limpo (HTML + CSS);
- Formulário simples para criar anúncios (em desenvolvimento);
- Estrutura organizada para backend/API (futura implementação);
- Embutir anúncios em sites parceiros via iframe ou script;
- Pagamentos via Pix (manual, inicialmente);

# Estrutura de Pastas

/miniads/
- index.html (Página principal do cartão de anúncio)
- create.html (Página principal do formulário)
- style.css (Arquivo CSS com o estilo)
- images/ (Pasta para imagens usadas no projeto)
- logo.jpg (Exemplo de imagem para o cartão)
- api/ (Pasta para backend (futuro))
- createAd.js (API para criar anúncios)
- getAds.js (API para listar anúncios)
- registerPartner.js (API para registrar sites parceiros)
- recordImpression.js (API para registrar visualizações)
- confirmPayment.js (API para confirmar pagamentos)
- README.md (Documentação do projeto)

# Como rodar localmente

1. Clone ou baixe o projeto para sua máquina.
2. Certifique-se que os arquivos .html e .css estejam na mesma pasta.
3. Coloque as imagens na pasta images/ (ex: images/meu-logo.jpg).
4. Abra os arquivos .html em seu navegador (ex: Google Chrome, Firefox).
5. Você verá o cartão de anúncio e formulário de envio estilizado.

# Tecnologias que serão usadas

- HTML5
- CSS3
- JavaScript (para futuras implementações)
- Pagamentos via Pix (planejado)

# Próximos passos

- Implementar backend para salvar e listar anúncios (API REST)
- Sistema de pagamentos integrado e validação automática
- Gerar código para parceiros incorporarem os anúncios
- Dashboard para parceiros visualizarem ganhos e estatísticas

# Contribuindo

Pull requests são bem-vindos!  
Para grandes mudanças, por favor abra uma issue antes para discutir o que deseja mudar.

# Licença

MIT License © 2025 Marcelo M. Silva

# Contato

Para dúvidas ou sugestões, entre em contato.