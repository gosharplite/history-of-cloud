# History of cloud

2012/3 - [Golang](https://golang.org/) 1.0<br>
2013/3 - [Docker](https://www.docker.com/) first version<br>
2013/7 - [CoreOS](https://coreos.com/) start<br>
2014/4 - Redhat [Atomic](http://www.projectatomic.io/) start<br>
2014/6 - Docker 1.0<br>
2014/7 - [Kubernetes](http://kubernetes.io/) start<br>
2014/7 - CoreOS [367.1.0](https://coreos.com/blog/stable-release/) first stable version<br>
2014/12 - [rkt, appc](https://coreos.com/blog/rocket/) start<br>
1014/12 - Docker machine/swarm/compose start<br>
2014/12 - Ubuntu [Snappy](http://www.markshuttleworth.com/archives/1434)<br>
2014/12 - [Rancher](http://rancher.com/) OS<br>
2015/5 - [Omega](http://eurosys2013.tudos.org/wp-content/uploads/2013/paper/Schwarzkopf.pdf) [becomes part of](http://www.theplatform.net/2015/05/05/google-omega-to-become-part-of-borg-collective/) [borg](https://static.googleusercontent.com/media/research.google.com/zh-TW//pubs/archive/43438.pdf)<br>
2015/5 - [Container war](http://www.theregister.co.uk/2015/05/05/coreos_fest_roundtable/)<br>
2015/6 - [OCI](https://www.opencontainers.org/) start<br>
2015/7 - Kubernetes 1.0<br>
2015/7 - [CNCF](https://cncf.io/) start<br>
2015/8 - Golang [1.5](https://blog.golang.org/go1.5)<br>
2015/8 - [GKE](https://cloud.google.com/container-engine/) is [GA](http://googlecloudplatform.blogspot.tw/2015/08/Google-Container-Engine-is-Generally-Available.html)<br>
<hr>
[Graph by Sam Ramji](https://twitter.com/solomonstre/status/634159354103488512)<br>
[Mesos](http://www.wired.com/2013/03/google-borg-twitter-mesos/)<br>
[RedHat's stand on container](http://www.redhat.com/en/about/blog/taking-stand-against-container-fragmentationwith-standards) and [rkt, appc, Docker](http://rhelblog.redhat.com/2015/05/05/rkt-appc-and-docker-a-take-on-the-linux-container-upstream/).<br>
[Immutable Infrastructure Is The Future](http://michaeldehaan.net/post/118717252307/immutable-infrastructure-is-the-future) (Michael Dehaan, creator of Ansible and Cobbler)<br>
[It’s The Future](http://blog.circleci.com/its-the-future/)
<hr>
[K8s on wired](http://www.wired.com/2015/06/google-kubernetes-says-future-cloud-computing/), [photo](https://twitter.com/jbeda/status/608703174992535552/photo/1)<br>
[A Technical Overview of Kubernetes](https://www.youtube.com/watch?v=WwBdNXt6wO4) (Brendan Burns)<br>
[Patterns for Composite Containers](http://blog.kubernetes.io/2015/06/the-distributed-system-toolkit-patterns.html) , [video](https://www.youtube.com/watch?v=Ph3t8jIt894) (Brendan Burns)<br>
[Flannel explained](https://www.youtube.com/watch?v=_HYeSaGtEYw)
<hr>
[Leaping the chasm from proprietary to open](http://www.slideshare.net/bcantrill/leaping-the-chasm-from-proprietary-to-open-a-survivors-guide) (Bryan Cantrill)<br>
[The foundation of cloud-native computing](http://dtrace.org/blogs/bmc/2015/07/21/the-foundation-of-cloud-native-computing/) (CNCF)<br>
<hr>
[Why Docker is Not Yet Succeeding Widely in Production](http://sirupsen.com/production-docker/), [twitter](https://twitter.com/kelseyhightower/status/626057416463912960).<br>
[Docker security fight](https://github.com/docker/docker/issues/9719). Jonathan Rudenberg<br>
[Docker Gets Serious About Security](http://www.eweek.com/security/docker-gets-serious-about-security.html?utm_medium=email&utm_campaign=EWK_NL_LPU_20150513_STR4L1&dni=245713323&rni=24844166).<br>
[Introducing docker content trust](http://blog.docker.com/2015/08/content-trust-docker-1-8/)<br>
[Twitter - Kelsey Hightower](https://twitter.com/kelseyhightower/status/631697830487261185)<br>
[Twitter - Brandon Philips](https://twitter.com/BrandonPhilips/status/631705281471213573)<br>
[Docker Image Insecurity - Jonathan Rudenberg](https://titanous.com/posts/docker-insecurity)<br>
<hr>
Shot fired at CoreOS<br>
https://www.youtube.com/watch?v=a9lE9Urr6AQ&feature=youtu.be&t=9m40s<br>
https://www.youtube.com/watch?v=zWGFqMuEHdw<br>
https://www.youtube.com/watch?v=NnhmHpywdW0&feature=youtu.be&t=1h1m15s<br>
https://github.com/coreos/coreos-overlay/pull/777<br>
https://github.com/coreos/coreos-overlay/pull/1311<br>
<hr>
[systemd at the Core of the OS](https://www.youtube.com/watch?v=VIPonFvPlAs) (Lennart Poettering)<br>

1. rkt uses systemd-nspawn for the actual containerization
2. docker [wiki](http://en.wikipedia.org/wiki/Docker_%28software%29)
3. systemd-nspawn, systemd-machined, systemd-networkd, systemd-resolved, systemd-importd (low level container implementation)

[Controversial Lennart Poettering Finds His Place In Linux Community](http://www.informationweek.com/software/operating-systems/controversial-lennart-poettering-finds-his-place-in-linux-community/a/d-id/1320316)<br>
[Unix philosophy](http://en.wikipedia.org/wiki/Unix_philosophy)<br>
[The Biggest Myths](http://0pointer.de/blog/projects/the-biggest-myths)<br>
[Why you cannot trust Lennart Poettering / systemd](https://www.linkedin.com/pulse/20140924071300-170035-why-you-cannot-trust-lennart-poettering-systemd)<br>
<hr>
[Please stop calling databases CP or AP](https://martin.kleppmann.com/2015/05/11/please-stop-calling-databases-cp-or-ap.html) (Martin Kleppmann)<br>
[Notes on Distributed Systems for Young Bloods](http://www.somethingsimilar.com/2013/01/14/notes-on-distributed-systems-for-young-bloods/)<br>
[The CAP FAQ](http://henryr.github.io/cap-faq/)<br>
[You Can’t Sacrifice Partition Tolerance](http://codahale.com/you-cant-sacrifice-partition-tolerance/)<br>
<br>
[CAP theorem creator on the future](https://medium.com/s-c-a-l-e/google-systems-guru-explains-why-containers-are-the-future-of-computing-87922af2cf95) (Eric Brewer)<br>
<br>
[Head to head](https://twitter.com/martinkl/status/613038862919671808?replies_view=true&cursor=AKDWixr0gQg)<br>
<hr>
[Kelsey vs Solomon](https://twitter.com/solomonstre/status/621938165784297472)<br>
<hr>
[Container Native Package System](http://www.eightypercent.net/post/new-container-image-format.html), [discussion](https://news.ycombinator.com/item?id=9814131) (Joe Beda)<br>
<hr>
Get your ops story straight. Have crisp answers for<br>

1. Networking
2. Logging
3. Monitoring
4. Security
5. Upgrades

<hr>
