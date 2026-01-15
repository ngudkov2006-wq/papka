---
{"dg-publish":true,"permalink":"/tfkp/neobhodimoe-i-dostatochnoe-uslovie-shodimosti-posledovatelnosti-z/"}
---

й
***
### Формулировка теоремы

Для того, чтобы последовательность комплексных чисел $\{z_n\}$ сходилась, необходимо и достаточно, чтобы сходились последовательности действительных чисел $\{a_n\}, \{b_n\}$ ($z_n = a_n + ib_n$).

---
### Доказательство

**1) Необходимость.**
Пусть последовательность $\{z_n\}$ сходится к некоторому числу $z = a + ib$, то есть $\forall \varepsilon > 0 \exists N > 0: \forall n \ge N: |z_n - z| < \varepsilon$. Воспользуемся очевидными неравенствами:
$$|a_n - a| \le |z_n - z|$$
$$|b_n - b| \le |z_n - z|$$
Получаем, что $\forall \varepsilon > 0 \exists N > 0: \forall n \ge N: |a_n - a| < \varepsilon$ и $|b_n - b| < \varepsilon$, что по определению и означает: $\{a_n\} \to a, \{b_n\} \to b, n \to \infty$.

**2) Достаточность.**
Пусть сходятся $\{a_n\}$ и $\{b_n\}$, то есть выполнено $\forall \frac{\varepsilon}{2} > 0 \exists N > 0: \forall n \ge N: |a_n - a| < \frac{\varepsilon}{2}$ и $|b_n - b| < \frac{\varepsilon}{2}$, тогда рассмотрим равенство:
$$|z_n - z| = \sqrt{(a_n - a)^2 + (b_n - b)^2} \le |a_n - a| + |b_n - b| < \varepsilon$$
Таким образом, $\forall \varepsilon > 0 \exists N > 0: \forall n \ge N: |z_n - z| < \varepsilon$.

**Теорема доказана.**