# 🤖 Agent-Zero no GitHub Codespaces
Este repositório permite que você execute e experimente com o Agent-Zero instantaneamente no GitHub Codespaces, sem configurações locais.

# 🚀 Visão Geral
O Agent-Zero é um agente de IA experimental focado em automação de tarefas e execução de código. Ele opera com base em prompts e funções definidas no código, usando LLMs para planejar e executar ações. Este repositório oferece um ambiente pré-configurado para que você possa explorar suas capacidades sem esforço.

# ✨ Como Usar
1. Iniciar seu Codespace
A maneira mais rápida é clicar no botão "Code" no GitHub e selecionar "Open with Codespaces". O Codespace será provisionado automaticamente com todas as dependências.

2. Configuração de Chave de API
Para a maioria dos modelos de LLM, você precisará de uma chave de API (e.g., OpenAI).

Recomendado: Adicione sua chave como um Codespace Secret. Vá em Settings (Ctrl+, ou Cmd+,), procure por "Codespaces" e adicione o segredo, por exemplo, OPENAI_API_KEY.

Temporário no Terminal: export OPENAI_API_KEY="sua_chave_aqui"

3. Executar o Agent-Zero
Abra o terminal no seu Codespace e execute o script principal:

Bash

python3 agent_zero.py
O agente começará a operar e você verá a saída no terminal.

# 📁 Estrutura Essencial
agent_zero.py: O código principal do Agent-Zero.

prompts/: Contém os prompts usados pelo agente para diferentes funções.

.devcontainer/: Configurações para o ambiente do Codespaces.

requirements.txt: Dependências Python do projeto.

# 🤝 Contribuição
Sinta-se à vontade para abrir Issues ou Pull Requests para melhorias!

# 📜 Licença
Este projeto está sob a Licença MIT.
