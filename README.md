# Agente_Literario
O Agente Literário é um assistente inteligente projetado para transformar a experiência de leitura através de personalização profunda. Utilizando modelos de linguagem de última geração, o sistema atua como um gerenciador, recomendador e guia de estudos, ajudando usuários a encontrar a obra perfeita e a manter a constância em seus planos de leitura.
# Instalação e Execução
Siga os passos abaixo para configurar o ambiente de desenvolvimento e executar o Agente Literário localmente:
1. Pré-requisitos / 
Certifique-se de ter instalado em sua máquina:
Node.js (versão 18 ou superior).
Um gerenciador de pacotes como npm, yarn ou pnpm.
2. Clonar o Repositório / 
git clone https://github.com/seu-usuario/agente-literario.git
cd agente-literario
4. Instalar Dependências / 
Utilize o comando abaixo para instalar as bibliotecas necessárias, incluindo Next.js, Radix UI (Shadcn) e as SDKs das APIs:
npm install
ou
yarn install
4. Configurar Variáveis de Ambiente / 
Crie um arquivo .env.local na raiz do projeto e adicione suas chaves de API para o funcionamento do modelo Llama e busca de livros:
GROQ_API_KEY=sua_chave_aqui
GOOGLE_BOOKS_API_KEY=sua_chave_aqui
5. Executar o Projeto / 
Inicie o servidor de desenvolvimento:
npm run dev
ou
yarn dev
Após o comando, a aplicação estará disponível em http://localhost:3000.
# Proposta do Projeto 
Desenvolver um ecossistema integrado que utiliza LLMs para interpretar os gostos do usuário e oferecer uma jornada literária fluida, desde a descoberta até a aquisição da obra.
Gerenciamento de Leitura: Acompanhamento de progresso (páginas lidas, porcentagem concluída) e marcadores de avanço.
Recomendação Personalizada: Sugestões baseadas em linguagem natural, interesses específicos e nível de complexidade.
Planos de Estudo: Criação de guias detalhados para fins acadêmicos ou de lazer.Integração de Compra: Redirecionamento direto para o Google Play para aquisição de livros.
# Tecnologias Utilizadas
O projeto utiliza um stack moderno focado em performance e tipagem forte. 
Framework: Next.js 14+ (Full-stack React). 
IA/LLM: Groq API utilizando o modelo Llama 3.1 8B Instant. 
Fonte de Dados: Google Books API. 
Linguagem: TypeScript para maior robustez do código. 
Estado Global: React Context API. 
Interface: Shadcn UI para componentes reutilizáveis.
# Inteligência e UXA aplicação se destaca pelo uso de IA para melhorar a experiência do usuário (UX)
Compreensão de Linguagem Natural: Interpreta consultas complexas sem sintaxe rígida. 
Inferência de Contexto: Reduz erros ao validar intenções em consultas ambíguas. 
Engajamento: Gera explicações personalizadas que justificam cada recomendação, aumentando a confiança do usuário.
Extração de Termos: Capacidade avançada de processar mensagens e extrair termos relevantes para busca.
# Equipe 
Cleiton Andrade 
Henrique Nogueira 
Geovani Lima 
Adriana Rocha Sousa 
Nayara Letycia Lima 
Lucca P. Bordin 
