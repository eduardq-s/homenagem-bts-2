# Homenagem ao BTS

Uma homenagem bonita e interativa ao grupo BTS, com diálogo personalizado do Eduardo, quiz interativo e cards dos sete membros com imagens.

## Como Hospedar no GitHub Pages

### Passo 1: Criar um Repositório no GitHub

1. Acesse [github.com](https://github.com) e faça login
2. Clique em "New" para criar um novo repositório
3. Nomeie como `seu-usuario.github.io` (substitua `seu-usuario` pelo seu usuário do GitHub)
4. Deixe como "Public"
5. Clique em "Create repository"

### Passo 2: Fazer Upload dos Arquivos

Você tem duas opções:

#### Opção A: Via Git (Recomendado)

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/seu-usuario.github.io.git

# Entre na pasta
cd seu-usuario.github.io

# Copie todos os arquivos da homenagem para esta pasta

# Adicione os arquivos ao Git
git add .

# Faça um commit
git commit -m "Adicionar homenagem ao BTS"

# Envie para o GitHub
git push origin main
```

#### Opção B: Via Interface do GitHub

1. Abra seu repositório no GitHub
2. Clique em "Add file" → "Upload files"
3. Arraste e solte todos os arquivos desta pasta
4. Clique em "Commit changes"

### Passo 3: Acessar o Site

Após alguns segundos, acesse: `https://seu-usuario.github.io`

Pronto! Sua homenagem ao BTS está no ar! 🎉

## Estrutura dos Arquivos

- `index.html` - Página principal (contém todo o HTML, CSS e JavaScript compilado)
- `assets/` - Arquivos CSS e JavaScript otimizados
- `members/` - Imagens dos sete membros do BTS

## Personalizações

Para fazer alterações na homenagem, você precisará:

1. Ter o código-fonte original do projeto React
2. Fazer as mudanças
3. Compilar novamente com `pnpm build`
4. Fazer upload dos novos arquivos para o GitHub

## Suporte

Se tiver dúvidas sobre como hospedar no GitHub Pages, consulte a [documentação oficial](https://docs.github.com/en/pages).

---

**Criado com muito amor por Eduardo** 💜
