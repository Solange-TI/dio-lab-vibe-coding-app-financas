# 💸 App de Finanças Pessoais Interativo com Vibe Coding

PRD Refinado no Copilot Web

''' Markdown
# PRD - Assistente de Finanças Pessoais Conversacional

## Visão Geral

Criar um aplicativo de finanças pessoais baseado em conversação natural, permitindo que usuários registrem despesas, acompanhem metas financeiras e recebam orientações de economia por meio de uma experiência semelhante a conversar com um assistente pessoal.

O objetivo é reduzir a fricção do controle financeiro tradicional, eliminando a necessidade de formulários complexos e lançamentos manuais detalhados.

---

## Problema

Muitas pessoas abandonam aplicativos financeiros porque precisam registrar manualmente suas despesas em múltiplos campos e categorias.

Esse processo gera esforço excessivo, reduz o engajamento e dificulta a criação do hábito de acompanhamento financeiro.

Existe a oportunidade de oferecer uma experiência mais simples através de linguagem natural e automação inteligente.

---

## Público-Alvo

### Primário

Pessoas que estão começando a organizar suas finanças pessoais.

### Secundário

Usuários que já tentaram utilizar planilhas ou aplicativos financeiros, mas desistiram por considerá-los complexos.

---

## Proposta de Valor

"Controle suas finanças simplesmente conversando."

O usuário pode registrar gastos e receitas em linguagem natural, enquanto a IA interpreta, categoriza e organiza as informações automaticamente.

Exemplos:

- "Gastei R$ 45 no almoço."
- "Recebi R$ 2.500 de salário."
- "Paguei R$ 180 de energia."

---

## Objetivos do MVP

1. Permitir o registro financeiro via chat.
2. Automatizar a categorização das movimentações.
3. Fornecer um resumo financeiro simples.
4. Permitir criação de metas financeiras.
5. Entregar recomendações básicas de economia.

---

## Funcionalidades

### 1. Registro Conversacional

O usuário envia mensagens em linguagem natural.

A IA extrai:

- Valor
- Tipo (receita ou despesa)
- Categoria
- Data

Exemplo:

Entrada:
"Gastei R$ 120 no mercado ontem."

Saída estruturada:

- Tipo: Despesa
- Valor: R$ 120
- Categoria: Alimentação
- Data: Ontem

---

### 2. Categorização Automática

Categorias iniciais:

- Alimentação
- Transporte
- Moradia
- Lazer
- Educação
- Saúde
- Compras
- Outros

O usuário poderá corrigir categorias quando desejar.

---

### 3. Metas Financeiras

Exemplos:

- Guardar R$ 5.000
- Economizar R$ 300 por mês
- Criar reserva de emergência

Acompanhamento visual de progresso.

---

### 4. Agente Financeiro

Assistente que analisa movimentações e oferece sugestões como:

- Redução de gastos recorrentes
- Comparação entre meses
- Alertas de excesso de despesas
- Incentivos para atingir metas

---

### 5. Dashboard Simplificado

Exibir:

- Saldo atual
- Gastos do mês
- Receitas do mês
- Categorias com maior consumo
- Progresso das metas

---

## Princípios de Design Universal e Acessibilidade

O aplicativo deverá seguir princípios de Design Universal, garantindo uma experiência intuitiva, acessível e agradável para o maior número possível de usuários, independentemente de idade, experiência tecnológica, alfabetização financeira, condição física ou cognitiva.

### Diretrizes

- Utilizar linguagem simples e objetiva.
- Evitar termos técnicos financeiros desnecessários.
- Priorizar fluxos guiados por conversa.
- Garantir contraste adequado entre textos e elementos visuais.
- Utilizar tipografia legível em diferentes tamanhos de tela.
- Oferecer ícones acompanhados por texto explicativo.
- Minimizar a necessidade de aprendizado prévio.
- Permitir correção fácil de erros durante o uso.
- Disponibilizar alternativas visuais e textuais para informações importantes.
- Garantir compatibilidade com leitores de tela e tecnologias assistivas.
- Funcionar adequadamente em dispositivos móveis de diferentes tamanhos.
- Priorizar acessibilidade desde o início do desenvolvimento, e não como adaptação posterior.

### Regra de Produto

Todas as decisões de produto, UX e interface devem priorizar simplicidade, acessibilidade e Design Universal, permitindo que usuários com diferentes níveis de alfabetização financeira e experiência tecnológica utilizem o aplicativo com sucesso desde o primeiro acesso.

### Critérios de Sucesso de UX

Um novo usuário deve conseguir:

- Registrar uma despesa.
- Visualizar seu resumo financeiro.
- Criar uma meta financeira.

Tudo isso sem necessidade de treinamento ou consulta a documentação externa.

---

## Telas Principais

### Tela 1 - Onboarding

Objetivo:
Explicar a proposta do aplicativo.

Elementos:

- Boas-vindas
- Explicação rápida
- Definição do objetivo financeiro inicial

---

### Tela 2 - Conversa

Objetivo:
Registrar informações financeiras.

Elementos:

- Campo de mensagem
- Histórico da conversa
- Sugestões rápidas
- Confirmação de lançamentos interpretados pela IA

---

### Tela 3 - Dashboard

Objetivo:
Visualizar situação financeira.

Elementos:

- Resumo financeiro
- Gráficos simples
- Insights automáticos
- Evolução mensal

---

### Tela 4 - Metas

Objetivo:
Acompanhar objetivos financeiros.

Elementos:

- Lista de metas
- Percentual concluído
- Data prevista
- Recomendações para alcançar metas

---

### Tela 5 - Perfil e Configurações

Objetivo:
Personalização e gerenciamento da conta.

Elementos:

- Preferências
- Categorias personalizadas
- Exportação de dados
- Configurações de acessibilidade

---

## Fluxo Principal do Usuário

1. Usuário cria conta.
2. Define um objetivo financeiro.
3. Registra gastos ou receitas pelo chat.
4. IA interpreta e categoriza automaticamente.
5. Dashboard atualiza em tempo real.
6. Agente Financeiro gera recomendações.
7. Usuário acompanha evolução das metas.
8. Usuário ajusta hábitos com base nos insights recebidos.

---

## Recursos Necessários para o MVP

### Frontend

- Interface conversacional estilo ChatGPT/WhatsApp.
- Dashboard financeiro simplificado.
- Gestão de metas.
- Onboarding guiado.
- Layout responsivo para dispositivos móveis e desktop.

### Backend

- Cadastro e autenticação de usuários.
- Banco de dados para transações.
- Banco de dados para metas.
- Histórico de conversas.
- Serviço de categorização.

### Inteligência Artificial

- Extração de entidades financeiras.
- Classificação automática de transações.
- Interpretação de linguagem natural.
- Geração de recomendações financeiras básicas.
- Sugestões contextualizadas baseadas no comportamento do usuário.

---

## Critérios de Validação

Realizar testes com 10 a 20 usuários.

Validar:

1. Facilidade de registro por conversa.
2. Clareza dos relatórios.
3. Utilidade das recomendações.
4. Facilidade para acompanhar metas.
5. Facilidade de uso para pessoas com pouca familiaridade financeira.

O MVP será considerado validado se a maioria dos usuários relatar que o aplicativo é mais simples e intuitivo do que planilhas ou aplicativos financeiros tradicionais.

---

## Métricas de Sucesso

- Usuário registrar pelo menos 5 movimentações na primeira semana.
- Retenção após 7 dias.
- Criação de pelo menos uma meta financeira.
- Precisão da categorização acima de 80%.
- Satisfação positiva com as recomendações da IA.
- Conclusão bem-sucedida do fluxo principal sem suporte externo.

---

## Fora do Escopo do MVP

- Integração bancária automática.
- Open Finance.
- Sincronização com cartões de crédito.
- Controle de investimentos.
- Planejamento tributário.
- Multiusuários.
- Compartilhamento familiar.
- Controle empresarial.
'''

