# 🌐 Deploy do Site - Abrigo Anjos Fiéis

## 📝 Passo a Passo para Hospedar Gratuitamente

### 🚀 Opção 1: GitHub Pages (Recomendada)

#### 1. Preparar o Repositório
```bash
# Se ainda não tem Git configurado
git init
git add .
git commit -m "Site responsivo da ONG Abrigo Anjos Fiéis"
```

#### 2. Criar Repositório no GitHub
1. Acesse [github.com](https://github.com)
2. Clique em "New repository"
3. Nome: `abrigo-anjos-fieis` ou `AbrigoAnjosFieis`
4. Deixe público (gratuito)
5. Clique "Create repository"

#### 3. Fazer Upload
```bash
git remote add origin https://github.com/SEU-USUARIO/abrigo-anjos-fieis.git
git branch -M main
git push -u origin main
```

#### 4. Ativar GitHub Pages
1. No GitHub, vá em Settings → Pages
2. Source: "Deploy from a branch"
3. Branch: `main` / `(root)`
4. Clique "Save"
5. Aguarde alguns minutos
6. Site estará em: `https://SEU-USUARIO.github.io/abrigo-anjos-fieis`

### 🌟 Opção 2: Netlify (Alternativa)

#### Deploy Direto
1. Acesse [netlify.com](https://netlify.com)
2. Faça login com GitHub
3. "New site from Git"
4. Selecione seu repositório
5. Deploy automático!

#### Ou Deploy por Drag & Drop
1. Zipar a pasta do projeto
2. Arrastar para netlify.com/drop
3. Site no ar instantaneamente!

### 🔗 Opção 3: Vercel

1. Acesse [vercel.com](https://vercel.com)
2. Login com GitHub
3. "Import Project"
4. Selecione o repositório
5. Deploy automático!

## 🏷️ Domínio Personalizado (Opcional)

### Gratuito:
- `abrigo-anjos-fieis.github.io`
- `abrigo-anjos-fieis.netlify.app`
- `abrigo-anjos-fieis.vercel.app`

### Personalizado (Pago):
- `abrigoanjosfieis.org` (~R$ 50/ano)
- `abrigoanjosfieis.com.br` (~R$ 40/ano)

## 📊 Comparação das Opções

| Plataforma | Gratuito | Fácil | Performance | Domínio |
|------------|----------|-------|-------------|---------|
| GitHub Pages | ✅ | ⭐⭐⭐ | ⭐⭐⭐ | .github.io |
| Netlify | ✅ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | .netlify.app |
| Vercel | ✅ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | .vercel.app |

## 🎯 **RECOMENDAÇÃO FINAL**

Para a ONG, sugiro:
1. **GitHub Pages** - Simples e confiável
2. **Netlify** - Se quiser funcionalidades extras
3. **Vercel** - Se quiser máxima performance

## 📱 Funcionalidades Após Deploy

✅ Site responsivo funcionando  
✅ Acesso mobile/tablet/desktop  
✅ HTTPS automático  
✅ CDN global (carregamento rápido)  
✅ Atualizações automáticas (se conectar ao Git)  

## 🔄 Atualizações Futuras

Depois do deploy inicial:
1. Faça alterações nos arquivos
2. `git add .`
3. `git commit -m "Atualização"`
4. `git push`
5. Site atualiza automaticamente!

---

**💡 Dica:** Comece com GitHub Pages. É a opção mais simples e confiável para ONGs!
