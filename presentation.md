---
marp: true
backgroundColor: #121212
color: #fff
_class: lead
theme: gaia
transition: melt
size: 16:9
footer: "Núcleo de Estudantes de Informática - ISEP ![w:120px](assets/logo-white.png 'Logo NEI-ISEP')"
style: |
  header {
    display: flex;
    align-items: center;
    gap: 1rem;
    padding: 1rem;
    font-size: 0.5rem;
  } 
  h1 {
    font-size: 1.5rem;
  }
  h2 {
    font-size: 1.25em;
    color: #e63;
    text-align: center;
  }
  footer {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 1.5rem;
  }
  p {
    font-size: 0.8rem;
  }
---

<style scoped>
  h1 {
    font-size: 2rem;
  }
</style>

# Software Livre no Núcleo de Estudantes de Informática do ISEP

## O caso do AntiRecurso

---

<!--
header: "**O que é o NEI** _AntiRecurso - Origem_ _AntiRecurso - Desenvolvimento_ _AntiRecurso - Sucesso_ _Software Livre_"
footer: "Núcleo de Estudantes de Informática - ISEP ![w:120px](assets/logo-black.png 'Logo NEI-ISEP')"
transition: fade
backgroundColor: #fff
color: #000
-->
<style scoped>
  p > img {
    position: absolute;
    right: 4rem;
    bottom: 50%;
    transform: translateY(50%);
  }
</style>

![NEI LOGO](assets/nei-icon.png)

# O que é o NEI-ISEP?

Núcleo de Estudantes de Informática do ISEP

Desde 2014

---

![w:620](assets/fallstack.JPG)

![w:620](assets/fallstack-stand.JPG)

---

![w:620](assets/gamejam.JPG)

---

# Departamento de Informática

<style scoped>
  section {
    display: flex;
    align-items: center;
    justify-content: space-around;
    gap: 1rem;
  }
  h1 {
    position: absolute;
    left: 2rem;
    top: 2rem;
  }
  code {
    width: 100%;
  }
</style>

```javascript
if (evento || plataforma || projeto) {
  informatica();
}
```

![w:520px](assets/github-org.png)

---

<!--
header: "_O que é o NEI_ **AntiRecurso - Origem** _AntiRecurso - Desenvolvimento_ _AntiRecurso - Sucesso_ _Software Livre_"
_class: lead
-->

![w:520px](assets/multiple-choice-meme.png)

---

<style scoped>
  p > img {
    position: absolute;
    right: 4rem;
    bottom: 50%;
    transform: translateY(50%);
  }
</style>

# Origem

Criado em 2018

Exclusivo Android

![w:750](assets/old-antirecurso.png)

---

<!--
header: "_O que é o NEI_ _AntiRecurso - Origem_ **AntiRecurso - Desenvolvimento** _AntiRecurso - Sucesso_ _Software Livre_"
_class: lead
-->

<style scoped>
  h1 {
    font-size: 3rem;
  }
</style>

# ♻️

<!--
Falar sobre a ideia do rewrite
-->

---

# Desafios

<style scoped>
  p > img {
    position: absolute;
    right: 4rem;
    bottom: 50%;
    transform: translateY(50%);
  }
</style>

Timing

Recursos

Informação disponível

![w:420](assets/timing-meme.png)

---

# Crawler

<style scoped>
  h1 {
    position: absolute;
    left: 2rem;
    top: 2rem;
  }
  h2 {
    font-size: 1.2rem;
  }
  section {
    display: grid;
    grid-template-columns: 1fr 1fr 10fr;

    align-items: center;
    gap: 0.5rem;
  }
  section code {
    width: 100%;
    font-size: 1.5rem;
  }
</style>

![w:480px](assets/sample-exam.png)

## ➡

