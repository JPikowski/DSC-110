# DSC 110 - Survey of Software Tools

TechStack topics for computational (and data) scientists.  The list of topics (see topics folder) is incomplete.  The course was inspired by (i) a summer course run by [Dr. Ed Overman at Ohio State University](https://math.osu.edu/people/overman.2) and (ii) [MIT - The Missing Semester](https://missing.csail.mit.edu). Edited from [dsc-techstack](https://github.com/jamesquinlan/dsc-techstack) by James Quinlan, Ph.D.


## Course description

This course facilitates the development of proficiency with the tools of computational and data science. Critical topics about the computing ecosystem that could make students’ lives significantly easier are covered. These topics include but are not limited to the command-line, the use of text editors, and version control systems. Students will spend hundreds of hours using these tools throughout their education (and possibly thousands over their careers). Mastering such tools enables students to be more efficient at the problem-solving process and provides unique knowledge and skills.


## Learning Outcomes
After successful completion of this course, the student will:

1. demonstrate benefits of virtual machines
2. navigate directories using the command line and automate common computer tasks
3. typeset basic mathematical notation
4. use Git: initialize, clone, commit, push
5. create a professional LinkedIn profile
6. consider data ethics issues
7. examine computer security and privacy issues



## Topics

1. [VMs & Linux Distro](topics/topic_01_vm.md)
2. [Shell Commands](topics/topic_02_shell.md)
3. [Shell & Scripting](topics/topic_03_scripting.md)
4. [Python & Colab](topics/topic_04_python.md)
5. [R & Rstudio](topics/topic_05_rstudio.md)
6. [Markdown](topics/topic_06_markdown.md)
7. [LaTeX](topics/topic_07_latex.md)
8. [Version Control (git)](topics/topic_08_git.md)
9. [Github](topics/topic_09_github.md)
10. [Data Ethics](topics/topic_10_ethics.md)
11. [LinkedIn](topics/topic_11_linkedin.md)
12. [Desmos & GeoGebra](topics/topic_12_desmos.md)
13. [Amazon AWS](topics/topic_13_aws.md)


<!-- 14. [Virtualization](topics/) -->
<!-- 15. [Unix](topics/unix.md) -->
<!-- 16. [File permissions](topics/chmod.md) -->
<!-- 3. [GitHub](topics/github.md) -->
<!-- 6. [R](topics/r.md) -->
<!-- 10. [Privacy and Security](topics/vpn.md) -->


## Contributing guidelines

All contributions are more than welcome. Contributions may close an issue, fix a bug (reported or not reported), add new design blocks, improve the existing code, add new features, and so on. In the interest of fostering an open and welcoming environment, we as contributors and maintainers pledge to make participation in our project and our community a harassment-free experience for everyone, regardless of age, body size, disability, ethnicity, gender identity, and expression, level of experience, nationality, personal appearance, race, religion, or sexual identity and orientation. [Read the full Code of Conduct](https://github.com/jamesquinlan/dsc-techstack/blob/main/CODE_OF_CONDUCT.md).

The `dev` branch is the project's default and base branch. It is used for development, and all Pull Requests should go there.



#### Get code

```bash
git clone https://github.com/JPikowski/DSC-110.git
cd DSC-110
```


## Copyright and License

Code and documentation copyright 2023 [Quinlan](https://github.com/jamesquinlan). The code was released under the [MIT License](https://github.com/jamesquinlan/dsc-techstack/blob/main/LICENSE).


## References

```BibTeX
@book{blum2008linux,
  title          = {Linux command line and shell scripting bible},
  author         = {Blum, Richard},
  volume         = {481},
  year           = {2008},
  publisher      = {John Wiley \& Sons}
}

@book{chacon2014pro,
  title          = {Pro git},
  author         = {Chacon, Scott and Straub, Ben},
  year           = {2014},
  publisher      = {Springer Nature}
}

@book{cone2020markdown,
  title         = {Markdown Guide},
  author        = {Cone, Matt},
  year          = {2020},
  publisher     = {Independently Published}
}

@misc{david2018aws,
  title         = {AWS: Amazon Web Services Tutorial for Beginners},
  author        = {David, Bert},
  year          = {2018},
  publisher     = {Independently published}
}

@incollection{del2021introducing,
  title         = {Introducing Visual Studio Code},
  author        = {Del Sole, Alessandro},
  booktitle     = {Visual Studio Code Distilled: Evolved Code Editing for Windows, macOS, and Linux},
  pages         = {1--15},
  year          = {2021},
  publisher     = {Springer}
}

@article{ebert2014graphing,
  title        = {Graphing projects with Desmos},
  author       = {Ebert, David},
  journal      = {The Mathematics Teacher},
  volume       = {108},
  number       = {5},
  pages        = {388--391},
  year         = {2014},
  publisher    = {National Council of Teachers of Mathematics}
}

@article{herschel2017ethics,
  title        = {Ethics \& big data},
  author       = {Herschel, Richard and Miori, Virginia M},
  journal      = {Technology in Society},
  volume       = {49},
  pages        = {31--36},
  year         = {2017},
  publisher    = {Elsevier}
}

@book{lakshman2011linux,
  title        = {Linux shell scripting cookbook},
  author       = {Lakshman, Sarath and Tushar, S},
  year         = {2011},
  publisher    = {Packt Publishing}
}

@book{lamport1991latex,
  title        = {LaTeX},
  author       = {Lamport, Leslie},
  year         = {1991},
  publisher    = {{\'S}Company Cyfronet}
}

@book{mcdonnell2014pro,
  title        = {Pro vim},
  author       = {McDonnell, Mark},
  year         = {2014},
  publisher    = {Apress}
}

@article{oracle2011virtualbox,
  title        = {VirtualBox user manual},
  author       = {Oracle, VM},
  journal      = {Oracle Corporation.-2004.-C},
  volume       = {357},
  year         = {2011}
}

@misc{kernighan2020c,
  title        = {The C programming language.},
  author       = {Kernighan, Brian W and Ritchie, Dennis M},
  year         = {2020},
  publisher    = {Prentice Hall}
}

@misc{richardson2007beautiful,
  title        = {Beautiful soup documentation},
  author       = {Richardson, Leonard},
  year         = {2007},
  publisher    = {April},
  url          = {https://buildmedia.readthedocs.org/media/pdf/beautiful-soup-4/latest/beautiful-soup-4.pdf}
}

@book{tsitoara2020beginning,
  title        = {Beginning Git and GitHub},
  author       = {Tsitoara, Mariot},
  year         = {2020},
  publisher    = {Springer}
}

@article{van2017personality,
  title        = {Personality perception based on LinkedIn profiles},
  author       = {Van de Ven, Niels and Bogaert, Aniek and Serlie, Alec and Brandt, Mark J and Denissen, Jaap JA},
  journal      = {Journal of Managerial Psychology},
  volume       = {32},
  number       = {6},
  pages        = {418--429},
  year         = {2017},
  publisher    = {Emerald Publishing Limited}
}

@book{xie2020r,
  title        = {R markdown cookbook},
  author       = {Xie, Yihui and Dervieux, Christophe and Riederer, Emily},
  year         = {2020},
  publisher    = {CRC Press}
}

@book{xie2018r,
  title        = {R markdown: The definitive guide},
  author       = {Xie, Yihui and Allaire, Joseph J and Grolemund, Garrett},
  year         = {2018},
  publisher    = {CRC Press}
}

```


