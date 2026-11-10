# Missão Corpo Humano

Laboratório digital interativo de revisão de Biologia para o Ensino Médio, com atividade individual e Escape Room.

## Arquivos
- `index.html`: estrutura do site.
- `style.css`: identidade visual e responsividade.
- `app.js`: estações, questões, integração dos sistemas e Escape Room.
- `assets/`: espaço para imagens e recursos complementares.

## Publicação no GitHub Pages
1. Envie `index.html`, `style.css`, `app.js` e a pasta `assets` para a raiz do repositório.
2. Acesse Settings > Pages.
3. Selecione Deploy from a branch, branch `main`, pasta `/ (root)`.
4. Salve e aguarde a publicação.

## Configurar Microsoft Forms
O site não coleta nem armazena nomes. Para registrar a participação:
1. Crie um Microsoft Forms com dois campos obrigatórios: **Nome completo** e **Código final da missão**.
2. No Forms, use a opção de compartilhar/incorporar e copie o link de incorporação (embed) e o link para responder.
3. Abra `app.js` e localize no início:
   - `FORMS_RESPONSE_URL`
   - `FORMS_EMBED_URL`
4. Substitua as aspas vazias pelos links correspondentes, mantendo as aspas.
5. Salve e envie o `app.js` atualizado ao GitHub.

Código de conclusão desta versão: o aluno recebe um código de cinco dígitos ao resolver os cinco enigmas. O código é exibido na tela final e deve ser digitado no Forms. A validação da participação é feita pela conferência das respostas no Microsoft Forms.

## Observações
- O Escape Room utiliza um cronômetro de 20 minutos, mas não bloqueia o estudante quando o tempo termina.
- O progresso das estações e dos enigmas permanece na sessão atual do navegador; não há banco de dados nesta versão.
- O site não substitui materiais didáticos, atlas anatômicos ou orientação docente.


## Microsoft Forms configurado
O link de resposta informado pela professora já está configurado em `app.js`. O botão de abertura do formulário será exibido após a conclusão do Escape Room e na área de registro. Para incorporar o formulário dentro da página, ainda é necessário obter o link específico de incorporação (`iframe`) no Microsoft Forms.


## Registro de participação
O Microsoft Forms está incorporado à seção **Registro de participação** por meio do link oficial de incorporação (`embed=true`). O estudante deve informar o nome completo e o código final da missão. O site não armazena esses dados.
