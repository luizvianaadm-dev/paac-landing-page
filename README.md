# PAAC Landing Page - Guia de Implementação com Vercel

## 📋 Descrição
Landing page profissional para o **PAAC (Programa de Aperfeiçoamento em Contabilidade)** integrada com Hotmart para checkout e pagamento.

## 🚀 Início Rápido (5 minutos)

### 1. Deploy automático no Vercel
Clique no botão abaixo para fazer deploy automático:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fluizvianaadm-dev%2Fpaac-landing-page)

### 2. Configurar domínio customizado (OPCIONAL)
Após fazer o deploy:
1. Vá para o painel Vercel
2. Acesse seu projeto
3. Vá em "Settings" > "Domains"
4. Adicione `paac.vorcon.academy` (ou seu domínio)
5. Configure as DNS records

## 📁 Estrutura do Projeto

```
paac-landing-page/
├── index.html          # Página principal (HTML/CSS/JS integrados)
├── vercel.json         # Configuração Vercel
└── README.md           # Este arquivo
```

## 🎯 Funcionalidades

✅ **Design Responsivo** - Mobile, tablet e desktop otimizados
✅ **Hero Section** - Com proposta de valor clara
✅ **Seção de Benefícios** - 6 cards com diferenciais
✅ **Curriculum/Conteúdo** - Exibe os 3 módulos (CPC 00, 01, 02)
✅ **CTA Destacados** - Botões de compra em múltiplos pontos
✅ **Informações do Criador** - Seção sobre o instrutor
✅ **Integração Hotmart** - Links diretos para checkout

## 💡 Personalizações Necessárias

Abra `index.html` e procure por `TODO:` para:

1. **Alterar link Hotmart**
   ```html
   <!-- TODO: Substitua pelo seu link Hotmart -->
   href="https://hotmart.com/pt-br/marketplace/produtos/..."
   ```

2. **Adicionar vídeo de apresentação**
   ```html
   <!-- TODO: Substitua pelo URL do seu vídeo -->
   <iframe src="https://www.youtube.com/embed/SEU_VIDEO_ID"></iframe>
   ```

3. **Informações do Instrutor**
   ```html
   <!-- TODO: Atualize nome, foto e descrição -->
   ```

4. **Cores de Branding**
   ```css
   /* Procure por :root e customize as cores -->
   --primary-color: #1e40af;
   --secondary-color: #f59e0b;
   ```

## 🔗 Links Importantes

- **Página do Marketplace Hotmart**: https://hotmart.com/pt-br/marketplace/produtos/programa-de-aperfeicoamento-com-foco-em-cpcs-e-educacao-continuada/H103573759N
- **Google Classroom**: https://classroom.google.com/c/NzkyOTc4OTMwMzYw
- **NotebookLM (Material)**: https://notebooklm.google.com/notebook/1a91485b-71c7-4bfd-a786-814a258986b6

## 📊 Preço & Pagamento

- **Valor**: R$ 290,00
- **Parcelamento**: 12x de R$ 29,99
- **Tipo**: Recorrência mensal no cartão
- **Plataforma**: Hotmart

## 🎓 Conteúdo do Curso

**Módulo 1**: CPC 00 (R2) - Estrutura Conceitual
**Módulo 2**: CPC 01 (R1) - Impairment
**Módulo 3**: CPC 02 (R2) - Taxas de Câmbio

## 👤 Instrutor

**Luiz Carlos Lopes Viana**
- Sócio de Auditoria e Consultoria - VORCON
- Especialista em Pronunciamentos Contábeis
- 4 anos Hotmarter
- Redes: Instagram, YouTube, Facebook, Twitter

## ✅ Garantia & Acesso

✓ Garantia de 7 dias
✓ Acesso 100% digital
✓ Estude em qualquer dispositivo
✓ Certificado de conclusão
✓ Suporte especializado

## 🛠️ Tecnologias

- HTML5
- CSS3 (com responsividade)
- JavaScript (vanilla)
- Vercel (deployment)
- Hotmart (pagamento)

## 📝 Licença

Propriedade de VORCON Auditoria & Consultoria

## 📧 Suporte

Para dúvidas sobre a plataforma: support@vorcon.com.br
