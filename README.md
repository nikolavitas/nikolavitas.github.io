
## Numerical Recipes for Stellar Atmospheres

The repositories here contain various routines for modeling stellar atmospheres from the first principles. Modeling atmospheres in 1D and 3D is intrinsically similar in terms of involved physics, the two tasks are very different in terms of required computing time. The 1D problem is solvable even in a slow script language as IDL (or Python), while for 3D it is necessity to write codes in parallel Fortran. An obvious advantage of having 1D routines in IDL equivalent to their 3D counterparts in Fortran is that IDL code is much easier to debug and the results can be directly visualize, so it is an excellent tool for prototyping and performing simple experiments. Another advantage of IDL is that its syntax is rather similar to the syntax of Fortran and thus the translation of the code form one to another is fairly quick and simple.

Most of the routines are described in detail in various posts in my blog
[http://nikolavitas.blogspot.com](http://nikolavitas.blogspot.com) and ![Image](<img src="https://lh3.googleusercontent.com/DUWUBR2NfQ7chKbADahZA8mfxBWr1uqtuoeO5F1PWHH3EsV1bCHCeu2enOaHie3EJPBEyjFU2JMg2tOXHUTrpYguQawO6Zxo2OsXka8p=s288-no" jsname="tEADhd" style="max-width: 288px; max-height: 288px; width: 506px; height: 506px;" alt="Photo: " data-iml="4415" data-atf="false">)
```
---

Nikola Vitas
