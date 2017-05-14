# Python教育资源大全中文版

*Python教育方面的资源列表*

有许多方式为本项目提交贡献. 你可以从[这儿](CONTRIBUTING.md)开始.

当前资源的遵循的协议是[CC0](LICENSE).

ps: 本列表翻译自[awesome-python-in-education](https://github.com/quobit/awesome-python-in-education)

Awesome-XXX 是GitHub上知名的一组项目，其主页：[Awesome 清单](https://github.com/sindresorhus/awesome/blob/master/awesome.md)

近期我在关注编程在教育中的现状和资源，于是找到这份资源列表，其中许多项目我都有在使用,对于我不熟悉的项目，我都将亲手试用一遍，并给上我的评价和使用体验,也欢迎交流

## 目录

* [课程](#courses-and-lessons)
  * [交互式编程环境](#interactive-environments)
  * [慕课](#moocs)
  * [介绍和教程](#introductions-and-tutorials)
    * [数据科学](#data-science)
* [练习和游戏](#exercises-and-games)
* [参考和论坛](#reference-and-forums)
  * [教育中Python的适用性](#python-suitability-for-education)
  * [参考](#reference)
  * [邮件列表](#mailing-lists)
  * [论坛](#forums)
* [工具与库](#tools-and-libraries)
  * [游戏，图形与仿真](#games-graphics-and-simulation)
  * [可视化](#visualization)
  * [Jupyter](#jupyter)
  * [IDEs](#ides)
  * [调试器](#debuggers)
* [会议与视频](#conferences-and-videos)
* [书籍](#books) (以下是出版社的名字，不译)
  * [Coding Club books](#coding-club-books)
  * [Green Tea Press](#green-tea-press)
  * [Invent with Python series](#invent-with-python-series)
  * [Manning Publications](#manning-publications)
  * [No Starch Press](#no-starch-press)
  * [O'Reilly](#oreilly)
  * [Packt Pub](#packt-pub)
* [硬件](#hardware)
  * [树莓派](#raspberry-pi)
  * [Arduino](#arduino)
  * [BBC micro:bit](#bbc-microbit)
  * [Pyboard](#pyboard)

## 课程

### 交互式编程环境

* [通过Trinket进行积木化的编程](https://hourofpython.com/from-blocks-to-code-with-trinket/) (更多资源参见 [Hour of Python](https://hourofpython.com/)) - 通过blockly来进行积木化的编程，并生成python代码(ps:我最近就在做此类事情，blockly是非常强大的工具，我试图将这个思路拓展到硬件和AI上)
* [Python for Everybody](https://books.trinket.io/pfe/) - trinket.io 交互式书籍
* [如何像计算机科学家一样思考](http://interactivepython.org/courselib/static/thinkcspy/index.html) (更多资源参见 [Runestone Interactive](http://runestoneinteractive.org/library.html))
* [pythonroom](https://pythonroom.com/) - pythonroom让大家轻松进行计算机科学教学
* [repl.it classrooms](https://repl.it/site/classrooms) - 专门为老师准备的新工具
* [CS Principles: Big Ideas in Programming](http://interactivepython.org/runestone/static/StudentCSP/index.html): 这本电子书非常有趣,它通过Python来教你编程,让你多读代码而不是一来就让你开始写，你无需安装任何东西在浏览器里就可以开始你的编程之旅
* [CodeSkulptor](http://www.codeskulptor.org/) - 使用[skulpt](https://github.com/skulpt/skulpt)在浏览器中跑Python,你可以在其中可视化地看待代码的执行过程
* [BlockPy](http://think.cs.vt.edu/blockpy/) - 基于web的编程环境，让你能同时使用blockly积木块和代码来编程，为数据科学而生
* [Edublocks](http://edublocks.org/) - 使 Scratch 到 Python 的转化更加容易
* [Python Lectures](https://github.com/rajathkumarmp/Python-Lectures) - 在IPython Notebooks中学习Python,十分理想的学习环境
* [Learn Python](http://www.learnpython.org/) - 一个在线学习Python的电子教程，同样是只要有浏览器就行
* [Code Club Python modules](https://www.codeclubprojects.org/en-GB/python/) - 使用trinket.io来教学Python,教学案例的设计有趣而用心
* [Computer Science Circles](http://cscircles.cemc.uwaterloo.ca/) - 一本学习Python的电子教程，你将跟着教材在浏览器中做练习,可以用可视化的方式看到代码的执行过程
* [Python from scratch](https://open.cs.uwaterloo.ca/python-from-scratch/) - 一门完整的课程，包括了视频讲解和线上练习
* [以交互式的方式通过100多个练习来学习Python3](https://snakify.org/) - 
* [Codesters](https://www.codesters.com/) - 这是一个非常完整的解决方案，你可以在学校里使用它,包含了编程平台、学习管理系统和课程，另外值得一提的是里边的例子都非常有意思

### 慕课

* [大家的编程 (Python 入门)](https://www.coursera.org/learn/python) - coursera上的一门Python入门课,课程对学生没有先设要求,用户评分4.8
* [Python 交互式编程导论（第1部分）](https://www.coursera.org/learn/interactive-python-1) - coursera上的一门课,课程的第1部分中，介绍编程的基本元素（如表达式，条件和函数），然后使用这些元素创建简单的交互式应用程序
* [Python 交互式编程导论（第2部分）](https://www.coursera.org/learn/interactive-python-2) - 课程的第2部分中，将介绍更多的编程元素（如列表，词典和循环），然后使用这些元素来创建诸如21点游戏
* [Python Programming: A Concise Introduction](https://www.coursera.org/learn/python-programming-introduction) - coursera上的一门课,这门课程将展示如何安装Python并使用Spyder IDE（集成开发环境）编写和调试程序（python3.x）
* [Introduction to Computer Science and Programming Using Python](https://www.edx.org/course/introduction-computer-science-mitx-6-00-1x-9) - edx上的一门课，本课是一门计算机科学的导论课，主要教授解决真实世界中的分析问题的方法。旨在帮助没有计算机科学及编程学习经验的人，培养他们的计算思维，并且编写程序来解决一些实用的问题
* [Learn to Program Using Python](https://www.edx.org/course/learn-program-using-python-utarlingtonx-cse1309x) -edx上的一门课，本课程的练习将基于与现实问题相关的小任务。
* [CS For All: Introduction to Computer Science and Python Programming](https://www.edx.org/course/cs-all-introduction-computer-science-harveymuddx-cs005x-0) - 通过各种各样的演示和项目来对计算机科学领域有一个广泛的认识
* [编程基础：Python](https://www.udacity.com/course/programming-foundations-with-python--ud036) - udacity 上的一门课,在此入门级编程课程中，你将学习软件工程师必须掌握的一门技能——面向对象编程方法.你将编写服务器端代码，以便存储你喜爱的电影，包括电影海报和预告片网址。然后将这些数据当做网页来投放，并允许访问者评论电影和观看预告片。
* [Python Codecademy](https://www.codecademy.com/learn/python) - Codecademy是一个在线交互式网站平台，它提供免费编程课堂,有大量用户在上边做练习
* [CS 61A: The Structure and Interpretation of Computer Programs](http://cs61a.org/) - CS 61系列是对计算机科学的介绍，特别强调站在软件和程序员的角度来看机器.这门课的课程表会给你在校学习的感觉
* [Python School](https://pythonschool.net/) -  Python School 为ICT(信息通讯技术)教师提供了一种在学校教授计算机/计算机科学所需的知识和技能的途径。
* [Let’s all build a comprehensive interactive Python curriculum together](https://forum.freecodecamp.com/t/lets-all-build-a-comprehensive-interactive-python-curriculum-together/103979) - 来自FreeCodeCamp.com的一份学习资源:让我们一起构建一个全面的交互式Python课程

### 介绍和教程

* [The Hello World Program: Learn Python](https://thehelloworldprogram.com/python/)
* [Introduction to Python](http://introtopython.org/)
* [NewCoder](http://newcoder.io/)
* [Python tutorial](https://pythonspot.com/)
* [Programming with Python](http://swcarpentry.github.io/python-novice-inflammation/) - from [Software Carpentry](http://software-carpentry.org/)
* [Introduction to Programming with Python](http://opentechschool.github.io/python-beginners/en/index.html)
* [Python Course](http://www.python-course.eu/)
* [The Programming Historian](http://programminghistorian.org/lessons/)
* [Program Arcade Games With Python And Pygame](http://www.programarcadegames.com/)
* [Python Tutorials for Kids 13+](https://python4kids.brendanscott.com/)
* [Python Asynchronous I/O Walkthrough](http://pgbovine.net/python-async-io-walkthrough.htm)
* [Python Tutorials and Courses Directory](https://hackr.io/tutorials/learn-python)
* [Python as a Second Language](https://swcarpentry.github.io/python-second-language/)
* [A simple tutorial about effectively using pdb](https://github.com/spiside/pdb-tutorial)
* [Beginning Python](http://archive.oreilly.com/oreillyschool/courses/Python1/index.html) - [Getting More out of Python](http://archive.oreilly.com/oreillyschool/courses/Python2/index.html) - [The Python Environment](http://archive.oreilly.com/oreillyschool/courses/Python3/index.html) - [Advanced Python](http://archive.oreilly.com/oreillyschool/courses/Python4/index.html) - 4 courses from the archived O'Reilly School of Technology
* [Testing and Continuous Integration with Python](http://katyhuff.github.io/python-testing/) - a tutorial from the Software Carpentry
* [Python Tutorials](https://pythonspot.com/en/)

#### 数据科学

* [A Whirlwind Tour of Python](http://www.oreilly.com/programming/free/a-whirlwind-tour-of-python.csp) and the [Jupyter Notebooks](https://github.com/jakevdp/WhirlwindTourOfPython) behind.
* [A Crash Course in Python for Scientists](http://nbviewer.jupyter.org/gist/rpmuller/5920182)
* [Intro to Python for Data Science](https://www.datacamp.com/courses/intro-to-python-for-data-science)
* [Learning Python for Data Science](http://www.datasciencecentral.com/profiles/blogs/learning-python-for-data-science)
* [Introduction to Python for Data Science](https://www.edx.org/course/introduction-python-data-science-microsoft-dat208x-5)
* [Programming with Python for Data Science](https://www.edx.org/course/programming-python-data-science-microsoft-dat210x-3)
* [Python Data Science Handbook](https://github.com/jakevdp/PythonDataScienceHandbook) complete book in Jupyter Notebook format
* [Exploratory Computing with Python](http://mbakker7.github.io/exploratory_computing_with_python/)
* [Data Carpentry: Python for Ecologists](http://www.datacarpentry.org/python-ecology-lesson/)
* [Plotting and Programming in Python](http://swcarpentry.github.io/python-novice-gapminder/)
* [Applied Plotting, Charting & Data Representation in Python](https://www.coursera.org/learn/python-plotting)
* [Using Python for Research](https://www.edx.org/course/using-python-research-harvardx-ph526x)

## 练习和游戏

* [CheckiO](https://checkio.org/)
* [CodeAbbey](http://www.codeabbey.com/)
* [Empire of Code](https://empireofcode.com/)
* [Project Euler](https://projecteuler.net/)
* [Exercism](http://exercism.io/languages/python/)
* [HackerRank Challenges](https://www.hackerrank.com/domains/python/py-introduction)
* [PyBites](http://pybit.es/)
* [Practice Python](http://www.practicepython.org/)
* [Python Challenge](http://www.pythonchallenge.com/)
* [Python for Fun](http://openbookproject.net/py4fun/)
* [CodingBat](http://codingbat.com/python)
* [Reeborg's world](http://reeborg.ca/index_en.html)
* [Python Koans](https://github.com/gregmalcolm/python_koans)
* [Boston Python Puzzles](http://puzzles.bostonpython.com/)
* [Python Koans](https://github.com/gregmalcolm/python_koans)
* [Code & Conquer](http://www.codeandconquer.co/)
* [CodeCombat](https://codecombat.com/)
* [TeachCraft-Challenges](https://github.com/teachthenet/TeachCraft-Challenges)
* [Slice like a Ninja](http://briandavidhall.com/slice_like_a_ninja/)
* [Python Datasets: The Collection of Really Great, Interesting, Situated Datasets](https://think.cs.vt.edu/corgis/python/index.html) - (visit [CORGIS](https://think.cs.vt.edu/corgis/) for raw formats)
* [Interactive Coding Challenges](https://github.com/donnemartin/interactive-coding-challenges)
* [Pyweek Programming Challenge](https://pyweek.org/)

## 参考和论坛

### Python在教育中的适用性

* [CP4E](https://www.python.org/doc/essays/cp4e/) by Guido van Rossum
* [Python in Education: Teach, Learn, Program](http://www.oreilly.com/programming/free/python-in-education.csp) - free e-book on why Python is well suited for education by Nicholas Tollervey
* ['Think Python like a Computer Scientist' book Foreword](http://interactivepython.org/courselib/static/thinkcspy/FrontBackMatter/foreword.html) by David Beazley
* [Why I push for Python](http://lorenabarba.com/blog/why-i-push-for-python/) by Lorena Barba
* [Why Python is a Great First Language](http://blog.trinket.io/why-python/) by Elliott Hauser (Trinket CEO)
* [Why Python is a great language for teaching beginners in introductory programming classes](http://pgbovine.net/python-teaching.htm) by Philip Guo
* [Python is Now the Most Popular Introductory Teaching Language at Top U.S. Universities](http://cacm.acm.org/blogs/blog-cacm/176450-python-is-now-the-most-popular-introductory-teaching-language-at-top-u-s-universities/fulltext) by Philip Guo (Communications of the ACM)
* [Why Learn Python? Here Are 8 Data-Driven Reasons](https://dbader.org/blog/why-learn-python) by Elena Ruchko
* [[Level 1] Programming: Python](http://web.archive.org/web/20160122210606/http://nzacditt.org.nz/resources/programming-and-cs/level-1-programming-python) - Archived version
* [Python as a way of thinking](http://allendowney.blogspot.com/2017/04/python-as-way-of-thinking.html)
* [Academic Papers](papers.md)

### 参考

* [Official Python documentation](https://docs.python.org/3/)
* [Python in Education](http://pythonineducation.org/) - [git repo](https://github.com/python/pythonineducation.org)
* [Google's Python Class](https://developers.google.com/edu/python/)
* [The Hitchhiker’s Guide to Python](http://python-guide.org/)
* [Tiny Python 3.6 Notebook](https://github.com/mattharrison/Tiny-Python-3.6-Notebook/blob/master/python.rst)
* [First Steps With Python](https://realpython.com/learn/python-first-steps/)
* [PEP8 - Python Style Guide](http://pep8.org/)
* [The Elements of Python Style](https://github.com/amontalenti/elements-of-python-style)
* [PyMOTW3](https://pymotw.com/3/) - Python Module Of The Week
* [Full Stack Python](http://www.fullstackpython.com/table-of-contents.html) - [(best python resources)](https://www.fullstackpython.com/best-python-resources.html)
* [Learn X in Y minutes where X=python3](https://learnxinyminutes.com/docs/python3/)
* [PyCrumbs - Bits and bytes of Python from the Internet](https://github.com/kirang89/pycrumbs)
* [EduPython](http://edupython.co.uk/)
* [A gallery of interesting IPython Notebooks](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks)
* [CS1 Python Programming Projects Archive](http://www.cse.msu.edu/~cse231/PracticeOfComputingUsingPython/index.php)
* [Python cheatsheet](https://www.pythonsheets.com/)
* [Python Crash Course - Cheat Sheets](http://ehmatthes.github.io/pcc/cheatsheets/README.html)
* [Algorithms implemented in python (for education)](https://github.com/TheAlgorithms/Python)
* [Algorithms](https://github.com/nryoung/algorithms)
* [Minimal examples of data structures and algorithms in Python](https://github.com/keon/algorithms)
* [awesome-python](https://github.com/vinta/awesome-python)
* [Python GitHub Projects](https://github.com/checkcheckzz/python-github-projects)
* [pycrumbs](https://github.com/kirang89/pycrumbs)
* [Python Reference](https://github.com/rasbt/python_reference) - useful functions, tutorials, and other Python-related things 
* [Pythonidae](https://github.com/svaksha/pythonidae) - curated decibans of scientific programming resources in Python
* [python-patterns](https://github.com/faif/python-patterns) - a collection of design patterns/idioms in Python 
* [PyPattyrn](https://github.com/tylerlaberge/PyPattyrn)
* [Python 3 Patterns, Recipes and Idioms](http://python-3-patterns-idioms-test.readthedocs.io/)
* [How to make mistakes in Python](http://www.oreilly.com/programming/free/files/how-to-make-mistakes-in-python.pdf)  
* [Python Knowledge Base](https://www.quantifiedcode.com/knowledge-base/)
* [Python IAQ: Infrequently Answered Questions](http://norvig.com/python-iaq.html) by Peter Norvig
* [Anti-Patterns in Python Programming](http://lignos.org/py_antipatterns/)
* [DjangoGirls Introduction to Python](https://tutorial.djangogirls.org/en/python_introduction/)
* [Experiments in Python Pedagogy](https://github.com/4dsolutions/Python5) - [rendered version](http://nbviewer.jupyter.org/github/4dsolutions/Python5/tree/master/)
* [29 common beginner Python errors on one page](http://pythonforbiologists.com/index.php/29-common-beginner-python-errors-on-one-page/)
* [Learn Python - Udacity](https://www.udacity.com/learn/python)
* [Popular Python Recipes](http://code.activestate.com/recipes/langs/python/)
* [Transforming Code into Beautiful, Idiomatic Python](https://gist.github.com/JeffPaine/6213790)
* [Improve your Python skills (Dan Bader's blog)](https://dbader.org/blog/)
* [Practical Business Python](http://pbpython.com/)

### 邮件列表

* [Python EDU-SIG](https://www.python.org/community/sigs/current/edu-sig/) - Python.org subsite
* [Python EDU-SIG](https://mail.python.org/mailman/listinfo/edu-sig) - Special Interest Group mailing list
* [Python EDU-WG](https://mail.python.org/mailman/listinfo/pythonedu-wg) - Working Group mailing list
* [Tutor](https://mail.python.org/mailman/listinfo/tutor) - (mailing list) Discussion for learning programming with Python
* [Python-list](https://mail.python.org/mailman/listinfo/python-list) - General discussion list for the Python programming language (mailing list)

### 论坛

* StackOverflow: [dashboard](http://stackoverflow.com/documentation/python) - [all topics](http://stackoverflow.com/documentation/python/topics) - [tag python](http://stackoverflow.com/questions/tagged/python)
* reddit: [Python](https://www.reddit.com/r/Python/) - [Python Learning](https://www.reddit.com/r/learnpython/) - [Python tips](https://www.reddit.com/r/pythontips/) - [Pygame](https://www.reddit.com/r/pygame/)

## 工具与库

* [Your Python Trinket](https://trinket.io/python) - Put Interactive Python Anywhere on the Web
* [Python Tutor](http://pythontutor.com/) - Visualize the execution of Python programs
* [Skulpt](http://www.skulpt.org/) - Skulpt is an entirely in-browser implementation of Python 2.X (!)
* [SoloLearn Python 3 Tutorial](https://www.sololearn.com/Course/Python/) - mobile version 
* [Python Anywhere](https://www.pythonanywhere.com/details/education)
* [repl.it](https://repl.it/site/languages/python3)
* [Python AST Explorer](https://python-ast-explorer.com/)
* [kite](https://kite.com/) - programming copilot
* [EarSketch](https://earsketch.gatech.edu/) - learn to code by making music
* [Ren'Py](https://www.renpy.org/) - a visual novel engine

### 游戏，图形与仿真

* [PyGame](http://www.pygame.org/)
* [Pygame Zero](https://pygame-zero.readthedocs.io) for creating games without boilerplate
* [Python Arcade Library](http://pythonhosted.org/arcade/)
* [Pyglet](https://bitbucket.org/pyglet/pyglet/wiki/Home) - a pure python cross-platform application framework intended for game development
* [Python Mode for Processing](http://py.processing.org/)
* [PythonTurtle](http://pythonturtle.org/)
* [VPython](http://vpython.org/) - 3D programming
* [Pymunk](http://www.pymunk.org/) - 2D physics library
* [PyPhysicsSandbox](https://github.com/jshaffstall/PyPhysicsSandbox) - a simple wrapper around Pymunk
* [Kivy](https://kivy.org/) - innovative user interfaces, such as multi-touch apps
* [Panda3D](http://www.panda3d.org/) - game engine and framework for 3D rendering

### 可视化

* [Bokeh](http://bokeh.pydata.org/)
* [VisPy](http://vispy.org/)

### Jupyter

* [Project Jupyter](http://jupyter.org/)
* [Jupyter Notebook cheatsheet](https://www.cheatography.com/weidadeyue/cheat-sheets/jupyter-notebook/)
* [IPython widgets](https://github.com/ipython/ipywidgets)
* [nbgrader](http://nbgrader.readthedocs.io/) - nbgrader is a tool that facilitates creating and grading assignments in the Jupyter notebook.
* [nbval](https://github.com/computationalmodelling/nbval) - Py.test plugin for validating Jupyter notebooks.
* [nbdime](https://nbdime.readthedocs.io/) - diffing and merging of Jupyter Notebooks.
* [nbscan](https://github.com/conery/nbscan) - search for and print contents of cells in Jupyter notebooks.
* [nbconvert](https://nbconvert.readthedocs.io/) - convert Notebooks to other formats.
* [nbautoeval](https://github.com/parmentelat/nbautoeval) - creating auto-evaluated exercises.
* [nbtutor](https://github.com/lgpage/nbtutor) - visualize Python code execution (line-by-line).
* [jupyter-drive](https://github.com/jupyter/jupyter-drive) - Google Drive for Jupyter.
* [Jupyter tips, tricks and shortcuts](https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/)
* [Notebook Gallery](http://nb.bianp.net/sort/views/) - links to the best IPython and Jupyter Notebooks.
* [Custom Jupyter Notebook Themes](https://github.com/dunovank/jupyter-themes)
* [IPythonBlocks](http://ipythonblocks.org/)
* [Using the IPython Notebook as a Teaching Tool](https://software-carpentry.org/blog/2013/03/using-notebook-as-a-teaching-tool.html)
* [Teaching with Jupyter Notebooks](https://groups.google.com/forum/#!forum/jupyter-education) - mailing list.
* [JupyterLab computational environment](https://github.com/jupyterlab/jupyterlab) - not suitable for general usage yet.
* [binder](http://mybinder.org/) - turn a GitHub repo into a collection of interactive notebooks.
* [JupyterHub](https://github.com/jupyterhub/jupyterhub) - multi-user server for Jupyter notebooks
* [Lectures on scientific computing with Python](https://github.com/jrjohansson/scientific-python-lectures)
* ["The world of Jupyter" —a tutorial](https://github.com/barbagroup/jupyter-tutorial)
* [List of Jupyter Notebooks by Peter Norvig](http://norvig.com/ipython/)
* [28 Jupyter Notebook tips, tricks and shortcuts](https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/)

### IDEs

* [bpython](https://bpython-interpreter.org/)
* [ptpython](https://github.com/jonathanslenders/ptpython)
* [Thonny, Python IDE for beginners](http://thonny.cs.ut.ee/)
* [VIM](http://www.vim.org/) with [Python plugins](https://realpython.com/blog/python/vim-and-python-a-match-made-in-heaven/)
* [Emacs](https://www.gnu.org/software/emacs/) with [Python plugins](https://realpython.com/blog/python/emacs-the-best-python-editor/)
* [Sublime Text 3](http://www.sublimetext.com/3) with [Python plugins](https://realpython.com/blog/python/setting-up-sublime-text-3-for-full-stack-python-development/)
* [PyCharm Edu](https://www.jetbrains.com/pycharm-edu/) - With [some courses](https://github.com/JetBrains/pycharm-courses)
* [Spyder](https://github.com/spyder-ide/spyder) - The Scientific PYthon Development EnviRonment
* [Wingware Python IDE](https://wingware.com/)
* [Ninja-IDE](http://ninja-ide.org/)
* [PyDev](http://www.pydev.org/)
* [Visual Studio Code](https://code.visualstudio.com/) with [Python plugins](https://marketplace.visualstudio.com/items?itemName=donjayamanne.python)

### 调试器

* [pdb](https://docs.python.org/3/library/pdb.html)
* [ipdb](https://pypi.org/project/ipdb/)
* [PuDB](https://pypi.org/project/pudb/)
* [pdb++](https://bitbucket.org/antocuni/pdb/src)
* [Python Linter Online](http://pythonbuddy.com/) - Live Syntax Checking Using Pylint while Running Python
* [PyTA](https://github.com/pyta-uoft/pyta) - static code analysis to help students find and fix common coding errors
* [coala](http://coala.io/) - linting and fixing code

## 会议与视频

* [Weekly Python Chat](http://www.weeklypython.chat/) - Weekly live video chats about Python, teaching, open source, and more
* [Python in Australian Education seminar](https://2016.pycon-au.org/programme/python_in_education_seminar) (2016)
* [PyCon Australia 2015 Education Miniconf](https://www.youtube.com/playlist?list=PLs4CJRBY5F1I5vuApyUXp6bLWly1E-b0s) (youtube playlist)
* [Python Education Summit Schedule](https://us.pycon.org/2016/events/edusummit/schedule/) (PyCon 2016)
* [A one-day mini-conference about Python in Education](http://2016.pyconuk.org/teachers/) (PyConUK 2016)
* [PyVideo tag 'education'](http://pyvideo.org/tag/education/)
* [Khan Academy Computer Science (Python video playlist)](https://www.youtube.com/playlist?list=PL36E7A2B75028A3D6)
* [Python Programming in one video](https://www.youtube.com/watch?v=N4mEzFDjqtA) - [Learn to Program with Python](https://www.youtube.com/playlist?list=PLGLfVvz_LVvTn3cK5e6LjhgGiSeVlIRwt) Derek Banas playlist
* [CPython internals: A ten-hour codewalk through the Python interpreter source code](http://pgbovine.net/cpython-internals.htm)
* [Teaching Python: The Hard Parts](http://pyvideo.org/pycon-us-2016/elana-hashman-teaching-python-the-hard-parts-pycon-2016.html) - PyCon 2016
* [Episode 14 – Allen Downey on Teaching Computer Science with Python](https://www.podcastinit.com/episode-14-allen-downey-on-teaching-computer-science-with-python/) from [podcast.\__init__('Python')](https://www.podcastinit.com/)
* [Python For Informatics](https://www.youtube.com/playlist?list=PLlRFEj9H3Oj4JXIwMwN1_ss1Tk8wZShEJ)
* [Python for Everybody - Exploring Information](https://www.youtube.com/playlist?list=PLlRFEj9H3Oj7Bp8-DfGpfAfDBiblRfl5p)
* [sentdex youtube playlists](https://www.youtube.com/user/sentdex/playlists) or via [Python Programming](https://pythonprogramming.net/)
* [Dan Bader's youtube channel](https://dbader.org/youtube/)
* [Python 3.4 Programming Tutorials](https://www.youtube.com/playlist?list=PL6gx4Cwl9DGAcbMi1sH6oAMk4JHw91mC_)
* [Programming Foundations with Python](https://www.youtube.com/playlist?list=PLAwxTw4SYaPnYajEbZvqtcVWQ6XGhvtOW) from [Udacity](https://www.udacity.com/course/ud036)
* [PySide Video Tutorials](http://wiki.qt.io/PySide_Video_Tutorials)
* [Python Basics - Coding is for girls](https://www.youtube.com/playlist?list=PLbd_WhypdBbAMyFfKgSj27JO7CEpuIcEK)
* [Python For Beginners - Learn To Code Tutorials ](https://www.youtube.com/playlist?list=PLW_tdZJKynZXgLKQAR2g52ut4c2IpUmOv)
* [TheNewBoston Python 3 videotutorials](https://thenewboston.com/videos.php?cat=98) - also [Flask](https://thenewboston.com/videos.php?cat=362) and others
* [Build applications in Python the antitextbook](https://www.youtube.com/playlist?list=PL41psiCma00wwvtQyLFMFpzWxUYmSZwZy)
* [Socratica Python Programming Tutorials](https://www.youtube.com/playlist?list=PLi01XoE8jYohWFPpC17Z-wWhPOSuh8Er-)
* [Python for Data Analysis - Pandas Cookbook](https://www.youtube.com/playlist?list=PLyBBc46Y6aAz54aOUgKXXyTcEmpMisAq3)

## 书籍

* [The Computer Science Field Guide](http://www.csfieldguide.org.nz/en/) - ([repo](https://github.com/uccser/cs-field-guide))
* [Awesome Python Books](https://github.com/Junnplus/awesome-python-books)
* [PythonBooks](http://pythonbooks.revolunet.com/)
* [Build applications in Python the antitextbook](http://github.com/thewhitetulip/build-app-with-python-antitextbook)
* [Algorithmic Problem Solving with Python](http://www.eecs.wsu.edu/~schneidj/PyBook/swan.pdf)
* [Openlibra: Python](https://openlibra.com/en/collection/search/category/python/language/english/)
* [Python Practice Book](http://anandology.com/python-practice-book/)
* [Scipy Lecture Notes](http://www.scipy-lectures.org/)
* [Natural Language Processing with Python](http://www.nltk.org/book/)
* [Problem Solving with Algorithms and Data Structures using Python](http://interactivepython.org/courselib/static/pythonds/index.html)
* [Python for Everybody - Exploring Data In Python 3](http://www.py4e.com/book)
* [Composing Programs](http://composingprograms.com/)
* [Dive into Python 3](http://getpython3.com/diveintopython3/)
* [Introduction to Programming with Python](http://opentechschool.github.io/python-beginners/en/)
* [Learn Python, Break Python - A Beginner's Guide to Programming](http://learnpythonbreakpython.com/)
* [Learn Python3 in Y minutes](https://learnxinyminutes.com/docs/python3/)
* [Non-Programmer's Tutorial for Python 3](https://en.wikibooks.org/wiki/Non-Programmer%27s_Tutorial_for_Python_3)
* [The Art and Craft of Programming (Python edition)](http://troll.cs.ua.edu/ACP-PY/)
* [Program Arcade Games With Python And Pygame](http://programarcadegames.com/)
* [Python for you and me](http://pymbook.readthedocs.io/en/py3/)
* [Object-Oriented Programming in Python](http://python-textbok.readthedocs.io)
* [Violent Python. A Cookbook for Hackers, Forensic Analysts, Penetration Testers and Security Engineers](http://store.elsevier.com/Violent-Python/TJ-OConnor/isbn-9781597499576/)

### Coding Club books

* [Python Basics](http://www.codingclub.co.uk/book1_home.php)
* [Python Next Steps](http://www.codingclub.co.uk/book2_home.php)
* [Python: Building Big Apps](http://www.codingclub.co.uk/book3_home.php)
* [Python: Programming Art](http://www.codingclub.co.uk/book4_home.php)
* [Python: Interactive Adventures](http://www.codingclub.co.uk/book5_home.php)
* [Black Flag: A Coding Club Mission](http://www.codingclub.co.uk/black_flag.php)
* [Coding Cards](http://www.codingclub.co.uk/codecards/CC-CodeCards.pdf) [PDF]

### Green Tea Press

* [Think Python: How To Think Like a Computer Scientist, 2nd ed.](http://greenteapress.com/thinkpython2/html/)
* [Think Complexity: Exploring Complexity Science with Python, 2nd ed.](http://greenteapress.com/complexity2/html/)
* [Think DSP: Digital Signal Processing in Python](http://greenteapress.com/thinkdsp/html/)
* [Think Stats: Exploratory Data Analysis in Python, 2nd ed.](http://greenteapress.com/thinkstats2/html/)
* [Think Bayes: Bayesian Statistics in Python](http://www.greenteapress.com/thinkbayes/html/)

### Invent with Python series

* [Invent your own computer games with Python](https://inventwithpython.com/)
* [Making Games with Python & Pygame](https://inventwithpython.com/pygame/)
* [Hacking Secret Ciphers with Python](http://inventwithpython.com/hacking/)
* [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/)

### Manning Publications

* [Hello! Python](https://www.manning.com/books/hello-python)
* [Hello World! 2nd ed. Computer Programming for Kids and Other Beginners](https://www.manning.com/books/hello-world-second-edition)
* [Hello Raspberry Pi!](https://www.manning.com/books/hello-raspberry-pi) - Python programming for kids and other beginners.
* [The Quick Python Book, Third Edition](https://www.manning.com/books/the-quick-python-book-third-edition)
* [Learn Programming with Python](https://www.manning.com/books/learn-programming-with-python)
* [Grokking Algorithms](https://www.manning.com/books/grokking-algorithms) - An illustrated guide for programmers and other curious people.

### No Starch Press

* [Python for Kids](https://www.nostarch.com/pythonforkids)
* [Teach Your Kids to Code](https://www.nostarch.com/teachkids)
* [Doing Math with Python: Use Programming to Explore Algebra, Statistics, Calculus, and More!](https://www.nostarch.com/doingmathwithpython)
* [Python Crash Course. A Hands-On, Project-Based Introduction to Programming](https://www.nostarch.com/pythoncrashcourse)
* [Python Playground. Geeky Projects for the Curious Programmer](https://www.nostarch.com/pythonplayground)
* [Learn to Program with Minecraft. Transform Your World with the Power of Python](https://www.nostarch.com/programwithminecraft)
* [Black Hat Python. Python Programming for Hackers and Pentesters](https://www.nostarch.com/blackhatpython)

### O'Reilly

* [Raspberry Pi Cookbook. Software and Hardware Problems and Solutions](http://shop.oreilly.com/product/0636920045182.do)
* [Head First Python, 2nd Edition](http://shop.oreilly.com/product/0636920036777.do)
* [Python for Unix and Linux System Administration](http://shop.oreilly.com/product/9780596515829.do) (2008)

### Packt Pub

* [Python Projects for Kids](https://www.packtpub.com/application-development/python-projects-kids)
* [Raspberry Pi Projects for Kids](https://www.packtpub.com/hardware-and-creative/raspberry-pi-projects-kids-second-edition)
* [Python Programming for Arduino](https://www.packtpub.com/application-development/python-programming-arduino)
* [Pro Python System Administration](http://www.apress.com/us/book/9781430226055) (2010)

## 硬件

* [Cozmo](https://developer.anki.com/)

### 树莓派

* [Raspberry Pi](https://www.raspberrypi.org/)

  * [Getting Started with Minecraft Pi](https://www.raspberrypi.org/learning/getting-started-with-minecraft-pi/)
  * [Create a "Whac-a-block" game in Minecraft](https://www.raspberrypi.org/learning/minecraft-whac-a-block-game/)
  * [MagPi issues](https://www.raspberrypi.org/magpi-issues/)

* [The Raspberry Pi Platform and Python Programming for the Raspberry Pi](https://www.coursera.org/learn/raspberry-pi-platform)

### Arduino

* [Arduino and Python](http://playground.arduino.cc/Interfacing/Python)
* [Using Python with Arduino](http://www.toptechboy.com/using-python-with-arduino-lessons/)

### BBC microbit

* [The micro:bit Foundation](http://microbit.org/)
* [BBC micro:bit MicroPython](https://microbit-micropython.readthedocs.io)

### PyBoard

* [MicroPython](http://micropython.org/)
