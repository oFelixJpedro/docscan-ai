# DocScan AI 📄

Ferramenta web de recorte inteligente de documentos com visão computacional e IA.

## O que faz

Você tira uma foto de um documento (RG, CNH, passaporte, comprovante...) em qualquer ângulo e o DocScan AI:

1. **Detecta** o documento na imagem via Google Gemini
2. **Aplica correção de perspectiva** com algoritmo de homografia implementado do zero
3. **Corrige a rotação** automaticamente
4. **Exporta** o documento recortado em JPG ou PDF

## Tecnologias

- **Google Gemini API** (gemma-4-31b) — detecção e análise do documento
- **Computer Vision** — algoritmo de homografia para correção de perspectiva
- **jsPDF** — geração de PDF no browser
- **JavaScript** — sem frameworks, implementação vanilla
- **HTML/CSS** — interface drag & drop

## Como funciona

```
Foto com documento
        ↓
Gemini analisa e retorna os 4 cantos do documento
        ↓
Algoritmo de homografia aplica a transformação de perspectiva
        ↓
Rotação corrigida automaticamente
        ↓
Exportação em JPG ou PDF
```

## Funcionalidades

- ✅ Drag & drop de imagens
- ✅ Processamento em lote (múltiplos documentos)
- ✅ Correção de perspectiva (homografia)
- ✅ Correção de rotação automática
- ✅ Rotação manual pós-processamento
- ✅ Exportação individual em JPG ou PDF
- ✅ PDF combinado com múltiplos documentos selecionados
- ✅ Indicador de legibilidade do documento

## Como usar

1. Cole sua chave da [Google AI Studio](https://aistudio.google.com/apikey)
2. Arraste as imagens ou clique para selecionar
3. Clique em **Iniciar Processamento**
4. Baixe os documentos recortados em JPG ou PDF

## Autor

**João Pedro Félix Barbosa**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/ofelix-jpedro)