### Interações com o Lovable

Crie um app de finanças pessoais com base no seguinte PRD (Product Requirements Document).
Como deve funcionar a conversa com o assistente?
Uma conversa contínua
Onde salvar lançamentos, metas e histórico?
Só neste navegador

### Resultado final no Lovable: (https://rotina-financeira-feliz.lovable.app/)

## Reflexão 

### O que funcionou bem?
O refinamento do PRD feito no Copilot anteriormente foi essencial, pois os créditos do Lovable acabaram com apenas três interações.

 ### O que não funcionou como o esperado?
Esperava poder visualizar a página inicial do App, porém fui direcionada a responder duas perguntas e estas consumiram os créditos do Lovable e tive que esperar três horas para poder visualizar.

### O que aprendeu sobre conversar com IAs?
Que quanto melhor as perguntas, melhores serão as respostas.

- Seu **prompt final** (PRD);  
- Prints ou pequenos vídeos das interações com a IA;
   
## Um resumo do que o seu **App de Finanças Pessoais** faz;
### <img width="290" height="2268" alt="image" src="https://github.com/user-attachments/assets/2ad2461b-2003-44f0-a3a2-ae6bb5effa61" />
 

<img width="795" height="609" alt="Captura de tela 2026-11-15 201259" src="https://github.com/user-attachments/assets/321e6305-11e5-460e-a726-80178c0c7ce5" />



## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
