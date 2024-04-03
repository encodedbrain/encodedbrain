# Olá devs 👋

Bem vindo(a) ao meu perfil.

## Mais sobre mim


```ts
class Developer {
  private props = {
    name: "",
    acknowledgements: "",
    skills: {
      languages: [] as string[],
      frameworks: [] as string[],
      primarySkillset: [] as string[],
    },
  };

  constructor() {
    this.set();
  }

  getProps() {
    return { ...this.props };
  }

  private set() {
    this.props.name = "Marco Damasceno";
    this.props.acknowledgements = "Developer Web";
    this.props.skills.languages = ["C#", "Javascript","Typescript];
    this.props.skills.frameworks = [".NET", "Nest"];
    this.props.skills.primarySkillset = [
      "Comunicação",
      "Resolução de problemas",
      "Adaptabilidade",
      "Proatividade",
      "Foco",
      "Empatia",
      "Criatividade",
    ];
  }
}

class Person extends Developer {
  constructor() {
    super();
  }
}

const marco = new Person();
const marcoAttributes = marco.getProps();
console.log(marcoAttributes);

```

<img align="right" width="300" src="https://i.pinimg.com/originals/21/11/61/21116158daaeb1459b4ec0758505e1ad.gif" />


## Linguagens e ferramentas

<img src="https://skillicons.dev/icons?i=typescript,nodejs,mysql,mongodb,nestjs,dotnet,postgresql,express,aws,git,docker" />

## Status

<a href="https://github.com/encodedbrain">
 <img align="center" src="https://github-readme-stats.vercel.app/api?username=encodedbrain&show_icons=true&theme=dracula&line_height=27" alt="marco damasceno github stats"/>
</a>

[linkedin]: https://www.linkedin.com/in/marcodmc/

<br>

## Rede sociais
👔 [LinkedIn][linkedin]

## Contato


[marco damaceno](mailto:marcodmc0101@gmail.com?subject=[GitHub]%20Source%20Han%20Sans)

[![spotify-github-profile](https://spotify-github-profile.vercel.app/api/view?uid=e4n64kj2aznh2qwitvfei7zco&cover_image=true&theme=default&show_offline=false&background_color=121212&interchange=false)](https://github.com/kittinan/spotify-github-profile)


![Snake animation](https://github.com/encodedbrain/encodedbrain/blob/output/github-contribution-grid-snake.svg)
