# Fernanda Berns França

**Estudante de Desenvolvimento de Sistemas**

Desenvolvendo conhecimentos em programação, desenvolvimento web e banco de dados.

[LinkedIn](https://www.linkedin.com/in/fernanda-berns-fran%C3%A7a-ba8939403/)

---

## about-me.sql

```sql
SELECT
    p.nome,
    p.area,
    t.tecnologia

FROM perfil p

INNER JOIN perfil_tecnologias pt
    ON p.id = pt.perfil_id

INNER JOIN tecnologias t
    ON pt.tecnologia_id = t.id




WHERE p.nome = 'Fernanda Berns França';

| nome                  | área                        | tecnologia |
| --------------------- | --------------------------- | ---------- |
| Fernanda Berns França | Desenvolvimento de Sistemas | C          |
| Fernanda Berns França | Desenvolvimento de Sistemas | PHP        |
| Fernanda Berns França | Desenvolvimento de Sistemas | HTML       |
| Fernanda Berns França | Desenvolvimento de Sistemas | CSS        |
| Fernanda Berns França | Desenvolvimento de Sistemas | PostgreSQL |


_____________________________________________________________________________________
Objetivo

Aprimorar minhas habilidades em programação, desenvolvimento web e banco de dados,
construindo minha carreira na área de tecnologia.

_____________________________________________________________________________________
SELECT status FROM carreira;
status: EM CONSTANTE APRENDIZADO
