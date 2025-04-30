# ⚕️ Projeto SAGE
Sistema de Acompanhamento e Gerenciamento de Equipamentos Hospitalares

## 🤝 Nossa Equipe
Somos um time apaixonado por tecnologia e inovação, trazendo expertise para transformar a gestão de equipamentos hospitalares. Nossa equipe é formada por quatro estudantes dedicados, cursando Análise e Desenvolvimento de Sistemas na renomada faculdade CESAR School, são eles:

- Diego Alves Xavier
- Hyngrid Souza e Silva
- Maria Gabriela Damásio Bezerra
- Pamela Teixeira Rodrigues

## 📝 Sobre o Projeto
O **Projeto SAGE** é uma solução inteligente para a **gestão de equipamentos clínicos** em ambientes hospitalares. Nosso objetivo é otimizar a manutenção e o monitoramento de equipamentos essenciais para o funcionamento da saúde, com uma interface intuitiva e poderosa.

**SAGE** não só facilita a criação e o fechamento de ordens de serviço, mas também oferece um painel visual interativo, alertas automáticos e relatórios detalhados. Isso ajuda gestores e equipes técnicas a tomarem decisões rápidas e assertivas. Com o **SAGE**, hospitais podem garantir que seus equipamentos estejam sempre operacionais, evitando falhas críticas e melhorando a eficiência no atendimento aos pacientes.

## 🔧 Funcionalidades Principais
**SAGE** oferece funcionalidades pensadas para garantir **eficiência, controle e segurança** no ambiente hospitalar:

- 🔐 **Autenticação Segura e Gestão de Acessos**: Login protegido com perfis de usuário (Gestor, Técnico, Administrador).
- 📊 **Dashboard Interativo**: Painel centralizado para monitoramento dos equipamentos e ordens de serviço, com indicadores visuais claros.
- 🛠️ **Gestão de Equipamentos**: Cadastro completo de equipamentos, com histórico de manutenções e condições em tempo real.
- 📋 **Gestão de Manutenções e O.S.**: Criação e fechamento de ordens de serviço de forma ágil e eficiente.

## 📋 Priorização do Backlog  
Utilizamos a metodologia MoSCoW para priorizar as funcionalidades de **SAGE**, garantindo que atendamos as necessidades mais urgentes desde o início do projeto:

### **Must Have**  
- 🔐 **Login e Perfis de Usuário**  
- 📊 **Dashboard com Status de O.S.**  
- 🛠️ **Cadastro e Consulta de Equipamentos**  
- 📋 **Abertura e Fechamento de O.S.**  
- ⏰ **Alertas de Manutenção Preventiva**  

### **Should Have**  
- 📄 **Controle de Contratos e Alertas de Vencimento**  
- 📦 **Gerenciamento de Estoque de Peças**  
- 📈 **Geração de Relatórios Personalizados**  

### **Could Have**  
- ⚠️ **Painel de Prioridades e Urgências**  
- ⏳ **Alertas de Atraso em O.S.**  

### **Won’t Have (por enquanto)**  
- 🌐 **Integração com Sistemas Externos de Gestão Hospitalar**  
- 🤖 **Inteligência Artificial para Previsão de Falhas**  

