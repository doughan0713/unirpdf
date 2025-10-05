# 📄 Unificador de PDF

![Version](https://img.shields.io/badge/version-1.0.0-orange)
![License](https://img.shields.io/badge/license-MIT-blue)
![LGPD](https://img.shields.io/badge/LGPD-compliant-green)

Uma aplicação web moderna e segura para unificar múltiplos arquivos PDF em um único documento, processando tudo localmente no navegador do usuário.

## 🌟 Características

- ✨ **Interface Moderna**: Design limpo e intuitivo com feedback visual
- 🔒 **100% Seguro**: Processamento local no navegador, sem upload para servidores
- 📱 **Responsivo**: Funciona perfeitamente em desktop, tablet e mobile
- ⚡ **Rápido**: Processamento instantâneo sem latência de rede
- 🇧🇷 **LGPD Compliant**: Totalmente em conformidade com a Lei Geral de Proteção de Dados
- 🎯 **Sem Instalação**: Funciona diretamente no navegador, não requer downloads
- 🔄 **Drag & Drop**: Suporte para arrastar e soltar arquivos
- 📊 **Preview em Tempo Real**: Visualização dos arquivos selecionados

## 🚀 Demonstração

A aplicação possui um fluxo de trabalho em 3 etapas simples:

1. **Etapa 1**: Selecione o primeiro arquivo PDF
2. **Etapa 2**: Selecione o segundo arquivo PDF
3. **Etapa 3**: Defina o nome e gere o PDF unificado

## 📋 Pré-requisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- JavaScript habilitado
- Conexão com internet (apenas para carregar bibliotecas CDN)

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilização moderna com animações
- **JavaScript (jQuery)**: Manipulação do DOM e eventos
- **Bootstrap 5.3.3**: Framework CSS responsivo
- **pdf-lib**: Biblioteca para manipulação de PDFs
- **SweetAlert2**: Alertas e modais elegantes
- **Lucide Icons**: Ícones SVG modernos
- **Google Fonts (Inter)**: Tipografia profissional

## 📁 Estrutura do Projeto

```
unificador-pdf/
│
├── index.html          # Arquivo principal HTML
├── styles.css          # Estilos personalizados
└── README.md          # Documentação (este arquivo)
```

## 💻 Instalação e Uso

### Opção 1: Clone o Repositório

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/unificador-pdf.git

# Entre na pasta do projeto
cd unificador-pdf

# Abra o arquivo index.html no seu navegador
```

### Opção 2: Download Manual

1. Baixe os arquivos `index.html` e `styles.css`
2. Coloque ambos na mesma pasta
3. Abra o arquivo `index.html` no seu navegador

### Opção 3: Hospedagem Web

Faça upload dos arquivos para qualquer servidor web ou plataforma de hospedagem:
- GitHub Pages
- Netlify
- Vercel
- Servidor Apache/Nginx

## 📖 Como Usar

1. **Acesse a aplicação** abrindo o arquivo `index.html` no navegador

2. **Etapa 1 - Adicionar PDF 1**:
   - Clique no campo de upload ou arraste o primeiro arquivo PDF
   - Aguarde a confirmação visual
   - Clique em "Próxima Etapa"

3. **Etapa 2 - Adicionar PDF 2**:
   - Clique no campo de upload ou arraste o segundo arquivo PDF
   - Aguarde a confirmação visual
   - Clique em "Próxima Etapa"

4. **Etapa 3 - Gerar PDF**:
   - Revise os arquivos selecionados
   - (Opcional) Altere o nome do arquivo final
   - Clique em "Unificar e Baixar PDF"
   - O arquivo será baixado automaticamente

## 🎨 Personalização

### Cores do Tema

Edite as seguintes variáveis no arquivo `styles.css`:

```css
/* Cor principal */
background: #ff5500;  /* Laranja principal */

/* Cor de destaque */
background: linear-gradient(135deg, #ff5500 0%, #ff6600 100%);

/* Ajuste as cores conforme necessário */
```

### Tamanho Máximo de Arquivo

Por padrão, o limite é de 50MB. Para alterar, modifique o texto informativo no HTML:

```html
<p class="muted-sm mb-0">Primeiro arquivo PDF (Máx. 50MB)</p>
```

## 🔐 Segurança e Privacidade

- ✅ **Processamento Local**: Todos os arquivos são processados no navegador
- ✅ **Sem Uploads**: Nenhum dado é enviado para servidores externos
- ✅ **Sem Armazenamento**: Arquivos não são salvos ou armazenados
- ✅ **LGPD Compliant**: Em conformidade com a legislação brasileira
- ✅ **Open Source**: Código transparente e auditável

## 🐛 Solução de Problemas

### O PDF não está sendo gerado

- Verifique se ambos os arquivos são PDFs válidos
- Certifique-se de que os arquivos não estão corrompidos
- Tente com arquivos menores (< 10MB)

### Erro ao carregar a página

- Verifique sua conexão com a internet (necessária para CDNs)
- Limpe o cache do navegador
- Tente outro navegador

### Interface não está responsiva

- Atualize seu navegador para a versão mais recente
- Verifique se o arquivo `styles.css` está na mesma pasta

## 🤝 Contribuindo

Contribuições são bem-vindas! Para contribuir:

1. Faça um Fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Roadmap

- [ ] Suporte para mais de 2 PDFs
- [ ] Reordenação de páginas via drag & drop
- [ ] Remoção de páginas específicas
- [ ] Rotação de páginas
- [ ] Adição de marcas d'água
- [ ] Compressão de PDF
- [ ] Conversão de imagens para PDF
- [ ] Modo escuro (dark mode)
- [ ] Histórico de operações
- [ ] Suporte para múltiplos idiomas

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 👨‍💻 Autor

**Central de Tecnologia SoftPog**

- Website: [em desenvolvimento]
- Email: contato@softpog.com.br

## 🙏 Agradecimentos

- [pdf-lib](https://github.com/Hopding/pdf-lib) - Biblioteca incrível para manipulação de PDFs
- [Bootstrap](https://getbootstrap.com/) - Framework CSS responsivo
- [SweetAlert2](https://sweetalert2.github.io/) - Alertas bonitos
- [Lucide](https://lucide.dev/) - Ícones modernos
- Comunidade open source

## 📞 Suporte

Se você encontrar algum problema ou tiver sugestões, por favor:

1. Abra uma [Issue](https://github.com/seu-usuario/unificador-pdf/issues)
2. Entre em contato via email: contato@softpog.com.br
3. Consulte a [Wiki](https://github.com/seu-usuario/unificador-pdf/wiki) do projeto

---

⭐ Se este projeto foi útil para você, considere dar uma estrela no GitHub!

**Desenvolvido com ❤️ pela Central de Tecnologia Mandu**
