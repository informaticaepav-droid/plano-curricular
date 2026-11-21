# plano-curricular

**Planeamento curricular e design pedagógico para o/a Técnico/a de Sistemas de Computação e Redes (481RA118)**

---

## 1. Descrição geral

Esta *skill* apoia o planeamento de uma **Unidade de Competência (UC)** ou de uma **UFCD** da qualificação profissional portuguesa **Técnico/a de Sistemas de Computação e Redes** (código de referência da qualificação: **481RA118**).

A partir do código e do nome da UC, da carga horária e do referencial oficial, a *skill* produz:

- um **plano pedagógico em Word editável**, organizado em blocos de 45 minutos;
- um **ficheiro Word com as rubricas de avaliação** correspondentes.

> **Nota sobre a sigla UC:** no referencial desta qualificação, UC significa *Unidade de Competência* (por exemplo, UC00639). Uma UFCD é uma *Unidade de Formação de Curta Duração*, com o seu próprio código.

---

## 2. O que a skill faz

- Pede o **código e o nome da UC/UFCD** antes de gerar qualquer plano, e a carga horária se esta faltar.
- Procura o **conteúdo oficial** no Catálogo Nacional de Qualificações (CNQ/ANQEP) e no Boletim do Trabalho e Emprego (BTE), quando a plataforma permite pesquisa, e **nunca inventa** resultados de aprendizagem, conteúdos ou cargas horárias oficiais.
- Converte a carga horária em minutos e em **blocos de 45 minutos**, mostra o valor exato e explica o resto, mantendo sempre o total oficial.
- Constrói um **cronograma por módulos** com temas, objetivos operacionais (verbos da taxonomia de Bloom), metodologias ativas e evidências de avaliação.
- Propõe a **matriz de recursos**, um **modelo de avaliação** (com pesos justificados) e a **diferenciação pedagógica**.
- Gera **rubricas** para cada instrumento de avaliação do plano.
- Termina com uma **secção de verificação**: soma das sessões, uso correto dos códigos e lista de pressupostos a validar.
- Inclui as **precauções de segurança e de proteção de dados** adequadas ao tipo de atividade.
- **Usa só o conteúdo da UC indicada**, sem importar conteúdos de outras UC. Cada pedido gera um plano para uma UC.

---

## 3. Como utilizar

### 3.1. Dados a fornecer

| Dado | Obrigatório | Observações |
| :--- | :--- | :--- |
| Código da UC/UFCD | Sim | Por exemplo, `UC00639` |
| Nome da Unidade de Competência (ou UFCD) | Sim | Por exemplo, *Orçamentar intervenções técnicas* |
| Carga horária em horas (ou minutos) | Sim | Os **pontos de crédito não são horas** e nunca são convertidos por suposição |
| Documentos de referência, recursos do laboratório, tamanho da turma | Opcional | Melhoram o ajuste do plano |

Se faltar o código ou o nome, a *skill* pede ambos numa única pergunta, juntamente com a carga horária, se também faltar. Se o código e o nome não corresponderem entre si ou ao referencial, a *skill* pede confirmação.

### 3.2. Exemplos reais de pedido

**Exemplo 1 – pedido completo**

> Entrada: "Plano da UC00639 Orçamentar intervenções técnicas, 25 horas."
>
> Resultado: 25 h = 1 500 min = 33,33 blocos. Propõe 33 blocos completos (1 485 min) mais uma sessão final de 15 min. Entrega o plano e as rubricas em Word.

**Exemplo 2 – carga horária em pontos de crédito**

> Entrada: "Plano da UC00627 Instalar e configurar servidores Web."
>
> Resultado: a *skill* encontra a UC no referencial, vê que só tem pontos de crédito (2,25) e pergunta a carga horária em horas, em vez de a estimar. Depois de a confirmar (25 h), gera o plano.

**Exemplo 3 – UC com forte componente técnica**

> Entrada: "Plano da UC02844 Gerir e manter as redes, 50 horas."
>
> Resultado: 50 h = 3 000 min = 66,67 blocos. Propõe 66 blocos completos (2 970 min) mais uma sessão final de 30 min. Reforça a segurança de laboratório (ambiente isolado, ponto de restauro, procedimento de recuperação, dados fictícios).

**Exemplo 4 – pedido de diferenciação**

> Entrada: "O grupo tem níveis muito diferentes; preciso de estratégias de apoio e de extensão."
>
> Resultado: secção de diferenciação com apoio (guiões e laboratórios parcialmente configurados), aprendizagem entre pares, desafios de extensão e remediação. A *skill* não assume necessidades individuais que não tenham sido indicadas.

### 3.3. Pedidos de formato

