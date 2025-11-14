# CVLaunch: Relatório de Desenvolvimento de Projeto

Este documento detalha o planejamento, metodologia e resultados do projeto **CVLaunch**, um gerador de currículos online desenvolvido como parte de uma atividade acadêmica.

## 1. Planejamento e Análise

### 1.1. Planejamento da Aplicação
O objetivo do CVLaunch é simplificar o processo de criação de currículos. A plataforma oferece templates customizáveis, preenchimento guiado de informações e integração com Inteligência Artificial para otimizar o conteúdo para vagas específicas.

### 1.2. Mapeamento das Tarefas
O desenvolvimento foi dividido nas seguintes frentes:
- **Frontend:** Criação da interface do usuário com Next.js, React e Tailwind CSS.
- **Backend:** Desenvolvimento da API para gerenciamento de dados do usuário e currículos, utilizando Next.js API Routes.
- **Banco de Dados:** Modelagem e gerenciamento do banco de dados com Drizzle ORM.
- **Autenticação:** Implementação de login/cadastro de usuários com NextAuth.js.
- **Integração com IA:** Conexão com a API da OpenAI para geração e otimização de texto.
- **Deploy:** Configuração de ambiente para deploy contínuo na Vercel.

### 1.3. Análise de Dados, Local e Público-Alvo
- **Processo Atual (Problema):** Tradicionalmente, a criação de currículos envolve editores de texto genéricos, o que frequentemente resulta em inconsistências de formatação e dificuldade de personalização rápida.
- **Público-Alvo:** Profissionais em busca de novas oportunidades, estudantes, recém-formados e qualquer pessoa que deseje ter um currículo profissional e bem estruturado.
- **Local:** A aplicação é uma plataforma web, acessível globalmente através de qualquer navegador com acesso à internet.

## 2. Metodologia

Nesta seção, seria apresentado o cronograma e as fases do projeto.

*<ins>Nota: Inserir aqui o diagrama com as fases e o cronograma detalhado do projeto, conforme solicitado.</ins>*

## 3. Resultados Esperados/Obtidos

O projeto resultou em uma aplicação web funcional onde os usuários podem se cadastrar, criar múltiplos currículos a partir de templates, personalizá-los e fazer o download em formato PDF.

Conforme a recomendação, o código-fonte do projeto está armazenado em um repositório Git. Isso facilita a organização, o versionamento e a revisão do conteúdo. Para consultar o código, acesse o link do repositório.

## 4. Evolução do Projeto (Atividade Extensionista II)

Como o desenvolvimento inicial foi concluído, a próxima fase (Atividade Extensionista II) focará na evolução do projeto. Os seguintes pontos serão abordados:
- Expansão da biblioteca de templates de currículos.
- Melhorias nas funcionalidades de IA, como a análise de descrições de vagas para customizar o currículo.
- Implementação de novas opções de exportação.
- Coleta de feedback dos usuários para refinar a experiência e guiar futuras iterações.