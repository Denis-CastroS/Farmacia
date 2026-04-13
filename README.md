# 🏥 Farmácia: Redução de Custos com AWS
## 📄 RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS

---

### ℹ️ Informações Gerais
* **📅 Data:** 12 de abril de 2026
* **🏢 Empresa:** Abstergo Industries
* **👨‍💻 Responsável:** Denis Silva
* **💊 Cliente:** Farmácias Pará

---

## 📝 Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa **Farmácias Pará**. O objetivo central do projeto foi selecionar **3 serviços AWS** estratégicos para reduzir custos imediatos e otimizar a infraestrutura da plataforma virtual, garantindo maior agilidade no atendimento e gestão.

---

## 🚀 Descrição do Projeto

O projeto foi estruturado em três etapas fundamentais, focando em armazenamento, banco de dados e computação eficiente:

### 🔹 Etapa 1: Armazenamento Inteligente
* **Ferramenta:** `Amazon S3 (Simple Storage Service)`
* **Foco:** Armazenamento de Objetos (Object Storage).
* **💼 Caso de Uso:** Armazenamento de imagens de produtos, bulas em PDF e documentos regulatórios.
* **💰 Benefício:** Elimina a necessidade de servidores de arquivos locais caros. Utiliza o **S3 Intelligent-Tiering** para mover arquivos pouco usados para classes mais baratas automaticamente.

### 🔹 Etapa 2: Banco de Dados de Alta Performance
* **Ferramenta:** `Amazon DynamoDB`
* **Foco:** Banco de Dados NoSQL (Chave-Valor).
* **💼 Caso de Uso:** Gestão do catálogo de medicamentos e controle de estoque em tempo real.
* **💰 Benefício:** Modelo *Serverless* (paga apenas pelo que usa). Evita gastos com servidores ligados 24/7 e oferece respostas em milissegundos para consultas de preços.

### 🔹 Etapa 3: Computação Otimizada
* **Ferramenta:** `Amazon EC2 com instâncias Spot`
* **Foco:** Computação em Nuvem Flexível.
* **💼 Caso de Uso:** Processamento de logs de vendas e geração de relatórios diários de fechamento de caixa.
* **💰 Benefício:** Redução de custos de até **90%** em comparação às instâncias comuns (on-demand), ideal para tarefas de processamento em lote que podem ser reiniciadas.

---

## 🏁 Conclusão
A implementação desses serviços projeta uma redução drástica nos gastos operacionais. Ao adotar o modelo *pay-as-you-go* (pagamento por uso), eliminamos a subutilização de hardware e aumentamos a produtividade. Recomendamos a exploração futura do **AWS Lambda** para tornar a arquitetura ainda mais eficiente e econômica.

---

## 🔗 Anexos e Referências
Abaixo, os documentos de apoio para a sustentação técnica do projeto:

* 📖 [Manual de políticas de ciclo de vida do Amazon S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/object-lifecycle-mgmt.html)
* 📊 [Dashboard de monitoramento de custos (AWS Cost Explorer)](https://aws.amazon.com/pt/aws-cost-management/aws-cost-explorer/)
* 💡 [Guia de boas práticas para instâncias Spot](https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/spot-best-practices.html)

---

**Assinatura:**

🖋️ **Denis Silva** *Arquiteto de Soluções Cloud*
