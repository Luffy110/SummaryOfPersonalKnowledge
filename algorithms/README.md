# 算法学习资料汇总

## 经典书籍

[算法导论 (Thomas H.Cormen)](https://dl.ebooksworld.ir/books/Introduction.to.Algorithms.4th.Leiserson.Stein.Rivest.Cormen.MIT.Press.9780262046305.EBooksWorld.ir.pdf)

[算法 (Robert.Sedgewick)](https://sedgewick.io/books/algorithms/)

[The Design and Analysis of Computer Algorithms(Aho, Hopcroft)](https://www.semanticscholar.org/paper/The-Design-and-Analysis-of-Computer-Algorithms-Aho-Hopcroft/10a463bb00b44bdd3a8620f2bedb9e1564bfcf32)

[The Art of Computer Programming(Donald.E.Knuth)](https://www-cs-faculty.stanford.edu/~knuth/taocp.html)

[Data Structure and Network Algorithm (Robert.E.Tarjan)](https://epubs.siam.org/doi/book/10.1137/1.9781611970265)

[Algorithm Design(Jon.Kleinberg, Eva Tardos)](https://edisciplinas.usp.br/pluginfile.php/7933913/course/section/6549987/Algorithm%20Design.pdf)

[Algorithms(Dasgupta)](http://algorithmics.lsi.upc.edu/docs/Dasgupta-Papadimitriou-Vazirani.pdf)

[算法引论-一种创造性方法(Udi.Manber)](https://bayanbox.ir/view/5593452708017877904/Introduction-to-Algorithms-A-Creative-Approach.pdf)

[Algorithms(Jeff Erickson)](https://jeffe.cs.illinois.edu/teaching/algorithms/book/Algorithms-JeffE.pdf)

## 学习网站

[Robert.Sedgewick 老爷子个人网站](https://sedgewick.io/)

[Jeff Erickson 算法网站](https://jeffe.cs.illinois.edu/teaching/algorithms/)

[leetcode](https://leetcode.cn/)

[OI Wiki](https://oi-wiki.org)

## 相关论文

### 数据结构

#### Fibonacci Heaps

[Fibonacci Heaps and Their Uses in Improved Network Optimization Algorithms(Robert.Ender.Tarjan)](https://web.eecs.umich.edu/~pettie/matching/Fredman-Tarjan-Fibonacci-Heaps.pdf)

### 树

#### B-树

[Binary B-Trees for Virtual Memory(Rudolf Bayer)](https://dl.acm.org/doi/pdf/10.1145/1734714.1734731)

[Organization and Maintenance of Large Ordered Indexes(Rudolf Bayer)](https://infolab.usc.edu/csci585/Spring2010/den_ar/indexing.pdf)

[The Ubiquitous B-Tree(Douglas.Comer)](https://carlosproal.com/ir/papers/p121-comer.pdf)

#### B *树

NOTE: Knuth [The Art of Computer Programming Volume 3] defines a B*-tree to be a B-tree in which each node is at least 2/3 full (instead of just 1/2 full). From [The Ubiquitous B-Tree](https://carlosproal.com/ir/papers/p121-comer.pdf)

#### B+树

NOTE: To avoid confusion, we will use the term B+-tree for Knuth's unnamed implementation. From [The Ubiquitous B-Tree](https://carlosproal.com/ir/papers/p121-comer.pdf)

#### 二叉树

#### AVL 树

[An Algorithm for The Organization of Information(G.M.ADELSON-VELSKII AND E.M.LANDIS)](https://zhjwpku.com/assets/pdf/AED2-10-avl-paper.pdf)

[Information Storage and Retrieval Using AVL Trees(C.C.Foster)](https://dl.acm.org/doi/10.1145/800197.806043)

#### 红黑树 (2-3/2-3-4 树）

[Symmetric Binary B-Tree: Data Structure and Algorithms for Random and Sequential Information Processing(Rudolf Bayer)](https://core.ac.uk/download/pdf/4951555.pdf)

[A Diciiromatic Framework for Balanced Trees(Robert.Sedgewick)](https://sedgewick.io/wp-content/themes/sedgewick/papers/1978Dichromatic.pdf)

[Functional Pearls - Red-Black Tress in a Functional Setting(Chris Okasaki)](https://www.cs.tufts.edu/comp/150FP/archive/chris-okasaki/redblack99.pdf)

[Functional Pearls - Deletion: The curse of the red-black tree(Kimball Germane)](https://matt.might.net/papers/germane2014deletion.pdf)

[Left-leaning Red-Black Trees(Robert.Sedgewick)](https://sedgewick.io/wp-content/themes/sedgewick/papers/2008LLRB.pdf)

[Revisiting 2-3 Red-Black Tress with a Pedagogically Sound yet Efficient Deletion Algorithm: The Parity-Seeking Delete Algorithm(Kamaledin Ghiasi-Shirazi)](https://arxiv.org/abs/2004.04344)

#### 树堆 (Treap)

[Randomized Search Trees(Raimund.Seidel)](https://faculty.washington.edu/aragon/pubs/rst96.pdf)

#### 伸展树(Splay Trees)

[Self-adjusting binary search trees(Robert.E.Tarjar)](https://www.cs.cmu.edu/~sleator/papers/self-adjusting.pdf)

NOTE: 更多细节，可参考[Data Structure and Network Algorithm (Robert.Ender.Tarjan)](https://epubs.siam.org/doi/book/10.1137/1.9781611970265).

#### 线段树(Interval Tree)

#### 跳表 (Skip List)

[Skip Lists: A Probabilistic Alternative to Balanced Trees](https://15721.courses.cs.cmu.edu/spring2018/papers/08-oltpindexes1/pugh-skiplists-cacm1990.pdf)

### 图

#### 最小生成树

[On The Shortest Spanning Subtree of A Graph and The Traveling Saleman Problem(Kruskal)](http://5010.mathed.usu.edu/Fall2018/THigham/Krukskal.pdf)

[Shortest Connection Networks And Some Generalizations(Prim)](https://archive.org/details/bstj36-6-1389)

[On the History of the Minimum Spanning Tree Problem(R.L.Garham)](https://www.cs.cmu.edu/afs/cs.cmu.edu/academic/class/15859-f09/www/handouts/cmuonly/graham-hell.pdf)

#### 最短路径

[A Note on Two Problems in Connexion with Graphs(E.W.GIJKSTRA)](https://ir.cwi.nl/pub/9256/9256D.pdf)

[Efficient Algorithms for Shortest Paths in Sparse Networks(Donald.B.Johnson)](https://dl.acm.org/doi/pdf/10.1145/321992.321993)

#### 网络流

[Network Flow Algorithms(Robert.Ender.Tarjan)](https://www.cs.cornell.edu/~eva/Network.Flow.Algorithms.pdf)

[Flows in Networks(L.R.Ford)](https://www.rand.org/content/dam/rand/pubs/reports/2007/R375.pdf)

### 字符串

[KMP - Fast Pattern Matching in Strings(Donald.E.Knuth,James.H.Morris and Vaughan.R.Pratt)](https://www.semanticscholar.org/paper/Fast-Pattern-Matching-in-Strings-Knuth-Morris/5253fead88bfeaaa2930daccb7324a264cb681a9)
