🚀 FinEdu AI - Gestão Financeira com IA
O FinEdu AI é uma plataforma Full-stack de gestão financeira pessoal e educação para investimentos. O projeto foi arquitetado para simular um produto real de mercado (fintech), unindo organização financeira, visualização de dados e inteligência artificial.

🌟 Destaques do Projeto
Arquitetura Empresarial: Divisão clara entre camadas (UI, Regras de Negócio, API e Banco de Dados), utilizando o App Router do Next.js.

Gestão de Dados: Sistema completo de CRUD para receitas e despesas, com cálculos automáticos de saldo e percentual de comprometimento de renda.

Dashboards Interativos: Visualização de métricas e evolução financeira através de gráficos dinâmicos com Recharts.

Chatbot Educativo: Interface de chat para suporte financeiro, preparada para integração com a API da OpenAI.

Segurança Avançada: Autenticação robusta com JWT em cookies HttpOnly, senhas criptografadas com Bcrypt e validação de dados com Zod.

🛠️ Tecnologias Utilizadas
Frontend
Next.js 14 (App Router)

React & TypeScript

Tailwind CSS (Estilização responsiva)

Lucide React (Ícones)

Backend & Banco de Dados
Node.js com Next.js API Routes

Prisma ORM (Modelagem e consultas)

PostgreSQL (Banco de dados relacional via Docker)

JWT & Bcrypt (Segurança e Autenticação)

📁 Estrutura do Projeto
O projeto segue uma estrutura organizada para facilitar a manutenção e escalabilidade:

/src/app: Rotas e páginas da aplicação.

/src/api: Endpoints do backend.

/src/components: Componentes de UI reutilizáveis (Atomic Design).

/src/lib & /src/services: Lógica de negócio, serviços de IA e utilitários.

/prisma: Esquema do banco de dados e sementes (seeds) para teste.

🚀 Como Executar
Clonar e Instalar:

Bash
git clone https://github.com/VictorAlves747/finedu-ai.git
npm install
Ambiente:
Crie um arquivo .env com base no .env.example.

Banco de Dados (Docker):

Bash
docker compose up -d
npm run prisma:generate
npm run prisma:migrate -- --name init
Rodar:

Bash
npm run dev
👤 Autor
Victor Alves Rodrigues Braulino
🎓 Ciência da Computação - UNICID
LinkedIn | Portfólio
