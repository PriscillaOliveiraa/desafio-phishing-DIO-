🛡️ Desafio Didático – Simulação de Ataque de Engenharia Social com SEToolkit

📚 Objetivo

O objetivo deste desafio didático foi simular um ataque de **engenharia social** utilizando a ferramenta **SEToolkit (Social-Engineer Toolkit)** disponível no Kali Linux. 
A simulação visou demonstrar como páginas falsas (phishing) podem ser utilizadas para capturar credenciais de usuários desavisados, 
reforçando a importância da conscientização em segurança da informação.

> ⚠️ **Aviso Legal:**  
> Este projeto foi desenvolvido **exclusivamente para fins educacionais** e realizados em ambiente controlado.
> Não incentiva qualquer uso malicioso ou ilegal das ferramentas e técnicas aqui descritas.

---

🧰 Ferramentas Utilizadas

- **Kali Linux** (versão utilizada: `informe a versão aqui`)
- **SEToolkit (Social-Engineer Toolkit)**
- Navegador Web (para testes locais)
- IP local da máquina virtual

---
🛠️ Etapas Realizadas

1. Acesso como Superusuário (root)
  Primeiramente, foi necessário obter privilégios de root para executar a ferramenta:
    sudo su
2. Execução do SEToolkit
  O SEToolkit foi iniciado com o comando:
    setoolkit
     -> A ferramenta exibiu seu menu principal com diversas opções de ataque disponíveis.

3. Seleção das Opções de Ataque
  No menu do SEToolkit, as seguintes opções foram selecionadas:
    1-Social-Engineering Attacks
    2-Website Attack Vectors
    3-Credential Harvester Attack Method
    4-Site Cloner

4. Definição do Alvo
  Foi informado como URL alvo o endereço do Facebook:

5. Clonagem da Página e Captura de Credenciais
  O SEToolkit clonou a interface da página de login do Facebook.
  Essa página foi hospedada localmente na máquina atacante.
  Quando um usuário acessava o IP pelo navegador e digitava suas credenciais, os dados eram capturados e exibidos no terminal do Kali Linux.

🔍 Resultado

O ataque foi simulado com sucesso. 
A página clonada foi acessada por um navegador, e ao inserir dados falsos de login, as credenciais foram corretamente capturadas pela ferramenta.

✅ Conclusão
Este exercício demonstrou de forma prática como um ataque de phishing pode ser montado com ferramentas amplamente disponíveis. 
Também evidencia a importância da educação em segurança digital e da atenção do usuário ao verificar URLs, certificados SSL e práticas de navegação segura.

🔒 Considerações Finais
Nunca utilize essas técnicas fora de ambientes controlados ou sem autorização.
O conhecimento em cibersegurança deve ser usado para proteger, não para prejudicar.
A conscientização do usuário é a primeira linha de defesa contra ataques de engenharia social.
