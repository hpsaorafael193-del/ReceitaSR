📄 Sistema de Receituário Médico — Hospital São Rafael

Sistema web para criação, visualização e exportação de receituários médicos, desenvolvido com foco em padronização institucional, fidelidade ao formato A4 e uso prático em ambientes simulados de atendimento médico (RP).

O projeto prioriza clareza visual, organização clínica e comportamento previsível do documento final, simulando sistemas reais utilizados em ambientes hospitalares.

🎯 Objetivo do Projeto

Padronizar a emissão de receitas médicas

Garantir fidelidade visual ao formato A4

Facilitar a prescrição com modo guiado

Gerar documentos com aparência profissional

Servir como módulo de um sistema clínico maior

Uso exclusivo em ambiente RP médico

🧩 Funcionalidades Principais
🩺 Prescrição

Prescrição livre por texto

Prescrição guiada (nome, dose, intervalo, via, duração)

Inserção automática no corpo da receita

Controle de tamanho para evitar receitas excessivamente longas

📄 Documento

Layout fixo em A4 (794 × 1123 px)

Cabeçalho institucional

Dados do paciente alinhados ao padrão médico

Corpo da receita com controle de rolagem

Rodapé fixo com nome do médico e CRM

Hierarquia visual semelhante a receituários reais

🖊️ Carimbo Médico

Upload de PNG sem fundo

Visualização no formulário

Aplicação automática no documento

Posicionamento flutuante institucional

Persistência via localStorage

💾 Persistência

Salvamento automático de rascunho

Recuperação ao recarregar a página

Numeração automática e sequencial da receita

📤 Exportação

Geração de PNG em A4

Fidelidade visual entre preview e arquivo final

Documento pronto para arquivamento ou envio

🗂️ Estrutura do Projeto
/
├── index.html
└── assets
    ├── css
    │   └── style.css
    └── js
        └── app.js


index.html → Estrutura da aplicação

style.css → Estilos gerais e padronização A4

app.js → Lógica de prescrição, preview, carimbo e exportação

🛠️ Tecnologias Utilizadas

HTML5

CSS3 (layout fixo A4)

JavaScript (vanilla)

html2canvas (exportação PNG)

LocalStorage (persistência de dados)

⚠️ Aviso Importante

Este sistema não possui validade legal e não substitui softwares médicos reais.

Uso destinado exclusivamente para simulação médica (RP)
Hospital São Rafael — Servidor RP Eldorado

🔐 Licença de Uso

Uso restrito ao autor do projeto e ao grupo autorizado do Hospital São Rafael (RP).
Qualquer redistribuição, modificação ou uso fora do contexto acordado não é permitida.

👤 Autor

Luidhy C. dos Santos
Projeto desenvolvido para uso interno em RP médico.
GitHub: https://github.com/Luidhycs