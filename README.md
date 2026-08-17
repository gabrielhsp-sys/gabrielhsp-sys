# Olá! Eu sou o Gabriel 👋

### Estudante de Ciência da Computação na UNIFAL-MG — do baixo nível à web, com obsessão por fazer bem feito.

---

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gabrielhspereira36@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabrielhsp-dev/)
[![Portfólio](https://img.shields.io/badge/Portfólio-0A0E1A?style=for-the-badge&logo=github&logoColor=white)](https://gabriel-bcc.github.io)

---

### 👨‍💻 Sobre mim

Me chamo **Gabriel Henrique Silva Pereira**, estou no **4º período** de Ciência da Computação na Universidade Federal de Alfenas (UNIFAL-MG).

Comecei mexendo em registro do Windows por curiosidade de entender o sistema por dentro. Essa mesma vontade de abrir a caixa e ver os fios me levou do **baixo nível em C/C++** à **orientação a objetos em Java** com testes e padrões de projeto, passando por **web full-stack** e chegando na administração do meu próprio **homelab em Linux**.

Tenho um jeito cético de trabalhar: prefiro decisão baseada em evidência a hype, e gosto de entender o *porquê* antes de aceitar. Quando construo algo, o foco não está só em funcionar — está na engenharia em volta: arquitetura em camadas, testes automatizados, CI/CD e documentação.

---

### 🛠️ Stack

![TESTE](https://img.shields.io/badge/TESTE-VERDE-brightgreen)

**Linguagens**

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Prolog](https://img.shields.io/badge/Prolog-darkred?style=flat-square)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Qualidade & Arquitetura**

![JUnit5](https://img.shields.io/badge/JUnit_5-25A162?style=flat-square&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-78A641?style=flat-square)
![JaCoCo](https://img.shields.io/badge/JaCoCo-C21325?style=flat-square)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![UML](https://img.shields.io/badge/UML-5C2D91?style=flat-square)

**Infra & Ferramentas**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white)

---

### 🎯 Projetos

🐧 **[Fedora Post-Install](https://github.com/gabriel-bcc/fedora-post-install)** — Linux

Guia pós-instalação do Fedora 44 em português, escrito pra ser copiado e colado sem quebrar o sistema. Não é lista de comando solto: cada seção tem como verificar se funcionou, e a última ensina a desfazer tudo.

- Correções do que mudou no **dnf5**: `groupupdate` não existe mais, `max_parallel_downloads` derruba metade dos guias copiados
- Secure Boot resolvido **assinando** o módulo NVIDIA com MOK, em vez de mandar desligar o Secure Boot
- Uma seção dedicada ao tuning que virou lenda e hoje é inútil no Fedora — `vm.max_map_count`, esync/fsync, libs Vulkan 32 bits na mão
- Snapshots com snapper realmente configurado, e não só o GUI instalado

`Fedora` · `Bash` · `systemd` · `Btrfs` · `RPM Fusion` · `Markdown`

---

**🎓 [Academic System](https://github.com/gabriel-bcc/academic-system)** — Java

Sistema de gestão acadêmica com controle de acesso por papéis (RBAC), rodando em CLI **e** interface JavaFX sobre exatamente a mesma lógica de negócio. O escopo funcional é enxuto de propósito: o foco está na engenharia.

- Arquitetura em camadas: `View → Controller → Service → Repository → Model`
- **Repository + Strategy** para persistência intercambiável em TXT/XML/JSON sem o domínio conhecer o formato
- Matriz de permissões como fonte única de verdade + trilha de auditoria
- **13 classes de teste** (JUnit 5 + Mockito) com cobertura via JaCoCo
- **4 workflows de CI/CD**: build/testes, validação de PR, imagem Docker no GHCR e release por tag

`Java` · `JavaFX` · `Maven` · `JUnit 5` · `Mockito` · `Docker` · `GitHub Actions`

---

**🖥️ Homelab Self-Hosted** — Linux

Servidor pessoal em Debian hospedando meus próprios serviços: gerenciador de senhas, backup de fotos, sincronização de arquivos, mídia, Git próprio e monitoramento.

- Serviços isolados em containers Docker
- Acesso por rede privada com **Tailscale** — contorna o CGNAT do provedor sem abrir uma porta sequer
- Zero exposição à internet pública

`Debian` · `Docker` · `Tailscale` · `Redes`

---

**💪 Reset — App de Treino** — Web

PWA instalável para registro e progressão de treinos, com backend em Supabase e deploy na Netlify.

`JavaScript` · `Supabase` · `PWA` · `Netlify`

---

**📚 [faculdade-bcc](https://github.com/gabriel-bcc/faculdade-bcc)**

Toda a graduação organizada por período — código, atividades e trabalhos de cada disciplina.

---

### 🌱 Cursando agora (4º período)

`Banco de Dados` · `Computação Gráfica` · `Sistemas Operacionais` · `Teoria de Linguagens e Compiladores` · `Programação Web` · `Gestão do Ciclo de Vida da Aplicação` · `Estatística Básica`

---

### 📊 Estatísticas

![Stats](https://github-readme-stats.vercel.app/api?username=gabriel-bcc&show_icons=true&theme=tokyonight&rank_icon=github)
![Linguagens](https://github-readme-stats.vercel.app/api/top-langs/?username=gabriel-bcc&layout=compact&langs_count=7&theme=tokyonight)

---

Aberto a oportunidades de estágio e a trocas de ideia. É só chamar.
