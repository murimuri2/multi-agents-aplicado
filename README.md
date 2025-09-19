# multi-agents-aplicado
Lucas é um assistente multi-agente em Python que utiliza LangChain, LangGraph e FastAPI. O projeto explora arquiteturas de IA distribuídas, roteamento inteligente de mensagens e integração com ferramentas externas, permitindo conversas naturais e execução automatizada de tarefas em um sistema modular e expansível.
Lucas – Assistente Multi-Agente com Inteligência Artificial

O Lucas é um projeto desenvolvido como parte de estudos em Inteligência Artificial aplicada a sistemas conversacionais. Ele adota uma arquitetura multi-agente construída em Python, com apoio das bibliotecas LangChain, LangGraph e FastAPI. O objetivo central é investigar como múltiplos agentes podem cooperar de forma organizada, compartilhar responsabilidades e produzir respostas que unam linguagem natural e execução de tarefas automatizadas.

O sistema é estruturado em agentes independentes, cada um responsável por funções específicas. Um agente atua como roteador de mensagens, analisando cada entrada e decidindo se deve responder de maneira direta ou acionar outro agente ou ferramenta externa. Outros agentes lidam com acesso a banco de dados, gerenciamento de lembretes, consulta de informações e integração com serviços adicionais. Essa divisão facilita a manutenção e torna a arquitetura expansível, já que novos módulos podem ser adicionados sem comprometer a lógica existente.

Entre as funcionalidades já implementadas estão: roteamento inteligente de diálogos, integração com ferramentas externas como previsão do tempo, lembretes e manipulação de dados, além de uma interface em terminal que simula escrita progressiva, criando uma interação mais próxima da conversa humana.

A motivação do projeto é dupla: por um lado, oferecer um ambiente prático de experimentação para testar ajustes de parâmetros de modelos de linguagem, como temperature e num_predict; por outro, fornecer uma base acadêmica para estudar coordenação entre múltiplas inteligências artificiais. O projeto busca unir teoria e prática, permitindo tanto reflexões científicas quanto aplicações reais em sistemas de apoio, assistentes digitais e automação de processos.
