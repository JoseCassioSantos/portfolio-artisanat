# Portfolio Artisanat - Sua Irmã

## Visão geral
Um site simples e gratuito para sua irmã expor seus trabalhos de artisanato e receber solicitações de clientes pelo WhatsApp.

## Funcionalidades
- **Seleção de categorias**: Crochet, Tricô, Bordado, Pintura/Artes plásticas, Outro
- **Geração de link WhatsApp**: Ao selecionar uma categoria e informar o número, gera um link que abre o WhatsApp com uma mensagem predefinida já pronta
- **Design iluminado**: Fundo branco com tons bege e amarelo, mais fácil de ler
- **Cards com imagens exemplo**: Exemplos visuais por categoria para inspirar clientes
- **Cores da marca**: amarelo #FFD600, bege #F5F0E8, marrom #8B5A2B

## Como usar

1. **Abra o site**: Basta abrir o arquivo `index.html` em qualquer navegador (Chrome, Firefox, Edge)

2. **Selecione o tipo de trabalho**: Use o dropdown para escolher:
   - Crochet / Crochê
   - Knitting / Tricô
   - Bordado
   - Pintura / Artes plásticas
   - Outro

3. **Informe o WhatsApp**: Digite o número com DDD (ex: `5511987654321`)

4. **Clique no link gerado**: Um link aparecerá abaixo que, ao ser clicado, abre o WhatsApp com a mensagem:

   > "Olá! Gostaria de solicitar um trabalho de [categoria] personalizado."

5. **Envie para clientes**: Compartilhe o link via redes sociais, e-mail ou impresso em papéis

### Dica: Adicione fotos dos seus trabalhos na categoria escolhida para atrair mais clientes!

## Customização

### Alterar categorias
Edite o objeto `categories` no JavaScript (linhas 199-224) para adicionar mais tipos de artisanato ou modificar os nomes.

### Alterar mensagem padrão
Modifique a variável `defaultMessage` em cada categoria ou a função `generateLink()` no JavaScript.

### Mudar cores
As cores estão definidas nas variáveis CSS no topo do arquivo (seção `:root`). Atualize os códigos hexadecimais se desejar.

### Mudar número de WhatsApp padrão
Altere o placeholder do input: `placeholder="Ex: 5511987654321"`

## Deploy (opcional)

### GitHub Pages (gratuito)
1. Crie um repositório no GitHub
2. Faça upload dos arquivos desta pasta
3. Vá em Settings > Pages
4. Selecione a branch `main` e pasta `/ (root)`
5. O site ficará disponível em `seu-usuario.github.io/nome-do-repositorio`

### Netlify (gratuito)
1. Arraste a pasta para https://app.netlify.com/drop
2. O site ficará online instantaneamente

## Suporte
Para dúvidas ou modificações, consulte a seção de código ou entre em contato.