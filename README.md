Capture the Flag - CTF - Maratona Forense - Daryus
=============================

Repositório para armazenar os DUMPS usados para o CTF Maratona Forense da [DARYUS][1]

Dependências
------------

Para a criação do laboratório é necessário ter pré instalado os seguintes softwares:

* [Git][2]
* [VirtualBox][3]

> Para as máquinas com MAC OS aconselhamos, se possível, que as instalações sejam feitas pelo gerenciador de pacotes **brew**.

CTF
-----------

Para que o **CTF** aconteca, estamos levando em consideracao que a etapa de **Coleta** do artefato ja foi realizada, portanto sera disponibilizada o objeto desta coleta que sao:

* f7868849bd5e0931301d15207359c3f8847965d0ed430b02499135b3631b54a3  MemLabs-Lab3.7z
* 737dd0c4834ddd7a4c36430479e46647e7eceb0a14959ff209e37902205a9c4e  MemLabs-Lab4.7z
* 2825d8a583a4afa2a0000328b46e3cd189bb904b25cb317c25c6bce54d75ab05  attack-trace.pcap_.gz

Caracterizando duas pericias de Memoria RAM e uma pericia de redes.

> Caso queiram conferir o HASH, use `sha1sum attack-trace.pcap_.gz`

Nesse laboratório, que está centralizado nas **.OVAs** do [Virtualbox][3], são sugeridas 3 distribuicoes que auxiliam no processo de analise:

Nome       | vCPUs | Memoria RAM | IP             | S.O.¹           | Link para Download²
---------- |:-----:|:-----------:|:--------------:|:---------------:| -----------------------------
Kali Linux | 1     | 3072MB      | 192.168.56.100 | Kali Linux      | [https://www.kali.org/get-kali/][5]
Windows10  | 1     | 3072MB      | 192.168.56.101 | Windows10       | [https://developer.microsoft.com/en-us/windows/downloads/virtual-machines/][6]
SIFT       | 1     | 4092MB      | 192.168.56.102 | SIFT            | [https://www.sans.org/tools/sift-workstation/][7]

> **¹**: Esses Sistemas operacionais estão sendo utilizado no formato de OVAs (Open Virtualization Appliances), é a forma como o VirtualBox chama as imagens do sistema operacional utilizado.

> **²**: Link para o Download de cada distribuicao sugerida

Criação do Laboratório 
----------------------

Para ter acesso aos dumps do **CTF** deste laboratorio é necessário fazer o `git clone` desse repositório e realizar a descompactacao dos arquivos, conforme abaixo:

```bash
git clone https://github.com/joathamp/maratona_forense_daryus.git
cd maratona_forense_daryus/
7z x MemLabs-Lab3.7z
7z x MemLabs-Lab4.7z
gunzip attack-trace.pcap_.gz 
```

Contato
----------------------

Entre em contato conosco.

Continue aprofundando seus conhecimentos, utilize este material para continuar praticando. 


Um forte abraco do Jota e do Vitor e de toda a equipe da Daryus, bons estudos e a gente se ve por ai:

* **Msc. Joatham Pedro**
  * **Perito Computacional**
  * **Pentester**
  * **Mestre em Sistemas e Computação** 
  * **Analista Sênior de Segurança da Informação - 4Linux** 
  * **Analista/Gerente de Seguranca - IFTO**   
  * **Instrutor MBA Cybersecurity Gov TI - FATEC Cuiabá**
  * **Instrutor  MBA Cybersecurity - IMPACTA**
  * **Instrutor Pos Graduacao Computação Forense - Daryus**
  * **Linux Professional Institute I** 
  * **Linux Professional Institute II** 
  * **Linux Professional Institute III - Security** 
  * **Datacenter Techical Specialist** 
  * **Novell Certified Linux Administrator (CLA)** 
  * **Computer Hacking Forensic Investigation - C|HFI** 
  * **Ec-Concil Incident Handler - EC|IH** 
  * **Certified Ethical Hacker - C|EH** 
  * **Exin Ethical Hacker - EXIN** 
  * **DevOps Essential Professional - DEPC** 
  * **Pos-Graduado em Redes de Computadores**
  * **Bacharel em Ciencia da Computacao**
  * **https://www.youtube.com/c/EaiQualteupapo**
  * **https://www.linkedin.com/in/joatham-pedro-44a3351b/**
  * **https://www.instagram.com/qualteupapo/**
  * **https://www.instagram.com/joatham.pedro/**



* **Vitor Moura Chunte**
  * **Perito Computacional**
  * **Graduado em Tecnologia e Seguranca da Informacao**
  * **Especializacao em Linux(Essentials, Security, Pentest e Forense)**
  * **Instrutor Pos Graduacao Computação Forense - Daryus**



[1]: https://www.daryus.com.br/
[2]: https://git-scm.com/downloads
[3]: https://www.virtualbox.org/wiki/Downloads
[5]: https://www.kali.org/get-kali/
[6]: https://developer.microsoft.com/en-us/windows/downloads/virtual-machines/
[7]: https://www.sans.org/tools/sift-workstation/
