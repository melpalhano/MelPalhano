<br />

```JS
class melpalhano {
  constructor() {
    this.nome = "Melissa Palhano";
    this.perfil = ["analítico", "estratégico"];
    this.faculdade = "B.I. Ciência e Tecnologia (UFMA)";
    this.tec = [
      "Javascript",
      "Typescript",
      `Python`,
      { "Frameworks/Bibliotecas": ["React.js", "Next.js"] },
    ];
  }

  get informations() {
    const today = new Date();

    return (
      `Meu nome é ${this.nome}, e estou com foco em desenvolvimento Full Stack. \n` +
      `Tenho um perfil ${this.perfil[0]} e ${this.perfil[1]}. \n` +
      `Tecnologias que mais utilizo: ${this.tec[0]} ${this.tec[1]} e ${this.tec[2]}. \n` +
      `Meu diferencial é a criatividade para resolver problemas de forma inovadora e eficiente. \n\n` +
      `Atualmente, estou me graduando em ${this.faculdade} \n` +
      `E faço parte de diversos projetos integrados à Universidade: \n` +
      `- Arm Digital - Desenvolvimento Web; \n` +
      `- Sirius Sat - Carga Útil; \n` +
      `- Zênite - Laboratório de Processamento de Imagem; `
    );
  }
}

const Me = new melpalhano();
console.log(Me.informations);
```
<br /><br />

<div>
<img align='left' src="https://data.whicdn.com/images/237176020/original.gif" width="250">
<p align="left"><a href="https://github.com/melpalhano/github-readme-stats"><img alt="Melissa Palhano's Top Languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=melpalhano&langs_count=8&count_private=true&layout=compact&theme=react&hide_border=true&bg_color=0D1117" /></a>
</div>

<br />

<div>
<p align="right">
  <a href="https://github.com/melpalhano?tab=repositories"><img alt="All Repositories" title="All Repositories" src="https://custom-icon-badges.herokuapp.com/badge/-All%20Repos-2962FF?style=for-the-badge&logoColor=white&logo=repo"/></a>
</p>
</div>
