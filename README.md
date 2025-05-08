# Diagrama-de-classes
Desafio uml DIO

classDiagram

    class ReprodutorMusical {
        +tocar()
        +pausar()
        +selecionalMusica(String musica)
    }

    class AparelhoTelefonico {
        +ligar(String numero)
        +atender()
        +iniciarCorreioVoz()
    }

    class NavegadorInternet {
        +exibirPagina(String url)
        +atualizarPagina()
    }

    class iPhone {
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet

![image](https://github.com/user-attachments/assets/f3663272-a11b-47a3-a054-261168a7e6af)


