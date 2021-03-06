<!-- [Pycoa Logo](fig/pycoa_logo.png) -->

<img src="fig/pycoa_plot_example.png" width="200px"> <img src="fig/pycoa_map_example.png" width="200px"> <img src="fig/pycoa_hist_example.png" width="200px"> <img src="fig/pycoa_get_example.png" width="200px">

# PyCoA release 1.0

April/November 2020

[<img src="fig/UK.png" height="14px" alt="UK flag"> English  version ](https://tjbtjbtjb.github.io/pycoa) / 
[ <img src="fig/FR.png" height="14px" alt="FR flag"> Version française ](https://tjbtjbtjb.github.io/pycoa/index_FR)


`PyCoA` (Python Covid Analysis) is a Python™ framework which provides:
- a simple access to common Covid-19 databases;
- tools to represent and analyse Covid-19 data such as time series plots and maps.

It is designed to be accessible to non-specialists: teenagers learning Python™, students, science journalists, even scientists who are not familiar in data access methods. A simple analysis can be performed out of the box, as well as a more complex analysis for people familiar with Python™ programming. As an example, after installing [pycoa install](https://github.com/tjbtjbtjb/pycoa/wiki/Install) to your framework, the following few lines of code produce the four figures introducing this short documentation.

```python
import pycoa.pycoa as pc
pc.plot(where=['France', 'Italy', 'United kingdom'], which='deaths', what='cumul')
pc.map(where=['world'])
pc.hist(where='middle africa', which='confirmed')
pc.get(where=['usa'], what='daily', which='recovered')
```

PyCoA works:
- on a local install of Python™ such as [`Spyder`](https://www.spyder-ide.org/),
- on an online `Jupyter` platforms, such as [`Google Colab`](https://colab.research.google.com/),
- or even through a `docker`, using for example [`mybinder`](https://mybinder.org/).

Demo code is available: 
- as [notebooks](https://github.com/tjbtjbtjb/pycoa/tree/main/notebooks)
- as [`py` files](https://github.com/tjbtjbtjb/pycoa/tree/main/py)

**-> Là il faut changer les liens pour pointer vers un unique demo code**

Full documentation is on [the Wiki](https://github.com/tjbtjbtjb/pycoa/wiki/Home).

### Authors

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
