<div align="center">

# Olá, eu sou o Lucas 

### Engenharia Elétrica @ EESC-USP · Sistemas Embarcados & Visão Computacional

Construindo percepção robótica de fronteira em hardware restrito — do processamento clássico de imagem à inferência leve em Edge AI.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/lucas-souza-engundergrad)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:lucasal.souza12@gmail.com)


</div>

---

### Sobre mim

Sou aluno do 4º semestre de Engenharia Elétrica na EESC-USP, com ênfase em Sistemas de Energia e Automação. Meu foco técnico está na interseção entre **eletrônica embarcada** e **software de percepção**: capturar dados do mundo real com hardware limitado (Raspberry Pi, câmeras USB, sensores) e transformá-los em decisões confiáveis de controle.

Trabalho seguindo princípios de engenharia de produção — SRP, contratos de dados rigorosos, *type hints* e testes automatizados, mesmo em projetos acadêmicos, porque acredito que código que roda ao ar livre sem supervisão não perdoa atalhos.

-  Atualmente desenvolvendo o subsistema de visão computacional do **BulbaTech**;
-  Migrando de visão clássica (HSV/OpenCV) para *Edge AI* (inferência leve em ARM) com Pytorch;
-  Interesses: sistemas embarcados, automação, visão computacional, robótica autônoma;
-  Pergunte-me sobre: Raspberry Pi, OpenCV, arquitetura de módulos *stateless*, calibração de câmera.

---

###  Destaque: BulbaTech

**Robô autônomo temático com propósito educacional em meteorologia e botânica**, desenvolvido para o Projeto de Bixos 2026 (EESC-USP). Atuo no subsistema embarcado de visão computacional, responsável por detectar e localizar alvos ambientais (sol/nuvem) sob condições reais de iluminação outdoor.

**Desafios técnicos resolvidos:**
-  **Captura sem travar o pipeline** — thread de aquisição dedicada (V4L2) com buffer protegido por *Lock*, desacoplando I/O de câmera do processamento
-  **Detecção robusta em campo aberto** — segmentação HSV com filtros geométricos (solidez de contorno) para rejeitar falsos positivos por glare solar
-  **Arquitetura substituível** — módulo de percepção 100% *stateless*, preparado para troca cirúrgica de visão clássica por inferência neural sem refatorar a máquina de estados
-  **Restrição de hardware como especificação** — resolução 320×240, kernels morfológicos pequenos e zero loops pixel-a-pixel em Python, tudo dimensionado para os limites de um Raspberry Pi 4B

**Stack:** `Python` · `OpenCV` · `NumPy` · `Raspberry Pi 4B`·

[![Repo](https://img.shields.io/badge/Ver_Repositório-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/usp-lucas/bulbatech-semear)

---

### 🛠️ Tech Stack & Ferramentas

**Linguagens**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Visão Computacional & Dados**

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Embarcado & Hardware**

![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Ferramentas & Testes**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

---

### 📊 GitHub Stats

<div align="center">

![Anurag's GitHub stats](https://github-stats-extended.vercel.app/api?username=usp-lucas)](https://github.com/stats-organization/github-stats-extended)
![Top Langs](https://github-stats-extended.vercel.app/api/top-langs/?username=usp-lucas&langs_count=4)

</div>

---

<div align="center">

📫 **Vamos conversar:** [LinkedIn](https://linkedin.com/in/lucas-souza-engundergrad) · [Email](mailto:lucasal.souza12@gmail.com)

</div>
