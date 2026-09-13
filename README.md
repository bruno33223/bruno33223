<div align="center">

# Bruno Ribeiro
### **Engenheiro de Software Sênior & Engenheiro de Sistemas de IA**

<p align="center">
  <img src="https://img.shields.io/badge/Experi%C3%AAncia-Desde%202012-blue?style=flat-square&logo=clock" alt="Desde 2012" />
  <img src="https://img.shields.io/badge/Foco-Engenharia%20de%20IA%20%26%20Sistemas%20Nativos-orange?style=flat-square&logo=openai" alt="Foco IA & Sistemas" />
  <img src="https://img.shields.io/badge/Ambiente-Linux%20%26%20Cross--Platform-black?style=flat-square&logo=linux" alt="Linux" />
  <img src="https://img.shields.io/badge/Status-Dispon%C3%ADvel%20para%20Projetos-success?style=flat-square" alt="Status" />
</p>

<p align="center">
  <i>Construindo sistemas de alta performance, ferramentas de compilação/runtime e arquiteturas autônomas de agentes de IA com rigor técnico e foco em engenharia sem atalhos.</i>
</p>

---

</div>

## 👨‍💻 Sobre Mim

Atuando profissionalmente no desenvolvimento de software desde **2012**, acumulo mais de uma década de vivência prática acompanhando a evolução dos paradigmas da computação moderna — desde o desenvolvimento web e de sistemas desktop nativos até arquiteturas distribuídas e o estado da arte em **Engenharia de Sistemas de IA**.