- O formato padrão é **Word editável**: um ficheiro com o plano e outro com as rubricas.
- Se pedir outro formato (Markdown, PDF ou texto no chat), a *skill* segue o pedido.
- Se a plataforma não conseguir criar ficheiros Word, a *skill* avisa e entrega o conteúdo em Markdown, pronto a colar no Word.

---

## 4. O que é entregue

### 4.1. Plano pedagógico (Word)

1. **Ficha técnica:** qualificação, referência 481RA118, UC e código, pontos de crédito (quando existem), carga horária, equivalência em blocos, distribuição proposta e fonte oficial.
2. **Contexto e resultados de aprendizagem:** realizações, critérios de desempenho e aptidões oficiais, distintos dos objetivos operacionais sugeridos.
3. **Cronograma pedagógico** (tabela de seis colunas, em página horizontal): módulo, blocos, temas, objetivos, metodologia e evidência.
4. **Matriz de recursos:** essenciais e opcionais, sem assumir disponibilidade.
5. **Avaliação das aprendizagens:** tabela de instrumentos, tipo, pesos sugeridos (a somar 100%) e justificação.
6. **Segurança, proteção de dados e boas práticas.**
7. **Diferenciação e apoio pedagógico.**
8. **Verificação do plano:** soma das sessões, códigos e pressupostos a validar.

### 4.2. Rubricas (Word)

Uma rubrica por instrumento de avaliação do plano (por exemplo, fichas e laboratórios, projeto, prova prática e observação), com quatro níveis qualitativos: *Não atingido*, *Parcialmente atingido*, *Atingido* e *Superado*. A escala é uma proposta e não uma escala oficial. A conversão em classificações e as notas mínimas ficam para o regulamento da entidade formadora.

---

## 5. Cálculo de blocos de 45 minutos

| Passo | Fórmula | Exemplo (50 h) | Exemplo (25 h) |
| :--- | :--- | :--- | :--- |
| Minutos totais | horas × 60 | 3 000 | 1 500 |
| Blocos exatos | minutos ÷ 45 | 66,67 | 33,33 |
| Distribuição proposta | blocos completos + sessão curta | 66 blocos + 30 min | 33 blocos + 15 min |

A *skill* nunca arredonda a carga horária oficial sem o dizer e verifica que a soma das sessões coincide com o total. Se o utilizador indicar outra duração de sessão, a *skill* adapta a unidade de planeamento e mantém a rastreabilidade da carga horária oficial.

---

## 6. Avaliação

Os pesos de avaliação são sempre **propostas justificadas**, nunca valores fixos nem requisitos oficiais. Dependem da UC. Nos testes feitos com UC de natureza prática, por exemplo, a *skill* propôs cerca de 75% do peso em produtos demonstráveis, 15% num teste escrito e 10% em atitudes, sempre com justificação e a somar 100%.

Cada instrumento tem uma rubrica, e as rubricas avaliam também a segurança do processo e a capacidade de explicar decisões, não só o resultado final. A *skill* assinala no plano quando o tempo de uma tarefa sumativa é curto e propõe uma distribuição alternativa.

---

## 7. Segurança e proteção de dados

A *skill* aplica as precauções **consoante o tipo de atividade**:

- **Sempre:** proteção de dados e RGPD, uso de dados e contas fictícios, uso responsável e autorizado de sistemas, postura ergonómica.
- **Atividades com configuração, redes ou segurança:** laboratório isolado e autorizado (por exemplo, máquinas virtuais numa rede fechada), sem testes sobre a rede da escola, da Internet ou de terceiros; ponto de restauro ou cópia antes de operações com risco; procedimento de recuperação e resultado esperado explicados antes do laboratório.
- **Manuseamento de equipamento físico:** descarga eletrostática (ESD), isolamento da alimentação e organização da cablagem.
- **UC só de simulação ou de gestão:** as precauções de hardware não se aplicam e são omitidas.

A *skill* não afirma que uma atividade foi realizada ou verificada sem evidência.

---

## 8. Política de linguagem

- Respostas e documentos em **português europeu (PT-PT)**, por defeito, com a ortografia do **Acordo Ortográfico de 1990** usada em Portugal. Se o utilizador pedir outra língua de forma explícita, a *skill* segue o pedido.
- Terminologia preferida: *ficheiro*, *ecrã*, *utilizador*, *palavra-passe*, *rede informática*, *sistema operativo*, *avaliação formativa*, *avaliação sumativa*, *formando*, *folha de cálculo*.
- Evita o português do Brasil: *arquivo* → *ficheiro*, *tela* → *ecrã*, *usuário* → *utilizador*, *senha* → *palavra-passe*, *planilha* → *folha de cálculo*, *aluno* (na formação profissional) → *formando*.
- Preserva nomes oficiais, códigos, siglas e comandos técnicos.

