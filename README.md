# 🌳 Tree Viewer - Análise de Estrutura de Pastas

Visualizador interativo de estrutura de pastas geradas pelo comando `tree /A` do Windows.

## 🚀 Demo

Acesse: [https://seu-usuario.github.io/AnalisePastasJCG](https://seu-usuario.github.io/AnalisePastasJCG)

## 📋 Como Usar

### 1. Gerar arquivo de estrutura
Execute no Windows CMD ou PowerShell:

```cmd
tree /A > estrutura.txt
```

Ou com caminho completo:
```cmd
tree /A C:\MinhaPasta > estrutura.txt
```

### 2. Carregar no visualizador
- Arraste e solte o arquivo `.txt` na área indicada, ou
- Clique em "Carregar arquivo .txt" para selecionar

## ✨ Funcionalidades

- 📊 **Estatísticas por nível** - Veja quantas pastas existem em cada profundidade
- 🎨 **Cores por profundidade** - Identificação visual rápida do nível
- 🔍 **Busca em tempo real** - Encontre pastas rapidamente
- 📁 **Contagem de subpastas** - Badge mostrando subpastas diretas
- 📈 **Gráfico de distribuição** - Visualize a distribuição por nível
- 🌙 **Tema claro/escuro** - Alterne conforme preferência
- 🎯 **Expandir por nível** - Controle preciso da visualização
- 📥 **Drag & Drop** - Arraste arquivos diretamente
- 💾 **Exportar JSON** - Exporte a estrutura parseada

## 🛠️ Deploy no GitHub Pages

### Opção 1: Diretamente na branch main
1. Vá em **Settings** > **Pages**
2. Em **Source**, selecione **Deploy from a branch**
3. Escolha **main** e **/ (root)**
4. Clique em **Save**

### Opção 2: Usando GitHub Actions
1. Vá em **Settings** > **Pages**
2. Em **Source**, selecione **GitHub Actions**
3. O site será publicado automaticamente a cada push

## 📁 Estrutura do Projeto

```
AnalisePastasJCG/
├── index.html        # Página principal
├── tree-viewer.jsx   # Componente React
├── Pastas.txt        # Exemplo de estrutura
└── README.md         # Este arquivo
```

## 🔧 Tecnologias

- **React 18** - UI reativa
- **Tailwind CSS** - Estilização
- **Lucide Icons** - Ícones
- **Babel Standalone** - Transpilação JSX no browser

## 📝 Formato Suportado

O visualizador suporta o formato gerado pelo comando `tree /A` do Windows:

```
Folder PATH listing for volume DATA
Volume serial number is 561F-08A7
C:.
+---Pasta1
|   +---SubPasta1
|   |   \---SubSubPasta
|   \---SubPasta2
+---Pasta2
\---Pasta3
```

## 📄 Licença

MIT License - Use livremente!

---

Desenvolvido com ❤️ para análise de estruturas de pastas
