👋 @ andff <a href="https://www.instagram.com/andff" alt="Instagram" target="_blank">
  <img src="https://img.shields.io/badge/-Instagram-DF0174?style=for-the-badge&labelColor=DF0174&logo=instagram&logoColor=white&link=https://www.instagram.com/andff">
</a> <br>
# 🐙 Formatações avançadas

## Alertas

Alertas são uma extensão Markdown baseada na sintaxe blockquote que você pode usar para enfatizar informações críticas. Eles são exibidos com cores e ícones distintos para indicar a importância do conteúdo.

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

## Seção recolhida

Você pode recolher temporariamente seções do seu Markdown criando uma seção expandida que o leitor pode optar por expandir. Por exemplo, quando você deseja incluir detalhes técnicos em um comentário do problema que pode não ser relevante ou interessante para todos os leitores, você pode colocar esses detalhes em uma seção recolhida.

Qualquer Markdown dentro do bloco `<details>` estará recolhido até que o leitor clique em para expandir os detalhes.

No bloco `<details>`, use a marca `<summary>` para que os leitores saibam o que está dentro dele. O rótulo aparece à direita de .

<details>

<summary>Tips for collapsed sections</summary>

### You can add a header

You can add text within a collapsed section.

You can add an image or a code block, too.

```ruby
   puts "Hello World"
```

</details>

## Diagramas do Mermaid

O Mermaid é uma ferramenta inspirada em Markdown que transforma texto em diagramas. Por exemplo, o Mermaid pode interpretar gráficos de fluxo, diagramas de sequência, gráficos de pizza e muito mais.

Para criar um diagrama do Mermaid, adicione a sintaxe do Mermaid dentro de um bloco de código isolado com o identificador de linguagem mermaid. 

Por exemplo, você pode criar um fluxograma especificando valores e setas.

Here is a simple flow chart:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

## Mapas

É possível usar a sintaxe GeoJSON ou TopoJSON para criar mapas interativos. Para criar um mapa, adicione GeoJSON ou TopoJSON em um bloco de código protegido com o identificador de sintaxe geojson ou topojson. 

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
            [
              -90,
              35
            ],
            [
              -90,
              30
            ],
            [
              -85,
              30
            ],
            [
              -85,
              35
            ],
            [
              -90,
              35
            ]
          ]
        ]
      }
    }
  ]
}
```
<br>
### ⚙️ GitHub Analytics
<table>
  <tr>
    <td>
      <img
        align="left"
        src="https://github-readme-stats.vercel.app/api?username=andff&theme=dark&hide_border=false&include_all_commits=true"
        alt="Github Stats"
      />
    </td>
    <td>
      <img
        align="left"
        src="https://github-readme-stats.vercel.app/api/top-langs/?username=andff&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact"
        alt="Github Stats"
      />
    </td>
    <td>
      <br />
      <img
        align="left"
        src="https://github-readme-streak-stats.herokuapp.com/?user=andff&theme=dark&hide_border=false"
        alt="Github Stats"
      />
    </td>
  </tr>
</table>

--- 

### 🏆 GitHub Profile Trophy

<p align="center">
  <a
    href="https://github.com/ryo-ma/github-profile-trophy"
    title="repositório de troféus"
  >
    <img
      width="800"
      src="https://github-profile-trophy.vercel.app/?username=andff&column=8&theme=darkhub&no-frame=true&no-bg=true"
    />
  </a>
</p>

---

<div align="center">
  <h3><b>📍 Profile Visitor Count</b></h3>
</div>

<p align="center">
  <img
    src="https://profile-counter.glitch.me/iuricode/count.svg"
    alt="Número de visitantes no perfil"
  />
</p>

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=andff&layout=compact)](https://github.com/andff/github-readme-stats)
