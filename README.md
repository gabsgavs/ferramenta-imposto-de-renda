# 📊 Ferramenta de Controle e Organização para Imposto de Renda

Projeto desenvolvido como parte do portfólio de modelagem e automação em Excel. Esta ferramenta tem como objetivo atuar como um agregador de dados centralizado, permitindo ao contribuinte organizar informações pessoais, informes de rendimentos bancários e extratos de receitas de maneira validada e estruturada para facilitar o preenchimento da declaração de Imposto de Renda.

---

## 🔍 1. Estrutura e Funcionalidades da Ferramenta

A planilha foi desenvolvida dividindo as informações em abas estratégicas para garantir navegação fluida e integridade dos dados:

1. **Aba `TITULAR` (Dados Cadastrais):**
   * Concentra as informações essenciais da pessoa física (Nome, CPF, Data de Nascimento, Título de Eleitor, Cônjuge, Endereço completo, CEP, Contatos e marcações de controle como alterações em relação à entrega anterior).
2. **Aba `INFORMES` (Rendimentos Bancários):**
   * Agrega os saldos e valores atuais de diferentes instituições financeiras, utilizando listas suspensas validadas (com base na listagem oficial de bancos) e campos para anexos de comprovantes em PDF (`.pdf`).
   * **Soma Automatizada:** Conta com fórmula de soma (`=SUM(...)`) na célula `C7` para totalizar o patrimônio/rendimentos informados.
3. **Aba `NOTAS` (Entradas e Holerites):**
   * Controla o fluxo de entradas mês a mês (datas, categorias como holerites e valores recebidos).

---

## ⚙️ 2. Validações de Dados e Recursos Técnicos Utilizados

* **Validação de Dados (Listas Suspensas):** Utilizadas na seleção dos bancos na aba `INFORMES`, apontando diretamente para a tabela de referência, o que evita erros de digitação e padroniza os dados.
* **Funções Matemáticas e de Agregação:** Uso da função `SOMA` (`SUM`) para consolidar dinamicamente os valores de rendimentos e saldos bancários.
* **Organização Modular:** Estruturação limpa com separação entre dados do contribuinte, consolidação bancária e controle de receitas mensais.

---

## 📸 Capturas de Tela da Ferramenta

* **Visão Geral - Dados do Titular:** 
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/717fa6d2-674b-4346-ac65-25efafd5eec7" />

* **Visão Geral - Informes Bancários:** 
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/860a5992-84f4-4fe3-8758-0608a273db84" />


---

### 💡 Checklist de Verificação Antes de Submeter:
- [x] Planilha aberta sem erros de fórmula.
- [x] Dados de exemplo preenchidos corretamente (sem expor dados sensíveis reais desnecessários).
- [x] Repositório público no GitHub com nome legível (`ferramenta-imposto-de-renda`).
- [x] Arquivo `README.md` detalhado anexado.
