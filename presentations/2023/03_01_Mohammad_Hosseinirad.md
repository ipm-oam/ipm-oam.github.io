---
layout: page
title: IPM-OAM presentation
subtitle: 
#menubar: docs_menu
show_sidebar: false
#toc: true
---

### Writing faster python codes in a controlled version Jupyter notebook + HPC discussion
#### Mohammad Hosseinirad (IPM)
**1 March 2023**

---

We (as astronomers) use python in our everyday research. Python is a very powerful tool but as it's an interpreted programming language, it's slow in comparison with the compiled ones. Also many of us use Jupyter in their research to combine their codes with their plots in a more unified manner, but this raises another problem: How can we use the nice tool git for version control of our Jupyter notebooks? OK, now we know how to write a much faster python code within a Jupyter notebook, but where can I run my notebook? Where is the standard infrastructure HPC?

In this talk I will try to introduce some tools to solve the first two challenges and also discuss the last one.

**Resources:**
- [Jupytext](https://jupytext.readthedocs.io/en/latest/index.html)
- [Numba](https://numba.readthedocs.io/en/stable/)
- [A simple Numba test (Monte Carlo integration)](https://gist.github.com/smhr/1a73cc7ce1071c47d6a01d62186d2dac). See also the original reference of the codes [here](https://www.infoworld.com/article/3622013/speed-up-your-python-with-numba.html).