- **Engenharia de IA & Agentes Autônomos**: Especialista em arquiteturas multiagentes orientadas a especificação (*Spec-Driven Development*), implementação de servidores e ferramentas no padrão **Model Context Protocol (MCP)**, indexação e análise sintática de código (AST), e loops de validação adversarial (*Gauntlet Loops / Harsh Critics*).
- **Engenharia de Baixo e Alto Nível (Poliglota)**: Experiência sólida em linguagens que exigem controle fino de memória, concorrência e tipagem estrita (**Rust**, **C# / .NET**, **C/C++**), combinada com agilidade no desenvolvimento de serviços assíncronos e APIs em **Python** e interfaces modernas e fluidas em **TypeScript** e **React**.
- **Filosofia de Engenharia**: Construção de software robusto, resiliente e escalável. Sem gambiarras ou soluções paliativas — priorizando sempre a melhor arquitetura técnica, telemetria em tempo real, segurança de tipos e contratos bem definidos.

---

## 🚀 Projetos em Destaque & Competências Técnicas

Abaixo estão três projetos autorais que sintetizam minhas competências em engenharia de sistemas, desenvolvimento de ferramentas desktop complexas e orquestração autônoma de inteligência artificial:

### 1. 🤖 [agent-cockpit](https://github.com/bruno33223/agent-cockpit) — *Mission Control & Orquestrador de Agentes Autônomos de IA*
> Central de comando e telemetria para frotas de agentes autônomos de IA integrados via Model Context Protocol (MCP).

* **Arquitetura Multiagente 3x3**: Governação de frotas operando em paralelo com agentes executores emparelhados com revisores adversariais (*Harsh Critics*), garantindo validação estrita antes de commits ou merges.
* **Servidor MCP Nativo**: Desenvolvimento de protocolo de comunicação JSON-RPC com gerenciamento de estado atômico, injeção cirúrgica de contexto e barramento de ferramentas (Tools & Resources).
* **Code Intelligence via AST**: Varredura automatizada da árvore sintática abstrata do código para análise de impacto de símbolos e geração de contexto sem saturação de tokens da LLM.
* **Telemetria em Tempo Real**: Pipeline assíncrono baseado em **FastAPI**, **WebSockets** e schemas **Pydantic** para monitoramento contínuo do ciclo de desenvolvimento, com integração nativa ao sistema operacional (Linux XDG Autostart).
* **Tecnologias**: `Python 3.11+` • `FastAPI` • `WebSockets` • `Model Context Protocol (MCP)` • `TypeScript` • `Pydantic` • `Linux XDG / Shell`

---

### 2. 🎮 [MonoGameMaker](https://github.com/bruno33223/MonoGameMaker) — *IDE & Orchestrator Code/AI-First para MonoGame*
> IDE desktop de alto desempenho projetada para delegar 100% da lógica e comportamento de entidades a código C# limpo gerado por desenvolvedores ou agentes de IA.

* **Dynamic Binary Hot Reload (.NET 8)**: Implementação de recarga dinâmica em tempo de execução utilizando `AssemblyLoadContext` customizado para carregar assemblies a partir de streams de bytes em memória. Elimina bloqueios físicos de arquivos no disco (*write locks*), permitindo compilações em background sem travamentos.
* **Live Tweaking via Reflection**: Inspeção em tempo real e mutação direta de campos, propriedades e variáveis das entidades durante a simulação por meio de uma interface Immediate Mode (**ImGui.NET**).
* **Sistemas Reativos e Thread Safety**: Cache reativo de arquivos baseado em `FileSystemWatcher` thread-safe com janela de debounce de 150ms e troca atômica por travamento de referências, evitando oscilações na taxa de quadros (*frame drops*).
* **P/Invoke & Interop de Baixo Nível**: Integração direta com `cimgui.dll` via P/Invoke para gerenciamento cirúrgico de layouts de janelas e docking nativo.
* **Tecnologias**: `C#` • `.NET 8` • `MonoGame` • `ImGui.NET` • `HLSL` • `P/Invoke Interop` • `JSON Schema`

---

### 3. 📋 [Linux-ClipBoard](https://github.com/bruno33223/Linux-ClipBoard) — *Gerenciador de Área de Transferência Nativo e Ultra-Leve*
> Utilitário desktop nativo publicado na **Snap Store**, com suporte a **AppImage** e **Deb**, otimizado para latência imperceptível e baixo consumo de memória.

* **Backend Nativo em Rust**: Construído sobre o **Tauri v2**, garantindo inicialização quase instantânea e consumo mínimo de RAM quando comparado a soluções baseadas em Electron.
* **Integração Profunda com o Desktop Linux**: Comportamento de instância única (*single-instance IPC*), minimização para a área de notificação (*System Tray*) e ativação dinâmica por atalho global de teclado (`Super+V`) com posicionamento seguindo o cursor.
* **Interface Moderna e Reativa**: Frontend desenvolvido em **React**, **TypeScript** e **TailwindCSS**, com reordenação de itens via arrastar e soltar (`@dnd-kit`), fixação de itens prioritários e persistência segura.
* **Automação de Build e Empacotamento**: Pipelines de CI/CD em GitHub Actions para compilação multiplataforma e publicação de pacotes `.snap`, `.deb` e `.AppImage`.
* **Tecnologias**: `Rust` • `Tauri v2` • `React 18` • `TypeScript` • `TailwindCSS` • `Linux GTK / WebKit` • `Snapcraft`

---

## 🛠️ Matriz de Habilidades & Tecnologias

### Linguagens & Core
<p>
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/Bash%20/%20Shell-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash" />
</p>

### Engenharia de IA & Sistemas de Agentes
<p>
  <img src="https://img.shields.io/badge/Model%20Context%20Protocol%20(MCP)-101828?style=flat-square&logo=anthropic&logoColor=white" alt="MCP" />
  <img src="https://img.shields.io/badge/Autonomous%20Agent%20Fleets-24292e?style=flat-square&logo=probot&logoColor=white" alt="Autonomous Agents" />
  <img src="https://img.shields.io/badge/Spec--Driven%20Development-0052CC?style=flat-square" alt="Spec-Driven" />
  <img src="https://img.shields.io/badge/AST%20Code%20Analysis-6f42c1?style=flat-square" alt="AST Analysis" />
  <img src="https://img.shields.io/badge/Adversarial%20Quality%20Gates%20(Gauntlet)-D9381E?style=flat-square" alt="Gauntlet Loop" />
  <img src="https://img.shields.io/badge/RAG%20%26%20Vector%20Contexts-008080?style=flat-square" alt="RAG" />
  <img src="https://img.shields.io/badge/Local%20LLMs%20(Ollama)-black?style=flat-square&logo=ollama&logoColor=white" alt="Ollama" />
</p>

### Sistemas, Desktop & Game Dev
<p>
  <img src="https://img.shields.io/badge/Tauri%20v2-24C8DB?style=flat-square&logo=tauri&logoColor=black" alt="Tauri" />
  <img src="https://img.shields.io/badge/.NET%208%20/%20CLR-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET 8" />
  <img src="https://img.shields.io/badge/MonoGame-E03A3E?style=flat-square" alt="MonoGame" />
  <img src="https://img.shields.io/badge/Dear%20ImGui-000000?style=flat-square" alt="ImGui" />
  <img src="https://img.shields.io/badge/Linux%20Desktop%20Internals-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux Internals" />
  <img src="https://img.shields.io/badge/P%2FInvoke%20%26%20Native%20Interop-333333?style=flat-square" alt="Native Interop" />
</p>

### Web, Backend & Tooling
<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="TailwindCSS" />
  <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white" alt="WebSockets" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Snapcraft-E95420?style=flat-square&logo=canonical&logoColor=white" alt="Snapcraft" />
</p>

---

## 🏛️ Princípios de Engenharia

1. **Sem Gambiarras**: Soluções arquitetadas com base em contratos firmes, tipagem sólida e padrões comprovados da indústria.
2. **Eficiência de Recursos**: Respeito pelo hardware — uso preferencial de linguagens compiladas e otimização de ciclos de CPU e alocações de memória.
3. **Automação & Evidências**: Nada é dado como concluído sem evidências empíricas de funcionamento (testes unitários, testes de integração e validação em runtime).

---

<details>
<summary><b>🇺🇸 View Profile in English</b></summary>
<br>

### Senior Software Engineer & AI Systems Engineer

Software developer with over a decade of hands-on experience (since **2012**), specializing in **AI Agent Systems**, **Low-Level/Desktop Engineering**, and **Polyglot Architecture** (Rust, C#, Python, TypeScript).

#### Flagship Projects:
- **[agent-cockpit](https://github.com/bruno33223/agent-cockpit)**: Autonomous AI agent orchestration cockpit powered by the Model Context Protocol (MCP), featuring 3x3 parallel agent fleets, AST codebase analysis, and adversarial verification loops (*Gauntlet Loops*).
- **[MonoGameMaker](https://github.com/bruno33223/MonoGameMaker)**: High-performance C# desktop IDE and runtime orchestrator for MonoGame, featuring dynamic in-memory hot reload via .NET 8 `AssemblyLoadContext`, reflection-based live inspection in ImGui.NET, and reactive thread-safe filesystem caching.
- **[Linux-ClipBoard](https://github.com/bruno33223/Linux-ClipBoard)**: Ultra-lightweight native Linux clipboard manager built with Tauri v2 (Rust backend) and React/Tailwind, distributed via Snap Store, AppImage, and Deb packages.

</details>

---

## 📬 Contato & Conexões

- **GitHub**: [@bruno33223](https://github.com/bruno33223)
- **Email**: [brunugui7l@gmail.com](mailto:brunugui7l@gmail.com)
