### Псевдокод
- Присвоим $d[a] \leftarrow 0$, $p[a] \leftarrow 0$
- Для всех $u \in V$ отличных от $a$ присвоим $d[u] \leftarrow \infty$
- Пока $\exists v \notin U$. Пусть $\exists v \notin U$ - вершина с минимальным $d[v]$ занесём $v$ в $U$
- Для всех $u \notin U$ таких, что $vu \in E$
- Еcли $d[u] > d[v] + w[vu]$ то
- Изменим $d[u] \leftarrow d[v] + w[vu]$
- Изменим $p[u] \leftarrow (p[v], u)$