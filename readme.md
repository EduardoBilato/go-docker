# Desafio Go
<div align="center">

![Imersão Full Stack && Full Cycle](https://fullcycle.com.br/wp-content/themes/fullcycle/assets/images/fullcycle-logo.svg)
</div>


<p>Esse desafio é muito empolgante principalmente se você nunca trabalhou com a linguagem Go!
<br>
<p>Você terá que publicar uma imagem no docker hub. Quando executarmos:

```bash
docker run <seu-user>/codeeducation
```

<p>Temos que ter o seguinte resultado: Code.education Rocks!
<br>
<p>Se você perceber, essa imagem apenas realiza um print da mensagem como resultado final, logo, vale a pena dar uma conferida no próprio site da Go Lang para aprender como fazer um "olá mundo".
<br>
<p>Lembrando que a Go Lang possui imagens oficiais prontas, vale a pena consultar o Docker Hub.

**OBS:** A imagem de nosso projeto Go precisa ter menos de 2MB =)


<hr><br>

## Nota:
<p>A imagem **scratch** é baseada em debian.

<hr><br>

## Buildar a imagem

```bash 
docker build -t eduardobilato/codeeducation .
```

## Rodar o container

```bash 
docker run --rm eduardobilato/codeeducation
```

## Referências:

[Golang](https://gobyexample.com/hello-world)