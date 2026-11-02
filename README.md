# UFPR - Gestor de Horas Formativas com IA

Ferramenta web gratuita para alunos da UFPR organizarem e contabilizarem seus certificados de Atividades Formativas usando Inteligência Artificial (Google Gemini).

## Como Usar

1. Acesse o site hospedado no GitHub Pages
2. Insira sua **API Key gratuita** do [Google AI Studio](https://aistudio.google.com/app/apikey)
3. Informe o **mês/ano de ingresso** na UFPR
4. Arraste seus certificados em PDF para a área de upload
5. A IA irá automaticamente:
   - Identificar o assunto e a data do certificado
   - Classificar na categoria correta (Grupo 1 - Acadêmico ou Grupo 2 - Social)
   - Extrair/estimar a carga horária
   - Validar se a data é posterior ao ingresso
   - Aplicar os tetos por categoria conforme o Regulamento

## Tecnologias

- **PyScript** (Python rodando no navegador via WebAssembly)
- **Google Gemini API** (chamada direta via REST, sem backend)
- **HTML/CSS/JS** (interface responsiva com glassmorphism)
- **localStorage** (dados ficam apenas no navegador do usuário)

## Privacidade

Nenhum dado é enviado para servidores nossos. Os PDFs são processados diretamente entre o navegador do aluno e a API do Google Gemini usando a chave pessoal do usuário.

## Contexto do projeto

Aplicação web desenvolvida para apoiar estudantes da UFPR na organização de Atividades Formativas. Combina processamento local no navegador, PyScript e Google Gemini, mantendo os arquivos do usuário fora de um backend próprio.

**Temas:** IA aplicada, automação acadêmica, privacidade e experiência do usuário.

[Ver repositório](https://github.com/brunomarafiga/horas_formativas_UFPR)
