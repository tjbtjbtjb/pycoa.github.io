<!-- [Pycoa Logo](fig/pycoa_logo.png) -->

<img src="fig/pycoa_plot_example.png" width="200px"> <img src="fig/pycoa_map_example.png" width="200px"> <img src="fig/pycoa_hist_example.png" width="200px"> <img src="fig/pycoa_get_example.png" width="200px">

# PyCoA version 1.0

Avril/Novembre 2020

<!-- _Ceci est la <a href="index_FR">version française </a><img src="fig/FR.png" height="14px" alt="FR flag" />. There is also an <a href=""/>english version </a><img src="fig/UK.png" height="14px" alt="UK flag" />._ -->

[<img src="fig/FR.png" height="14px" alt="FR flag"> Version française ](https://github.com/pycoa/pycoa.github.io/index_FR) / 
[ <img src="fig/UK.png" height="14px" alt="UK flag"> English  version ](https://github.com/pycoa/pycoa.github.io)


`PyCoA` (Python Covid Analysis) est un ensemble de code Python™ qui fournit :
- un accès simple aux bases de données sur la Covid-19 ;
- des outils pour représenter et analyser les données du Covid-19, comme des séries temporelles ou des cartes.

Elle est pensée pour être accessibles à des non-spécialistes : des lycéen·nes qui apprennent Python™, des étudiant·es, des journalistes scientifiques, voire même des chercheurs et chercheuses qui ne sont pas famillier·es avec l'extraction de données. Des analyses simples peuvent être directement effectuées, et des analyses plus poussées peuvent être produites par les personnes habituées à programmer en Pythpn™. Comme exemple, après avoir [installé PyCoA](https://github.com/pycoa/wiki/Install), les quelques lignes suivantes permettent de créer les figures en entête de cette courte documentation.

```python
import pycoa.pycoa as pc
pc.plot(where=['France', 'Italy', 'United kingdom'], which='deaths', what='cumul')
pc.map(where=['world'])
pc.hist(where='middle africa', which='confirmed')
pc.get(where=['usa'], what='daily', which='recovered')
```

PyCoA fonctionne :
- sur une installation locale de Python™ comme [`Spyder`](https://www.spyder-ide.org/),
- sur des plateforme `Jupyter` en ligne, comme [`Google Colab`](https://colab.research.google.com/),
- ou même avec un `docker`, comme [`mybinder`](https://mybinder.org/).

Un code de démonstration est accesible comme : 
- [notebook Jupyter](https://github.com/pycoa/pycoa-notebooks)
- [fichier `.py`](https://github.com/pycoa/py)

**-> Là il faut changer les liens pour pointer vers un unique demo code**

La documentation complète se trouve sur [le Wiki](https://github.com/pycoa/wiki/Home).

### Auteurs

* Tristan Beau - [Université de Paris](http://u-paris.fr) - [LPNHE laboratory](http://lpnhe.in2p3.fr/)
* Julien Browaeys - [Université de Paris](http://u-paris.fr) - [MSC laboratory](http://www.msc.univ-paris-diderot.fr/)
* Olivier Dadoun - [CNRS](http://cnrs.fr) - [LPNHE laboratory](http://lpnhe.in2p3.fr/)

---
<!-- 
<section id="downloads" class="clearfix">
  <a href="https://github.com/tjbtjbtjb/pycoa/zipball/main" id="download-zip" class="button"><span>Download .zip</span></a>
  <a href="https://github.com/tjbtjbtjb/pycoa/tarball/main" id="download-tar-gz" class="button"><span>Download .tar.gz</span></a>
  <a href="https://github.com/tjbtjbtjb/pycoa/" id="view-on-github" class="button"><span>View on GitHub</span></a>
</section>~~
-->
