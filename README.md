<br />

```JS
class MelPalhano {
  constructor() {
    this.name = "Melissa Palhano";
    this.profile = ["analytical", "strategic"];
    this.tech = [
      "Javascript",
      "Typescript",
      `Python`,
      { "Framework/Library": ["React.js", "Next.js"] },
    ];
  }

  get informations() {
    const today = new Date();

    return (
      `My name is ${this.name} and I'm focusing on Full Stack development (sometimes also A.I.). \n` +
      `I have an ${this.profile[0]} and ${this.profile[1]} profile. \n` +
      `Technologies I use the most: ${this.tech[0]}, ${this.tech[1]} e ${this.tech[2]}. \n` +
      `My differential is in the creativity to solve problems in an innovative and efficient way. \n\n`      
    );
  }
}

const Me = new MelPalhano();
console.log(Me.informations);
```
<br />

<div>
<img align='left' src="https://data.whicdn.com/images/237176020/original.gif" width="250">
  
<br />

<p align="left"><a href="https://github.com/melpalhano/github-readme-stats"><img alt="Melissa Palhano's Top Languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=melpalhano&langs_count=8&count_private=true&layout=compact&theme=react&hide_border=true&bg_color=0D1117" /></a>

<p align="right"><a href="https://github.com/melpalhano?tab=repositories"><img alt="All Repositories" title="All Repositories" src="https://custom-icon-badges.herokuapp.com/badge/-All%20Repos-2962FF?style=for-the-badge&logoColor=white&logo=repo"/></a>
</p>
</div>