```json
{
    "line": "8) Em x86-64, a instrução “popq %rax” é o equivalente a “movq %rax,(%rsp)” seguido de “subq...",
    "question_number": 8,
    "question": "Em x86-64, a instrução “popq %rax” é o equivalente a “movq %rax,(%rsp)” seguido de “subq $8,%rsp”",
    "options": [
      "Verdadeiro",
      "Falso"
    ],
    "correct_index": 1
  },
  {
    "line": "9) Em x86-64, se atribuirmos valores com sinal aos registos a somar, o resultado será incorreto se a flag ..."
    "question_number": 9,
    "question": "Em x86-64, se atribuirmos valores com sinal aos registos a somar, o resultado será incorreto se a flag..."
    "options": [
      "Verdadeiro",
      "Falso"
    ],
    "correct_index": 1
  },
  {
    "line": "10) Em x86-64, a instrução “movq %rax,%rsp” é o equivalente a “popq %rax” seguido de “addq $8,%rsp”",
    "question_number": 10,
    "question": "Em x86-64, a instrução “movq %rax,%rsp” é o equivalente a “popq %rax” seguido de “addq $8,%rsp”",
    "options": [
      "Verdadeiro",
      "Falso"
    ],
    "correct_index": 1
  }
```

---

<style scoped>
  section {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 1rem;
  }
  p {
    width: 607px;
    height: 361px;
    margin: 0;
  }
  p img {
    width: 100%;
    height: 100%;
  }
</style>

![AntiRecurso Landing](assets/antirecurso-landing.png)

![AntiRecurso Exam](assets/antirecurso-exam.png)

---

<style scoped>
  section {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 1rem;
  }
  p {
    width: 620px;
    height: 360px;
    margin: 0;
  }
  p img {
    width: 100%;
    height: 100%;
  }
</style>

![AntiRecurso Profile](assets/antirecurso-profile.png)

![AntiRecurso Stats](assets/antirecurso-stats.png)

---

<!--
_transition: wiper
-->
<style scoped>
  p {
    height: 420px;
    position: absolute;
    right: 50%;
    bottom: 50%;
    transform: translate(50%, 50%);
  }
</style>

![w:720](assets/codebase-meme-cropped.png)

---

<style scoped>
  p {
    height: 420px;
    position: absolute;
    right: 50%;
    bottom: 50%;
    transform: translate(50%, 50%);
  }
</style>

![w:720](assets/codebase-meme.png)

---

<!--
header: "_O que é o NEI_ _AntiRecurso - Origem_ _AntiRecurso - Desenvolvimento_ **AntiRecurso - Sucesso** _Software Livre_"
-->

<style scoped>
  section {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 1rem;
  }
</style>

## ![w:420](assets/no-exams-per-day.png)

## ![w:620](assets/pr-list.png)

---

<!--
_class: lead
-->

<style scoped>
  h1 {
    font-size: 2.5rem;
  }
</style>

# 🔜

<!--
Falar sobre os próximos passos:

- Melhorar o crawler (generalizar)
- Novos tipos de perguntas
- Novas funcionalidades
- Não ir preso
-->

---

<!--
header: "_O que é o NEI_ _AntiRecurso - Origem_ _AntiRecurso - Desenvolvimento_ _AntiRecurso - Sucesso_ **Software Livre**"
_class: lead
-->

![w:720](assets/github-repos.png)

---

<!--
_class: lead
-->

<style scoped>
  h1 {
    font-size: 2.5rem;
  }
</style>

# 📈

---

<!--
_class: lead
-->

![w:720](assets/fork-dei.png)

---

<!--
_class: lead
-->

<style scoped>
  h1 {
    font-size: 2.5rem;
  }
</style>

# 📚

<!--
Recurso para os estudantes estudarem e terem uma base de um projeto real.
-->

---

<!--
_class: lead
-->

![w:720](assets/pr-list.png)

---

<!--
_class: lead
-->

<style scoped>
  h1 {
    font-size: 2.5rem;
  }
  p {
    display: flex;
    align-items: center;
    gap: 0.25rem;
  }
</style>

![w:32](assets/socials/instagram.png) @nei.isep

![w:32](assets/socials/twitter.jpg) @nei_isep

![w:32](assets/socials/website.png) nei-isep.org