## 🧑‍💻 Histórias de Usuário 
[Screencast](https://drive.google.com/file/d/1slR2k941rDWS85niRgqrt9ieG7XNEMER/view)

- ### 1. **Autenticação e Definição de Perfil**  
**Conversa com o P.O:**  
**Desenvolvedor:**  
Oi, PO! Para a história "Autenticação e Definição de Perfil", temos um requisito claro de login e senha. Para a recuperação de senha, qual fluxo você imagina? O usuário vai receber um link por e-mail para resetar a senha ou ele vai responder a perguntas de segurança?  
**Product Owner:**  
Boa pergunta! Acredito que a recuperação de senha deva ser via e-mail, com um link temporário para redefinir a senha. Em relação aos perfis, precisamos garantir que o sistema mostre opções de menu diferentes dependendo do perfil. No caso de "Gestor", por exemplo, ele deverá ter acesso a relatórios e dashboards, mas "Técnicos" só verão informações relevantes para manutenção.

**História do Usuário:**  
Como usuário do sistema, quero fazer login de forma segura e escolher meu perfil, para acessar funcionalidades específicas ao meu papel.

**Critérios de Aceitação:**
- O sistema deve permitir login e senha.
- Deve haver opção de recuperação de senha.
- O sistema adapta a interface conforme o perfil do usuário (Gestor, Técnico, Administrador).
- 
**Time Stamp:** 00:00-00:28  
**Figma Time Stamp:** 02:48-03:38
  
**Implementação no protótipo:**
![image](https://github.com/user-attachments/assets/97d60a62-5d38-4bce-9f1c-30e13ffabd94)

---

- ### 2. **Visualização de Dashboard**  
**Conversa com o P.O:**  
**Desenvolvedor:**  
PO, sobre o painel do gestor, o que você imagina quando fala sobre indicadores visuais de criticidade? Você tem algum modelo ou exemplo de visualização?  
**Product Owner:**  
Quero algo bem visual, tipo semáforo: verde, amarelo e vermelho para indicar o status dos equipamentos e das ordens de serviço. E, sobre filtros, podemos ter opções por período (diário, semanal, mensal) e também por tipo de manutenção, como preventiva ou corretiva.

**História do Usuário:**  
Como gestor hospitalar, quero ver um painel de controle com status dos equipamentos e ordens de serviço, para tomar decisões rápidas.

**Critérios de Aceitação:**
- Exibir status dos equipamentos e O.S. abertas.
- Incluir indicadores visuais de criticidade.
- Permitir filtros por período e tipo de manutenção.

**Time Stamp:** 00:28-01:23  
**Figma Time Stamp:** 03:38-04:16; 04:47-05:50; 06:18-06:48

**Implementação no protótipo:**
![image](https://github.com/user-attachments/assets/0d4e5bf6-8137-47f0-94e6-a58c182367e3)
![image](https://github.com/user-attachments/assets/363e0d90-8e49-40a6-b8c6-050b4cd0203e)
![image](https://github.com/user-attachments/assets/8381bd9f-2dc8-4cbc-94f5-61d5b7d0f2db)

---

- ### 3. **Consulta de Equipamento**  
**Conversa com o P.O:**  
**Desenvolvedor:**  
Para a consulta de equipamentos, a busca pode ser feita pelo nome, código ou categoria, mas em relação ao histórico de manutenção, você quer ver também o que foi feito nos últimos meses ou o histórico completo?  
**Product Owner:**  
O histórico precisa ser completo, incluindo todas as manutenções anteriores, para que o técnico possa identificar padrões de falha. E a exibição do status atual do equipamento deve ser visível no topo da tela para facilitar o acesso rápido.

**História do Usuário:**  
Como técnico de manutenção, quero consultar um equipamento pelo código ou nome, para ver seu histórico de manutenção.

**Critérios de Aceitação:**
- Permitir busca por nome, código ou categoria.
- Mostrar status atual do equipamento.
- Listar histórico completo de manutenções.

**Time Stamp:** 01:15-01:22 

---

- ### 4. **Abertura de Ordem de Serviço (O.S.)**  
**Conversa com o P.O:**  
**Desenvolvedor:**  
Para abrir uma O.S., o técnico deve selecionar o equipamento e relatar o problema. Quando falamos sobre a prioridade, você acha que a opção de "Baixa, Média e Alta" é suficiente ou devemos adicionar alguma outra prioridade, como "Urgente"?  
**Product Owner:**  
Acho que "Baixa, Média e Alta" são suficientes, mas precisamos ter flexibilidade para alterar a prioridade depois, caso a situação mude. Atribuir o técnico responsável também é crucial, por isso precisamos garantir que ele seja notificado assim que a O.S. for criada.

**História do Usuário:**  
Como técnico de manutenção, quero abrir uma O.S. rapidamente, para garantir que os equipamentos sejam reparados sem atrasos.

**Critérios de Aceitação:**
- Selecionar equipamento e relatar problema.
- Definir prioridade da O.S. (Baixa, Média, Alta).
- Atribuir técnico responsável.

**Time Stamp:**  01:24-01:55  
**Figma Time Stamp:** 04:16-04:46; 06:48-07:48

**Implementação no protótipo:**
![image](https://github.com/user-attachments/assets/bc4c5267-3046-4ce4-9c66-3bf91961e82a)
![image](https://github.com/user-attachments/assets/544e939c-1ba4-4dcd-ad8a-5984a27a3494)

---

- ### 5. **Fechamento de Ordem de Serviço com Relatório**  
**Conversa com o P.O:**  
**Desenvolvedor:**  
Ao fechar uma O.S., você mencionou que o técnico pode adicionar descrição da manutenção. Devemos também permitir que o técnico adicione fotos do que foi feito ou da peça substituída?  
**Product Owner:**  
Sim, seria interessante adicionar fotos, especialmente para casos de peças danificadas ou problemas recorrentes. Isso ajudaria a documentar melhor e a tornar o histórico mais rico.

**História do Usuário:**  
Como técnico de manutenção, quero registrar detalhes da O.S. ao encerrá-la, para manter um histórico completo das intervenções.

**Critérios de Aceitação:**
- O técnico pode adicionar descrição da manutenção realizada.
- Registrar peças substituídas e tempo gasto.
- Gerar relatório automático da intervenção.

**Time Stamp:**  01:55-03:08  
**Figma Time Stamp:** 07:48-08:35

**Implementação no protótipo:**
![image](https://github.com/user-attachments/assets/130016b9-d43e-438f-8dd9-d730f8a31b4e)

---

- ### 6. **Controle de Contratos**  
**Conversa com o P.O:**  
**Desenvolvedor:**  
Quando falamos sobre monitoramento de contratos, você imagina que o sistema deve enviar alertas para os contratos próximos do vencimento, mas com que antecedência você gostaria desses alertas? Uma semana? 30 dias?  
**Product Owner:**  
Idealmente, alertas com 30 dias de antecedência. Isso daria tempo suficiente para a equipe verificar a renovação. E sim, os documentos contratuais devem ser anexados ao contrato para fácil acesso.

**História do Usuário:**  
Como gestor hospitalar, quero monitorar contratos com fornecedores, para garantir conformidade e evitar problemas operacionais.

**Critérios de Aceitação:**
- Permitir cadastro e visualização dos contratos.
- Gerar alertas para contratos próximos ao vencimento.
- Anexar documentos contratuais.

**Time Stamp:**  01:38-01:46  
**Figma Time Stamp:** 05:50-06:17

**Implementação no protótipo:**
![image](https://github.com/user-attachments/assets/c66db552-bb0a-4b94-af8e-4729e3b53d7b)

---

- ### 7. **Alertas Automáticos de Manutenção**  
**Conversa com o P.O:**  
**Desenvolvedor:**  
Em relação aos alertas de manutenção, você gostaria de configurar o tipo de notificação (e-mail, SMS, ou dentro do sistema)? E sobre a falha recorrente, seria interessante que o sistema enviasse uma notificação automaticamente quando detectar o mesmo erro mais de uma vez em um curto período?  
**Product Owner:**  
Sim, por favor! E-mails são uma boa forma de notificação, mas dentro do sistema também precisa haver uma área de alertas visíveis. E sim, sobre a falha recorrente, se um erro aparecer mais de 3 vezes no mês, o sistema deve enviar uma notificação automática.

**História do Usuário:**  
Como administrador da clínica, quero receber alertas sobre manutenções programadas, para garantir que os equipamentos estejam sempre operacionais.

**Critérios de Aceitação:**
- Alertas automáticos para manutenções preventivas.
- Notificações sobre falhas recorrentes.
- Opção de configurar preferências para receber alertas.
  
**Time Stamp:**  01:46-01:56 

---

- ### 8. **Geração de Relatórios Personalizados**  
**Conversa com o P.O:**  
**Desenvolvedor:**  
Na geração de relatórios, além de tempo médio de resposta e custo de manutenção, você gostaria de incluir mais algum indicador específico? Como, por exemplo, o custo total por equipamento ou por tipo de manutenção?  
**Product Owner:**  
Sim, incluir o custo total por equipamento seria ótimo, mas também precisamos considerar a possibilidade de gerar relatórios específicos para diferentes períodos. Como gestor, eu adoraria poder personalizar o período de análise e ver esses dados de forma mais granular.

**História do Usuário:**  
Como gestor hospitalar ou administrador, quero gerar relatórios sobre status dos equipamentos e O.S., para analisar métricas de desempenho.

**Critérios de Aceitação:**
- Permitir filtros personalizados para gerar relatórios.
- Mostrar tempo médio de resposta e custo de manutenção.
- Possibilidade de exportação em PDF e Excel.

**Time Stamp:**  01:56-02:04

---

- ### 9. **Gerenciamento de Estoque de Peças**  
**Conversa com o P.O:**  
**Desenvolvedor:**  
Para o gerenciamento de estoque de peças, você gostaria de integrar o sistema com o fornecedor para que a reposição de peças seja feita automaticamente quando o estoque atingir um valor mínimo?  
**Product Owner:**  
Isso seria ótimo! Integrar com os fornecedores permitiria um fluxo mais ágil de reposição, mas se isso não for viável agora, pelo menos um alerta de estoque baixo seria necessário, para que a equipe tome ação manual.

**História do Usuário:**  
Como técnico de manutenção, quero ter controle sobre as peças disponíveis no estoque, para evitar atrasos na manutenção por falta de insumos.

**Critérios de Aceitação:**
- Permitir cadastro e controle de estoque de peças.
- Notificar sobre itens com estoque baixo.
- Registrar histórico de uso de peças em manutenções.

**Time Stamp:**   02:04-02:13

---

- ### 10. **Cadastro e Classificação de Equipamentos**  
**Conversa com o P.O:**  
**Desenvolvedor:**  
No cadastro de novos equipamentos, você gostaria de incluir alguma informação adicional, como a data de aquisição ou o fabricante? E para a classificação dos equipamentos, deveríamos ter algum campo de "última manutenção"?  
**Product Owner:**  
Sim, a data de aquisição e o fabricante são essenciais. E a última manutenção também deve ser visível, pois ajuda na análise da condição do equipamento. A classificação por criticidade vai depender do impacto no hospital, então, é bom que isso seja algo que o gestor possa definir.

**História do Usuário:**  
Como administrador da clínica, quero cadastrar novos equipamentos no sistema, para controlar seu ciclo de vida e manutenções.

**Critérios de Aceitação:**
- Permitir cadastro de novos equipamentos com detalhes técnicos.
- Classificar equipamentos por tipo, localização e criticidade.
- Vincular equipamentos a contratos de manutenção.

**Time Stamp:**   02:13-02:22

---

- ### 11. **Painel de Prioridades e Urgências**  
**Conversa com o P.O:**  
**Desenvolvedor:**  
Você mencionou um painel destacando as O.S. urgentes. Como o sistema deve lidar com mudanças de prioridade? Se, por exemplo, uma O.S. "Média" se tornar urgente, como devemos mostrar isso para os técnicos?  
**Product Owner:**  
A prioridade precisa ser editável em tempo real, e quando algo for alterado, a O.S. deve subir automaticamente para o topo do painel, com uma cor diferente para destacar a urgência.

**História do Usuário:**  
Como gestor hospitalar, quero visualizar um painel que prioriza as O.S. mais urgentes, para direcionar esforços rapidamente para as demandas críticas.

**Critérios de Aceitação:**
- Criar um painel destacando O.S. urgentes.
- Permitir reordenação de prioridades em tempo real.
- Integrar com alertas automáticos para notificação de emergências.

**Time Stamp:**   02:22-02:29

---

- ### 12. **Histórico de Intervenções Técnicas**  
**Conversa com o P.O:**  
**Desenvolvedor:**  
Quando falamos sobre o histórico de intervenções, você imagina que ele deve incluir apenas as manutenções ou também detalhes sobre as falhas encontradas durante a inspeção?  
**Product Owner:**  
O histórico deve incluir tanto as manutenções realizadas quanto as falhas encontradas. Seria bom também que, ao clicar em uma intervenção, o técnico possa ver informações detalhadas sobre o problema identificado.

**História do Usuário:**  
Como técnico de manutenção, quero acessar um histórico detalhado de todas as intervenções já realizadas em um equipamento, para analisar padrões e prever falhas futuras.

**Critérios de Aceitação:**
- Exibir histórico cronológico das intervenções técnicas.
- Permitir filtros por tipo de falha ou componente trocado.
- Gerar insights sobre padrões de falha recorrentes.

**Time Stamp:**   02:29-02:37

## 🎨 Prototipagem e Design  
Para uma visão mais imersiva do projeto, confira nossos protótipos e veja como **SAGE** vai revolucionar a gestão de equipamentos hospitalares:

- **Protótipos Lo-Fi** disponíveis no [Figma](https://www.figma.com/proto/fNpzjR1EqV8dfAkAnqauC4/SAGE?node-id=16-283&p=f&t=MnvjLIMUqd6eujuW-0&scaling=scale-down&content-scaling=fixed&page-id=0%3A1)
- **Screencast** para explicar e visualizar o protótipo em desenvolvimento [Link do Screencast](https://drive.google.com/file/d/1foDUKuqZTrG89-B_wx9Gv1R1nwtUj-_m/view?usp=drive_link)

## 📸 Capturas de Tela e Backlog (Trello)  
Acompanhe nosso progresso diretamente nas ferramentas de gestão de projetos:

- **Quadro e Backlog (Trello)**  
  - **Sprint 1**:
  ![backlog](https://github.com/user-attachments/assets/2a748d86-6a82-4d64-989b-53a576fe3ef8)

## 📚 Sketches e Storyboards  
Acompanhe o desenvolvimento do projeto com os sketches e storyboards das funcionalidades em andamento: [Figma](https://www.figma.com/proto/fNpzjR1EqV8dfAkAnqauC4/SAGE?node-id=16-283&p=f&t=MnvjLIMUqd6eujuW-0&scaling=scale-down&content-scaling=fixed&page-id=0%3A1), [Link do Screencast](https://drive.google.com/file/d/1foDUKuqZTrG89-B_wx9Gv1R1nwtUj-_m/view?usp=drive_link)
  
- **História 1**: Autenticação e Definição de Perfil (MINUTAGEM: 00:52-01:06; 02:48-03:38)  
- **História 2**: Visualização de Dashboard (MINUTAGEM: 01:06-01:15; 03:38-04:16; 04:47-05:50; 06:18-06:48)  
- **História 4**: Abertura de Ordem de Serviço (MINUTAGEM: 01:23-01:30; 04:16-04:46; 06:48-07:48)    
- **História 5**: Fechamento de Ordem de Serviço com Relatório (MINUTAGEM: 01:30-01:38; 07:48-08:35)
- **História 6**: Controle de Contratos (MINUTAGEM: 01:38-01:46; 05:50-06:17)

## 🎥 Screencast do Protótipo  
Assista ao vídeo do protótipo para ver como o sistema funciona e entender como ele pode beneficiar a gestão de equipamentos hospitalares:

- [Screencast do Protótipo](https://drive.google.com/file/d/1slR2k941rDWS85niRgqrt9ieG7XNEMER/view)

### 1. TIME STAMP

- **INTRODUÇÃO**: 00:00-00:51  
- **HU 1 (Autenticação e Definição de Perfil)**: 00:52-01:06  
- **HU 2 (Visualização de Dashboard)**: 01:06-01:15  
- **HU 3 (Consulta de Equipamento)**: 01:15-01:22  
- **HU 4 (Abertura de Ordem de Serviço (O.S.))**: 01:23-01:30  
- **HU 5 (Fechamento de Ordem de Serviço com Relatório)**: 01:30-01:38  
- **HU 6 (Controle de Contratos)**: 01:38-01:46  
- **HU 7 (Alertas Automáticos de Manutenção)**: 01:46-01:56  
- **HU 8 (Geração de Relatórios Personalizados)**: 01:56-02:04  
- **HU 9 (Gerenciamento de Estoque de Peças)**: 02:04-02:13  
- **HU 10 (Cadastro e Classificação de Equipamentos)**: 02:13-02:22  
- **HU 11 (Painel de Prioridades e Urgências)**: 02:22-02:29  
- **HU 12 (Histórico de Intervenções Técnicas)**: 02:29-02:37  
- **Encerramento HU’s**: 02:38-02:48  

**Figma**

- **HU 1 (Autenticação e Definição de Perfil)**: 02:48-03:38  
- **HU 2 (Visualização de Dashboard)**: 03:38-04:16; 04:47-05:50; 06:18-06:48  
- **HU 4 (Abertura de Ordem de Serviço (O.S.))**: 04:16-04:46; 06:48-07:48  
- **HU 5 (Fechamento de Ordem de Serviço com Relatório)**: 07:48-08:35  
- **HU 6 (Controle de Contratos)**: 05:50-06:17

**Protótipo do Site**
- Login (Autenticação e Definição de Perfil):  00:00-00:28
- Dashboard Eng Clínico (Visualização de Dashboard): 00:28-01:23
- Abrir O.S (Abertura de Ordem de Serviço (O.S.)):  01:24-01:55
- Fechar O.S (Fechamento de Ordem de Serviço com Relatório): 01:55-03:08

---

**Transforme a gestão de manutenção hospitalar com o SAGE** — mais controle, mais eficiência, mais segurança para você e sua equipe. Se você está interessado em saber mais ou contribuir para o desenvolvimento deste projeto inovador, não hesite em entrar em contato!

---
