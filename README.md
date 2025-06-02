# Oi, me chamo Maxson Almeida

### Entre em contato comigo! 
<div>
<a href="https://www.linkedin.com/in/maxson-almeida/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>   
<a href="malito: maxsonferovante@gmail.com" target="_blank"><img src="https://img.shields.io/badge/-Gmail-%230077B5?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>   
</div>

### Sobre mim! 

```java
interface Desenvolvedor {
    void apresentarAtuacao();
    void escreverCodigo();
}

class Endereco {
    private String cidade;
    private String estado;

    public Endereco(String cidade, String estado) {
        this.cidade = cidade;
        this.estado = estado;
    }

    @Override
    public String toString() {
        return cidade + " – " + estado;
    }
}

class Contato {
    private String[] telefones;
    private String email;

    public Contato(String[] telefones, String email) {
        this.telefones = telefones;
        this.email = email;
    }

    public void exibirContatos() {
        System.out.println("📞 Telefone(s): " + String.join(", ", telefones));
        System.out.println("📧 E-mail: " + email);
    }
}

class RedesSociais {
    private String linkedin;
    private String github;

    public RedesSociais(String linkedin, String github) {
        this.linkedin = linkedin;
        this.github = github;
    }

    public void exibirRedes() {
        System.out.println("🔗 LinkedIn: " + linkedin);
        System.out.println("💻 GitHub: " + github);
    }
}

public class MaxsonAlmeida implements Desenvolvedor {

    private String name = "Maxson Almeida Ferovante";
    private String birthDate = "14/10/1994";
    private int age = 30;
    private Endereco endereco = new Endereco("Florianópolis", "SC");
    private Contato contato = new Contato(new String[]{"(48) 99223-8206"}, "maxsonferovante@gmail.com");
    private RedesSociais redes = new RedesSociais(
            "https://www.linkedin.com/in/maxson-almeida/",
            "https://github.com/maxsonferovante"
    );

    public void sayHi() {
        System.out.println("Olá! Eu sou " + name + ", um desenvolvedor backend com experiência em Python e Java.");
    }

    @Override
    public void apresentarAtuacao() {
        System.out.println("💻 Atuo como Desenvolvedor Backend, com foco em APIs, Microsserviços e soluções escaláveis.");
    }

    @Override
    public void escreverCodigo() {
        System.out.println("⌨️ Escrevendo código limpo, eficiente e escalável usando boas práticas de engenharia de software.");
    }

    public static void main(String[] args) {
        MaxsonAlmeida maxson = new MaxsonAlmeida();
        maxson.sayHi();
        maxson.apresentarAtuacao();
        maxson.escreverCodigo();
        System.out.println("📍 Localização: " + maxson.endereco);
        maxson.contato.exibirContatos();
        maxson.redes.exibirRedes();
    }
}
```

**Tecnologias e Ferramentas**

<!-- (Aqui você pode adicionar tecnologias que aprendeu no curso, já listamos algumas delas, e outras que já domina)) -->

**Programming Languages**

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

**Backend Development**

![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white) 
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) 
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white)

**Tests**

![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![Pytest](https://img.shields.io/badge/pytest-%23ffffff.svg?style=for-the-badge&logo=pytest&logoColor=2f9fe3)

**Database**

![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white) 
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-13aa52?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)


**Plataform**

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
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

<div align="left">
  
  <img width="41%" height="195px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=maxsonferovante&layout=compact&hide_border=true&title_color=8f00ff&text_color=ffffff&bg_color=0d1117" />
  
 </div>

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