---

## 9. Estrutura de ficheiros

```text
plano-curricular/
├── SKILL.md      (instruções da skill, em inglês, com resposta em PT-PT)
└── README.md     (esta documentação)
```

A pasta deve chamar-se `plano-curricular`, igual ao campo `name` do `SKILL.md`. O nome só pode ter minúsculas, números e hífenes.

---

## 10. Compatibilidade e requisitos

- Estrutura **Agent Skills**: `SKILL.md` com cabeçalho YAML (`name`, `description`) seguido de instruções em Markdown.
- Não precisa de *scripts* nem de pacotes externos.
- **Pesquisa na web** (opcional): usada para localizar o referencial oficial quando a plataforma a permite.
- **Criação de ficheiros Word:** depende das ferramentas de criação de ficheiros da plataforma. Se não existirem, a *skill* entrega o conteúdo em Markdown, pronto a colar no Word.
- Em plataformas que não carregam *skills*, cole o corpo do `SKILL.md` (sem o cabeçalho YAML) no campo de instruções personalizadas.
- O funcionamento do carregamento de *skills* e a geração de ficheiros dependem da aplicação anfitriã. Confirme o comportamento na documentação de cada ferramenta.

---

## 11. Perguntas frequentes

**O código 481RA118 é o código de uma UC?**
Não. É o código de referência da qualificação *Técnico/a de Sistemas de Computação e Redes*. Cada UC e cada UFCD tem o seu próprio código (por exemplo, UC00639).

**A *skill* planeia várias UC de uma só vez?**
Não. Cada pedido gera um plano para uma UC, usando apenas o conteúdo dessa UC. Para várias UC, peça um plano por UC.

**Qual é a duração padrão de uma sessão?**
O bloco de 45 minutos. Se o utilizador indicar outra duração, a *skill* adapta a unidade de planeamento e mantém o total oficial.

**E se o referencial só indicar pontos de crédito?**
A *skill* pergunta a carga horária em horas. Os pontos de crédito não se convertem em horas por suposição.

**A *skill* assume que tenho determinado software ou equipamento?**
Não. Indica o que é essencial e o que é opcional e assinala o que deve ser confirmado pela entidade formadora, incluindo licenciamento.

**Os pesos de avaliação são oficiais?**
Não. São propostas justificadas, que devem ser alinhadas com o regulamento da entidade formadora.

**Que garantias dá sobre o conteúdo oficial?**
A *skill* usa as fontes oficiais que conseguir consultar (CNQ/ANQEP e BTE) e indica a fonte no plano. Quando não consegue localizar ou confirmar uma fonte, diz-o claramente em vez de inventar conteúdos.

**O plano é entregue em que formato?**
Em Word editável (plano e rubricas). Outros formatos podem ser pedidos.

---

## 12. Qualidade

Antes de entregar, a *skill* percorre uma lista de controlo de **18 pontos**, que inclui:

- língua e ortografia em PT-PT;
- nome da qualificação e códigos corretos (481RA118 como código da qualificação, nunca da UC);
- código e nome da UC fornecidos ou confirmados, e uso exclusivo do conteúdo dessa UC;
- origem da carga horária (utilizador ou fonte oficial) e pontos de crédito não tratados como horas;
- soma das sessões igual à carga horária, ou discrepância explicada;
- objetivos observáveis, avaliação e recursos coerentes, e rubricas para todos os instrumentos;
- precauções de segurança e proteção de dados adequadas;
- ficheiros Word verificados (orientação, tabelas e totais), ou limites da verificação indicados;
- mensagem final curta, com as propostas e os pressupostos a confirmar.

---

## 13. Limitações

- É uma ferramenta de apoio e não substitui o parecer técnico nem a supervisão pedagógica do formador.
- A distribuição por módulos, os pesos de avaliação, o software e os valores de referência são **propostas** e vêm assinalados como tal em cada plano.
- Os dados dos referenciais devem ser confirmados nas fontes oficiais, que podem ter sido atualizadas.

---

## 14. Versões

### v1.1.0 (31 de outubro de 2026)
- Alinhamento do README com a skill final.
- Código e nome da UC passam a ser obrigatórios no início do pedido.
- Regra dos pontos de crédito (não são horas).
- Saída padrão em Word editável, com ficheiro de rubricas.
- Verificação do plano, segurança adaptada à atividade, âmbito de uma UC por pedido e política de ortografia AO90.
- Checklist de 18 pontos.

### v1.0.0 (29 de outubro de 2026)
- Versão inicial.

---

## 15. Autor e licença

=======
- **Autor / contacto:** António Baptista / abaptista@zonmail.pt
- **Licença:** MIT License
>>>>>>> ad18bdbf14558f81060e71b41dda30b70dc528aa
