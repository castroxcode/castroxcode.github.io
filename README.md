<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currículo - Thiago de Castro Ferreira</title>
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #34495e;
            --accent-color: #3498db;
            --text-color: #333;
            --bg-color: #f4f7f6;
            --white: #ffffff;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            padding: 20px;
            line-height: 1.6;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background-color: var(--white);
            padding: 40px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            border-radius: 8px;
        }

        header {
            text-align: center;
            border-bottom: 2px solid var(--accent-color);
            padding-bottom: 20px;
            margin-bottom: 30px;
        }

        h1 {
            color: var(--primary-color);
            margin: 0;
            font-size: 2.5em;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .subtitle {
            color: var(--primary-color);
            font-size: 1.2em;
            font-weight: bold;
            margin-top: 5px;
        }

        .contact-info {
            margin-top: 15px;
            font-size: 0.9em;
            color: var(--secondary-color);
        }

        .contact-info a {
            color: var(--accent-color);
            text-decoration: none;
        }

        section {
            margin-bottom: 30px;
        }

        h2 {
            color: var(--primary-color);
            border-left: 5px solid var(--accent-color);
            padding-left: 15px;
            font-size: 1.5em;
            text-transform: uppercase;
            margin-bottom: 15px;
            background-color: #f9f9f9;
            padding-top: 5px;
            padding-bottom: 5px;
        }

        .summary p {
            text-align: justify;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 15px;
        }

        .skill-category {
            background-color: #f9f9f9;
            padding: 10px;
            border-radius: 4px;
        }

        .skill-category strong {
            display: block;
            color: var(--secondary-color);
            margin-bottom: 5px;
        }

        .experience-item, .project-item {
            margin-bottom: 20px;
        }

        .project-details {
            padding-left: 20px;
            border-left: 3px solid #ececec;
        }

        .project-details p {
            margin: 5px 0;
        }

        .project-details .project-link {
            margin-top: 3px;
        }

        .item-header {
            display: flex;
            justify-content: space-between;
            font-weight: bold;
            color: var(--primary-color);
        }

        .item-tech {
            font-style: italic;
            color: var(--accent-color);
            font-size: 0.9em;
            margin-top: 5px;
        }

        .project-link {
            font-size: 0.9em;
            margin-top: 5px;
        }

        ul {
            margin-top: 5px;
            padding-left: 20px;
        }

        .education-item {
            margin-bottom: 10px;
        }

        footer {
            text-align: center;
            font-size: 0.8em;
            color: #777;
            margin-top: 40px;
            border-top: 1px solid #eee;
            padding-top: 20px;
        }

        @media print {
            body {
                background-color: var(--white);
                padding: 0;
                -webkit-print-color-adjust: exact;
                print-color-adjust: exact;
            }
            .container {
                box-shadow: none;
                width: 100%;
                padding: 0;
            }
            .projects {
                page-break-before: always;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>THIAGO DE CASTRO FERREIRA</h1>
            <div class="subtitle">ANALISTA DE SISTEMAS</div>
            <div class="contact-info">
                castroxcode@gmail.com | (99) 98173-6333 | Imperatriz – MA
            </div>
            <div class="contact-info">
                <a href="https://www.linkedin.com/in/castroxcode">linkedin.com/in/castroxcode</a> | <a href="https://github.com/castroxcode">github.com/castroxcode</a>
            </div>
        </header>

        <section class="summary">
            <h2>Resumo Profissional</h2>
            <p>
                Analista de Sistemas com experiência em <strong>Java e Spring Boot</strong>, focado no desenvolvimento de aplicações escaláveis e na integração entre sistemas. Atuo com <strong>APIs REST</strong>, <strong>mensageria (RabbitMQ)</strong> e bancos de dados <strong>SQL Server e PostgreSQL</strong>, garantindo performance e confiabilidade nas soluções entregues. No frontend, trabalho com <strong>Vue.js</strong> e <strong>React</strong>, construindo interfaces funcionais e responsivas. Possuo vivência com <strong>Elasticsearch</strong>, <strong>Docker</strong> e ambientes Linux em produção. Formado em Sistemas de Informação com pós-graduação em Engenharia de Software, meu foco é transformar regras de negócio complexas em sistemas bem estruturados, automatizando processos e reduzindo retrabalho operacional.
            </p>
        </section>

        <section class="skills">
            <h2>Competências Técnicas</h2>
            <div class="skills-grid">
                <div class="skill-category">
                    <strong>Backend & Frameworks</strong>
                    Java, Spring Boot, Python, LangChain, Next.js
                </div>
                <div class="skill-category">
                    <strong>Frontend</strong>
                    Vue.js, React, TypeScript, Tailwind CSS
                </div>
                <div class="skill-category">
                    <strong>Banco de Dados</strong>
                    PostgreSQL, Microsoft SQL Server, Redis
                </div>
                <div class="skill-category">
                    <strong>APIs & Mensageria</strong>
                    APIs REST, RabbitMQ
                </div>
                <div class="skill-category">
                    <strong>DevOps & Busca</strong>
                    Linux, Docker, GitHub, Elasticsearch
                </div>
                <div class="skill-category">
                    <strong>Outras Ferramentas</strong>
                    Visual Studio Code, Supabase, Figma
                </div>
            </div>
        </section>

 
        <section class="experience">
            <h2>Experiência Profissional</h2>
            <div class="experience-item">
                <div class="item-header">
                    <span>Desenvolvedor Full Stack / Analista de Sistemas (2015 – Presente)</span>
                </div>

                <p>
                    Desenvolvimento de sistemas web e soluções para automação de processos,
                    atuando desde o levantamento de requisitos até a implantação e manutenção
                    de aplicações, com foco em performance, escalabilidade e integração entre sistemas.
                </p>

                <ul>
                    <li>Construção e consumo de <strong>APIs REST</strong> para integração entre sistemas, CRMs, serviços externos e plataformas de terceiros.</li>
                    <li>Modelagem e manutenção de bancos de dados <strong>PostgreSQL</strong>, incluindo consultas, otimização e estruturação de dados.</li>
                    <li>Desenvolvimento de sistemas corporativos para gestão comercial, controle de estoque, vendas e automação de processos.</li>
                    <li>Implantação de aplicações em Docker, utilização de Git e acompanhamento de todo o ciclo de desenvolvimento.</li>
                </ul>
            </div>
        </section>


        <section class="projects">
            <h2>Projetos Relevantes</h2>
            <div class="project-item">
                <div class="item-header">
                    <span>IA Escala — Plataforma SaaS de Inteligência Artificial</span> 
                </div>
                <div class="project-details">
                    <div class="item-tech">Vue.js, React, TypeScript, Tailwind, Python, Supabase</div>
                    <p>Plataforma completa para atendimento ao cliente e CRM com automação operacional. Integra chat estilo WhatsApp (API Oficial/Não Oficial), agenda, pipeline comercial, base de conhecimento com RAG, controle de acesso RBAC e painel de observabilidade de agentes.</p>
                    <div class="project-link">🔗 <a href="https://iaescala.com.br">iaescala.com.br</a></div>
                </div>
            </div>
            <div class="project-item">
                <div class="item-header">
                    <span>AgendaIN — Gestão de Clínicas e Salões</span>
                </div>
                <div class="project-details">
                    <div class="item-tech">React, TypeScript, Vite, Tailwind, Supabase</div>
                    <p>Sistema SaaS web multi-tenant de gestão completa. Inclui agenda visual com status por cor, PDV, controle de caixa, fichas de anamnese personalizáveis, gestão de comissões, financeiro, integração com WhatsApp para lembretes e API pública.</p>
                    <div class="project-link">🔗 <a href="https://agendain.com.br">agendain.com.br</a></div>
                </div>
            </div>
            <div class="project-item">
                <div class="item-header">
                    <span>Djuju Moda - Controle de Estoque</span>
                </div>
                <div class="project-details">
                    <div class="item-tech">React, TypeScript, Tailwind, Supabase</div>
                    <p>Sistema focado na otimização de controle de estoque, compras, transferências e vendas, fornecendo visão analítica detalhada do negócio.</p>
                    <div class="project-link">🔗 <a href="https://djuju.egestor.pro">djuju.egestor.pro</a></div>
                </div>
            </div>
            <div class="project-item">
                <div class="item-header">
                    <span>RR Calçados — Gestão Loja de Calçados</span>
                </div>
                <div class="project-details">
                    <div class="item-tech">React, TypeScript, Tailwind, Supabase</div>
                    <p>Sistema SaaS web multi-tenant de gestão completa. Inclui agenda visual com status por cor, PDV, controle de caixa, fichas de anamnese personalizáveis, gestão de comissões, financeiro, integração com WhatsApp para lembretes e API pública.</p>
                    <div class="project-link">🔗 <a href="https://rogerio.egestor.pro">rogerio.egestor.pro</a></div>
                </div>
            </div>
            <div class="project-item">
                <div class="item-header">
                    <span>Transmar — Site Institucional para Tranportadora</span>
                </div>
                <div class="project-details">
                    <div class="item-tech">HTML, CSS, Javacript</div>
                    <p>Site institucional para a Transportadora Transmar com foco em alta performance, responsividade e conversão de leads.</p>
                    <div class="project-link">🔗 <a href="https://transportadoratransmar.com.br">transportadoratransmar.com.br</a></div>
                </div>
            </div>
        </section>

        <section class="education">
            <h2>Formação Acadêmica</h2>
            <div class="education-item">
                <strong>Bacharel em Sistemas de Informação</strong>
                <div class="item-tech">Faculdade Facimp</div>
            </div>
            <div class="education-item">
                <strong>MBA em Empreendedorismo e Criação de Startups</strong>
                <div class="item-tech">Faculdade Unyleya</div>
            </div>
            <div class="education-item">
                <strong>Pós-graduação em Engenharia de Software</strong>
                <div class="item-tech">Faculdade Focus</div>
            </div>            
        </section>

        <section class="additional">
            <h2>Informações Adicionais</h2>
            <ul>
                <li>Disponibilidade imediata para trabalho <strong>Presencial, Híbrido ou Home Office</strong>.</li>
                <li>Perfil adaptável a novas tecnologias e metodologias ágeis.</li>
            </ul>
        </section>

    </div>
</body>
</html>
