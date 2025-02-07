# The Docker Handbook

![](docker-handbook-preview.png)

The concept of containerization itself dates back to the nineties with the development of [`cgroups`](https://www.kernel.org/doc/html/latest/admin-guide/cgroup-v1/cgroups.html) in Unix, which Google put to use in scale in the early two thousands.

In 2008 `cgroups` got merged into the Linux kernel and paved the way for the development of [Linux Containers (LXC)](https://linuxcontainers.org/) in the same year. LXC allowed users to create isolated environments called containers for running multiple applications by utilizing kernel features like the aforementioned `cgroups` and namespaces.

First introduced in 2013 The [Docker Engine](https://docs.docker.com/get-started/overview/#docker-engine) made it easier to create and run Linux Containers by utilizing LXC but quickly came up with [`libcontainer`](https://github.com/opencontainers/runc/blob/main/libcontainer/README.md) their own execution enginne.

As popular as it may be, getting started with Docker can seem a bit intimidating at first. So in this free full-length book, you'll learn everything from basic to intermediate ideas of containerization using Docker.

## Prerequisites

* Familiarity with the Linux Terminal

## Project Code

Code for the example projects can be found in the following repository:

[https://github.com/fhsinchy/docker-handbook-projects/](https://github.com/fhsinchy/docker-handbook-projects/)

There are two directories in the `master` branch. The `starter` directory contains the project codes without any containerization applied and the `containerized` directory contains the project cods alongside necessary instructions for containerization.

## Contributions

This book is completely open-source and quality contributions are more than welcomed. You can find the full content in the following repository:

[https://github.com/fhsinchy/the-docker-handbook](https://github.com/fhsinchy/the-docker-handbook)

I usually do my changes and updates on the GitHub version of the article first and then publish them on freeCodeCamp. You can find the always updated and often incomplete version of the article in the following link:

[https://docker-handbook.farhan.dev/](https://docker-handbook.farhan.dev/)

If you're looking for the complete and stable version of the article then freeCodeCamp will be the best place to go:

[https://www.freecodecamp.org/news/the-docker-handbook/](https://www.freecodecamp.org/news/the-docker-handbook/)

Which ever version of the article you end up reading though, don't forget to let me know your opinion.

## Awesome Contributors

I am listing the names of the amazing people who have contributed to this small project in alphabetical order.

* [Andrea Trogolo](https://github.com/ATrogolo) - fixed several grammatical mistakes and inconsistencies in code examples.
* [Arsen Melikyan](https://github.com/bugron) - fixed typos and inconsistencies in multiple images and sections.
* [David A. Carley](https://github.com/dacarley) - fixed spelling mistakes in some of the `svg` files.
* [Emilano Vazquez](https://github.com/gamba47) - fixed inconsistencies in code explanations.
* [Steven Cook](https://github.com/Dez-BlueRose) - fixed mistakes and added new sub-sections with better explanations for some of the topics.

Thanks a lot to all of you, I appreciate the effort you guys have put in improving this project. Hoping to collaborate in the future also.

