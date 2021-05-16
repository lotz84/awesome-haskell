> いわゆるgetter/setterの圏論による表現。  
> [Lens](http://mbps.hatenablog.com/entry/2014/10/28/152931)

> `Lens' s a`: given a type `s` that always has an `a` in it, a `Lens' s a` is a way of getting and setting that `a` inside of `s`  
> `Prism' s a`: given a type `s` that might have an `a` in it, a `Prism' s a` is a way of extracting the `a` if it exists, and being able to create an `s` given an `a`  
> `Traversal' s a`: target many `a`s which may or may not exist inside of an `s`  
> `Iso' s a` : says that `s` and `a` are different representations of the same type  
> All `Lens`es are `Traversal`s and all `Prism`s are also `Traversal`s. Not all `Traversal`s are `Lens`es or `Prism`s though.  
> <https://www.reddit.com/r/haskell/comments/9ded97/is_learning_how_to_use_the_lens_library_worth_it/e5hf9ai/>

* [Well-Typed - The Haskell Consultants: Announcing the optics library](https://www.well-typed.com/blog/2019/09/announcing-the-optics-library/)
* [microlens](http://hackage.haskell.org/package/microlens)
* [lens](https://hackage.haskell.org/package/lens)
* [Control.Lens.Tutorial](https://hackage.haskell.org/package/lens-tutorial/docs/Control-Lens-Tutorial.html)
* [Lensってなに？どういう仕組みなの？](http://qiita.com/cormojs/items/f94be4300b5cc60a9de0)
* [Lensの仕組みがわかった - Qiita](https://qiita.com/sgmryk/items/c467af40c6c9df0f95a1)
* [Kinokkory/lens-japanese](https://github.com/Kinokkory/lens-japanese/wiki)
* [lensパッケージのオプティクス(弱い順)](http://fumieval.hatenablog.com/entry/2015/07/14/223329)
* [A Clear Intro to Lenses](http://begriffs.com/posts/2016-01-07-clear-intro-to-lenses.html)
* [Lensで行こう！](http://myuon-myon.hatenablog.com/entry/20121228/1356708483)
* [Lensで行こう！(2):Isoへの拡張](http://myuon-myon.hatenablog.com/entry/2013/01/06/232142)
* [lens over tea](http://artyom.me/#lens-over-tea)
* 🎥 [Lenses, Folds and Traversals: An Introduction to the Lens Library with Edward Kmett](http://vimeo.com/56063074)
* [Picking a lens library](https://ro-che.info/ccc/23)
* [Functor is to Lens as Applicative is to Biplate: Introducing Multiplate](http://arxiv.org/abs/1103.2841)
* [Could someone explain the diagram about the `lens` library?](http://stackoverflow.com/questions/29742634/could-someone-explain-the-diagram-about-the-lens-library/29742635#29742635)
* [Lenses: compositional data access and manipulation.](https://skillsmatter.com/skillscasts/4251-lenses-compositional-data-access-and-manipulation)
* [Zippers and lenses](http://www.scs.stanford.edu/14sp-cs240h/slides/lenses-slides.html)
* [LensでHaskellをもっと格好良く！ 2013/3/31](http://www.slideshare.net/itsoutoftunethismymusic/ekmett-17955009)
* [LensでHaskellをもっと格好良く！ 2013/5/30](http://tokiwoousaka.github.io/takahashi/contents/20150530LensPrism.html)
* [Lens : Smart setter for immutable data](https://speakerdeck.com/hiratara/lens-smart-setter-for-immutable-data)
* [Beyond Scala Lens](http://www.slideshare.net/JulienTruffaut/beyond-scala-lens)
* [total-1.0.0: Exhaustive pattern matching using traversals, prisms, and lenses](http://www.haskellforall.com/2015/01/total-100-exhaustive-pattern-matching.html)
* [himura/lens-regex](https://github.com/himura/lens-regex)
* [Lens from Scratch](http://myuon-myon.hatenablog.com/entry/2015/07/14/203521)
* [Haskell/Lenses and functional references](https://en.wikibooks.org/wiki/Haskell/Lenses_and_functional_references)
* [Lenses from the ground up](http://taylor.fausak.me/2014/08/03/lenses-from-the-ground-up/)
* [Explicit is better than implicit](http://www.haskellforall.com/2015/10/explicit-is-better-than-implicit.html)
* [The lens-simple package](http://hackage.haskell.org/package/lens-simple)
* [Profunctor Polymorphism](https://bartoszmilewski.com/2016/08/16/profunctor-polymorphism/)
* [Lenses: Yoneda with Adjunctions](https://bartoszmilewski.com/2016/09/06/lenses-yoneda-with-adjunctions/)
* [$(lens 'foo) -- handy one-off lens maker for record fields](https://gist.github.com/chrisdone/c50e2ffc9e71a38d4fed9813fa90bbf4)
* [Oleg's gists - Affine Traversal](http://oleg.fi/gists/posts/2017-03-20-affine-traversal.html)
* [Oleg's gists - Compiling lenses](http://oleg.fi/gists/posts/2017-03-31-compiling-lenses.html)
* [Oleg's gists - Mutated lenses](http://oleg.fi/gists/posts/2017-04-07-mutated-lens.html)
* [Oleg's gists - Glassery](http://oleg.fi/gists/posts/2017-04-18-glassery.html)
* [Lost in Technopolis](http://newartisans.com/2017/04/putting-lenses-to-work/)
* [Oleg's gists - Indexed Profunctor optics](http://oleg.fi/gists/posts/2017-04-26-indexed-poptics.html)
* [Profunctor Optics: The Categorical View \|   Bartosz Milewski's Programming Cafe](https://bartoszmilewski.com/2017/07/07/profunctor-optics-the-categorical-view/)
* [mchaver - Lens Tutorial - SimpleLens](http://www.mchaver.com/posts/2017-07-12-lens-tutorial-1.html)
* [Why Lenses Work](http://blog.vmchale.com/article/why-lenses-work)
* [hablapps/DontFearTheProfunctorOptics: Don't Fear the Profunctor Optics!](https://github.com/hablapps/DontFearTheProfunctorOptics#readme)
* [AnkiWeb - Haskell lens operators](https://ankiweb.net/shared/info/1994529308)
* [Quick and easy user-defined operators with Plated](https://qfpl.io/posts/quick-and-easy-user-defined-operators/)
* [Announcing generic-lens 0.5.0.0 – ( )](http://kcsongor.github.io/generic-lens/)
* [Oleg's gists - Functor Optics](http://oleg.fi/gists/posts/2017-12-23-functor-optics.html)
* [あいや☆ぱぶりっしゅぶろぐ！ - lensの演算子と等価な関数の対応表](http://aiya000.github.io/posts/2017-09-10-lens-operator-to-func.html)
* [あいや☆ぱぶりっしゅぶろぐ！ - lens（のMonadState演算子など）で自己に言及したい時はidを使う](http://aiya000.github.io/posts/2017-10-29-identity-in-lens-monadstate.html)
* [Free Lenses for Higher-Kinded Data :: Reasonably Polymorphic](http://reasonablypolymorphic.com/blog/free-lenses)
* [HKD: Less Terrible than You Might Expect :: Reasonably Polymorphic](http://reasonablypolymorphic.com/blog/hkd-not-terrible)
* [高談活論: 双方向変換の原理と実践](https://www.jstage.jst.go.jp/article/jssst/31/2/31_2_44/_pdf)
  * [b18n-combined: Combining Syntactic and Semantic Bidirectionalization](http://www2.sf.ecei.tohoku.ac.jp/~kztk/b18n-combined/desc.html)
  * [bff: Bidirectionalization for Free! (POPL'09)](https://hackage.haskell.org/package/bff-0.3.1.2)
* [Deciphering lens error messages, part 1 – Urbint Engineering – Medium](https://medium.com/urbint-engineering/deciphering-lens-error-messages-part-1-75627c440090)
* [Lysxia - Monadic profunctors for bidirectional programming](https://blog.poisson.chat/posts/2017-01-01-monadic-profunctors.html)
* [Lenses embody Products, Prisms embody Sums · in Code](https://blog.jle.im/entry/lenses-products-prisms-sums.html)
* [Haskell Lens Operator Onboarding – Urbint Engineering – Medium](https://medium.com/urbint-engineering/haskell-lens-operator-onboarding-a235481e8fac)
* [Well-Typed - The Haskell Consultants: Compositional zooming for <tt>StateT</tt> and <tt>ReaderT</tt> using <tt>lens</tt>](http://www.well-typed.com/blog/2018/09/compositional-zooming/)
* [Lenses for philosophers – Jules Hedges](https://julesh.com/2018/08/16/lenses-for-philosophers/)
* [A clear picture of lens laws —Functional Pearl—](http://research.nii.ac.jp/~hu/pub/mpc15.pdf)
* [Lens By Example - Writing Traversals](https://lens-by-example.chrispenner.ca/articles/traversals/writing-traversals)
* [Yoneda](https://gist.github.com/Icelandjack/aecf49b75afcfcee9ead29d27cc234d5)
* [Yoneda Intuition from Humble Beginnings](https://gist.github.com/Icelandjack/02069708bc75f4284ac625cd0e2ec81f)
* [Functional Works - Yo, Yoneda!](https://functional.works-hub.com/learn/yo-yoneda-a2965)
* [What You Needa Know about Yoneda](https://www.cs.ox.ac.uk/jeremy.gibbons/publications/proyo.pdf)
* [Oleg's gists - Finding correct (lens) laws](http://oleg.fi/gists/posts/2018-12-12-find-correct-laws.html)
* [TemplateHaskell不要なレコードアクセサgeneric-lens🙄 - Qiita](https://qiita.com/aiya000/items/778308345bc863f55d26)
* [Lens into wrapped newtypes / Jappie](https://jappieklooster.nl/lens-into-wrapped-newtypes.html)
* [Exercises for understanding lenses \| William Yao](https://williamyaoh.com/posts/2019-04-25-lens-exercises.html)
* [Lens as a Divisibility Relation: Goofin' Off With the Algebra of Types - Hey There Buddo!](http://www.philipzucker.com/lens-as-a-divisibility-relation-goofin-off-with-the-algebra-of-types/)
* [ChrisPenner/lens-errors: Handling errors which occur deep inside lens-chains](https://github.com/ChrisPenner/lens-errors#readme)
* [ChrisPenner/lens-filesystem: Lens interface for your filesystem; still a bit experimental](https://github.com/ChrisPenner/lens-filesystem)
* [Profunctor Optics and the Yoneda Lemma](https://ifipwg21wiki.cs.kuleuven.be/pub/IFIP21/Brandenburg/wg21m77.pdf)
* [Optics + Regex: Greater than the sum of their parts](https://chrispenner.ca/posts/lens-regex-pcre)
* [Building Lenses](https://vitez.me/building-lenses)
* [Fibrations, Cleavages, and Lenses \|   Bartosz Milewski's Programming Cafe](https://bartoszmilewski.com/2019/10/09/fibrations-cleavages-and-lenses/)
* [[1809.00738] Categories of Optics](https://arxiv.org/abs/1809.00738)
* [Optics Cheatsheet](https://gist.github.com/ChrisPenner/1f7b6923448b3396a45d04a2b6b9d066)
* [Algebraic lenses](https://chrispenner.ca/posts/algebraic)
* [Optics By Example by Chris Penner [Leanpub PDF/iPad/Kindle]](https://leanpub.com/optics-by-example/)
* [Advent of Optics: Day 1](https://chrispenner.ca/posts/advent-of-optics-01)
* [Intro to Kaleidoscopes: Optics for aggregating data through Applicatives](https://chrispenner.ca/posts/kaleidoscopes)
* [Oleg's gists - Case study: migrating from lens to optics](http://oleg.fi/gists/posts/2020-01-25-case-study-migration-from-lens-to-optics.html)
* [Digging into Lenses \| Deontologician](https://deontologician.com/wiki/lenses/)
* [[2002.11480] String Diagrams for Optics](https://arxiv.org/abs/2002.11480)
* [Lenses for Tree Traversals](https://www.michaelpj.com/blog/2020/08/02/lenses-for-tree-traversals.html)
* [[1807.01948] Incremental Relational Lenses](https://arxiv.org/abs/1807.01948)
* [Optics and Kleisli arrows](https://gist.github.com/serras/5152ec18ec5223b676cc67cac0e99b70)
* [kowainik/prolens: 👓 Profunctor based lightweight implementation of Lenses](https://github.com/kowainik/prolens)
* [Trying to create Syntax Optics](https://yairchu.github.io/posts/attempting-syntax-optics)
* [Composable filters using Witherable optics](https://chrispenner.ca/posts/witherable-optics)
* [Oleg's gists - Coindexed optics](https://oleg.fi/gists/posts/2021-01-04-coindexed-optics.html)
* [[1805.06798] Generic Deriving of Generic Traversals](https://arxiv.org/abs/1805.06798)
* [Lensとは - Qiita](https://qiita.com/sparklingbaby/items/e66f48224067647d8e67)

> Thus the Yoneda embedding of the functor category leads to the van Laarhoven representation of the lens

出典: [From Lenses to Yoneda Embedding](http://bartoszmilewski.com/2015/07/13/from-lenses-to-yoneda-embedding/)

* [[1809.00738] Categories of Optics](https://arxiv.org/abs/1809.00738)

### Lens Libraries
* [yaml-light-lens](https://hackage.haskell.org/package/yaml-light-lens)

## Prism
> A prism is like a first-class pattern match

<https://www.youtube.com/watch?v=GZPup5Iuaqw>

* [Parsers and Builders as Prisms](https://yairchu.github.io/posts/codecs-as-prisms.html)
* [Elegant AST Parsing and Building with Prisms](https://yairchu.github.io/posts/codecs-as-prisms-asts.html)

## Iso
[Data.Text.Lens](https://hackage.haskell.org/package/lens/docs/Data-Text-Lens.html)

```haskell
packed :: IsText t => Iso' String t

pack x ≡ x ^. packed
unpack x ≡ x ^. from packed
```

## Traversal
* [Reducer transformers can definitely be encoded in a lens-like shape](https://www.reddit.com/r/haskell/comments/2cv6l4/clojures_transducers_are_perverse_lenses/cjjfrxt)

## Classy Optics
* [lensのmakeClassyで型を合成する](http://tune.hateblo.jp/entry/2014/09/27/191008)
* [makeClassyを使って複数のオブジェクトで共通する函数をまとめる](https://gist.github.com/myuon/6349238)
* [Next Level MTL - George Wilson - BFPG 2016-06](https://www.youtube.com/watch?v=GZPup5Iuaqw)
