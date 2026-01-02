# 📄 FitBro - Documentos Legais

Este diretório contém os documentos legais do FitBro prontos para hospedagem no GitHub Pages.

## 📁 Estrutura

```
documentos/
├── privacy-policy/
│   ├── index.html (PT)
│   └── index-en.html (EN)
└── terms-of-service/
    ├── index.html (PT)
    └── index-en.html (EN)
```

## 🚀 Como hospedar no GitHub Pages

### Passo 1: Criar repositório

1. Acesse: https://github.com/new
2. Nome sugerido: `fitbro-legal`
3. Marque: ✅ Public
4. Marque: ✅ Add a README file
5. Clique em **Create repository**

### Passo 2: Upload dos arquivos

**Opção A - Via Interface Web:**
1. No repositório, clique em **Add file** > **Upload files**
2. Arraste a pasta `documentos` completa
3. Commit message: "Adicionar documentos legais"
4. Clique em **Commit changes**

**Opção B - Via Git (Terminal):**
```bash
# Clone o repositório
git clone https://github.com/SEU-USUARIO/fitbro-legal.git
cd fitbro-legal

# Copie a pasta documentos
cp -r /caminho/para/fitbro-app/documentos/* .

# Commit e push
git add .
git commit -m "Adicionar documentos legais"
git push origin main
```

### Passo 3: Habilitar GitHub Pages

1. No repositório, vá em **Settings**
2. No menu lateral, clique em **Pages**
3. Em **Source**, selecione:
   - Branch: `main`
   - Folder: `/ (root)`
4. Clique em **Save**
5. Aguarde 2-3 minutos

### Passo 4: Acessar os documentos

Suas URLs serão:

**Política de Privacidade:**
- 🇧🇷 PT: `https://SEU-USUARIO.github.io/fitbro-legal/privacy-policy/`
- 🇺🇸 EN: `https://SEU-USUARIO.github.io/fitbro-legal/privacy-policy/index-en.html`

**Termos de Uso:**
- 🇧🇷 PT: `https://SEU-USUARIO.github.io/fitbro-legal/terms-of-service/`
- 🇺🇸 EN: `https://SEU-USUARIO.github.io/fitbro-legal/terms-of-service/index-en.html`

## 📝 Atualizar app.json

Após hospedar, atualize o `app.json` do FitBro:

```json
{
  "expo": {
    "privacy": "https://SEU-USUARIO.github.io/fitbro-legal/privacy-policy/",
    // ... resto da configuração
  }
}
```

## ✅ Checklist

- [ ] Repositório GitHub criado
- [ ] Arquivos HTML enviados
- [ ] GitHub Pages habilitado
- [ ] URLs testadas e funcionando
- [ ] app.json atualizado com URL de privacidade
- [ ] Pasta `docs/` do projeto pode ser removida ✅

## 🎨 Características dos HTMLs

✅ **Design responsivo** - funciona em mobile e desktop  
✅ **Profissional** - cores e layout modernos  
✅ **Acessível** - estrutura semântica correta  
✅ **Multi-idioma** - switcher entre PT e EN  
✅ **SEO otimizado** - meta tags apropriadas  
✅ **Links internos** - navegação entre documentos  

## 📊 Progresso Atualizado

Com isso pronto, você salta de **47.5% → 52.5%**! 🎉

## 🆘 Problemas Comuns

**GitHub Pages não aparece:**
- Aguarde 5-10 minutos após ativar
- Verifique se o repositório está público
- Limpe o cache do navegador

**404 Error:**
- Certifique-se que os arquivos estão na raiz ou na pasta correta
- Verifique se os nomes dos arquivos estão corretos (case-sensitive)

**Links quebrados:**
- Use caminhos relativos: `../privacy-policy/index.html`
- Teste todas as URLs após deploy

## 📧 Suporte

Se tiver problemas, entre em contato: contato@fitbroapp.com

---

✨ **Pronto para produção!**
