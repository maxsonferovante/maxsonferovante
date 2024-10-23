# Oi, me chamo Maxson Almeida

### Entre em contato comigo! 
<div>
<a href="https://www.linkedin.com/in/maxson-almeida/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>   
<a href="malito: maxsonferovante@gmail.com" target="_blank"><img src="https://img.shields.io/badge/-Gmail-%230077B5?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>   
</div>

### Sobre mim! 

```python
from dataclasses import dataclass, field
from typing import List

@dataclass
class MaxsonAlmeida:
    name: str = "Maxson Almeida Ferovante"
    birth_date: str = "14/10/1994"
    age: int = 30
    location: str = "Florianópolis – SC"
    phone_numbers: List[str] = field(default_factory=lambda: ["(48) 99223-8206"])
    email: str = "maxsonferovante@gmail.com"
    linkedin: str = "https://www.linkedin.com/in/maxson-almeida/"
    github: str = "https://github.com/maxsonferovante"
    objetivo: str = "Atuar como Desenvolvedor Backend"
    
    resumo_profissional: str = (
        "Profissional com mais de 9 anos de experiência na área administrativa e 2 anos "
        "em desenvolvimento de software, com ênfase em backend utilizando Python. Atuação em "
        "desenvolvimento de sistemas web e microsserviços, com foco em integração e implementação "
        "de APIs RESTful usando frameworks como FastAPI, Flask e Django. Conhecimento em SQLAlchemy, "
        "bancos de dados relacionais como PostgreSQL e MySQL, além de vivência com bancos NoSQL. "
        "Experiência com infraestrutura em nuvem AWS (S3, EC2, SQS, ELB). Habilidade em trabalhar de "
        "forma colaborativa com equipes multifuncionais."
    )

    formacao_academica: List[str] = field(default_factory=lambda: [
        "Graduação em Análise e Desenvolvimento de Sistemas – UNAMA – Previsão de conclusão em 05/2026",
        "Curso Técnico de Informática – IFPA – 2014"
    ])
    
    experiencia_profissional: List[str] = field(default_factory=lambda: [
        "IN8 – 12/2023 – atual: Desenvolvimento de APIs RESTful, microsserviços, e automação na AWS.",
        "API Potiguar – 09/2024 – 10/2024: Consulta de infrações de veículos usando FastAPI, Celery e Redis.",
        "Prontofisio APP – 08/2024 – 09/2024: Desenvolvimento backend com Firebase, Python, PostgreSQL.",
        "Sindicato dos Portuários do Pará e Amapá – 02/2020 – 12/2023: Desenvolvimento Full Stack com Python e Django."
    ])

    cursos_qualificacoes: List[str] = field(default_factory=lambda: [
        "Desenvolvimento de Software com foco em Backend Node.Js – Cubos Academy – 12/2023",
        "Excel avançado",
        "Inglês básico para leitura e escrita"
    ])

    def say_hi(self):
        return f"Olá! Eu sou {self.name}, um desenvolvedor backend com experiência em Python, FastAPI, e AWS."

maxson = MaxsonAlmeida()
print(maxson.say_hi())
```

**Tecnologias e Ferramentas**

<!-- (Aqui você pode adicionar tecnologias que aprendeu no curso, já listamos algumas delas, e outras que já domina)) -->

**Programming Languages**

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

**Backend Development**

![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white) 
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) 
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?logo=pytest)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)

**Database**

![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white) 
![Prisma](https://img.shields.io/badge/prisma-5D3FD3?style=for-the-badge&logo=prisma&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-13aa52?style=for-the-badge&logo=mongodb&logoColor=white)

**Plataform**

![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-000?style=for-the-badge&logo=apachekafka)
![RabbitMQ](https://img.shields.io/badge/Rabbitmq-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)

**Deployment**

![LINUX](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Manjaro](https://img.shields.io/badge/Manjaro-35BF5C?style=for-the-badge&logo=Manjaro&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white)

[![](https://visitcount.itsvg.in/api?id=maxsonferovante&icon=2&color=1)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
