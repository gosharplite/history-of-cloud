# History of cloud

2012/3 - [Golang](https://golang.org/) 1.0<br>
2013/3 - Docker first version<br>
2013/7 - CoreOS start<br>
2014/4 - Redhat Atomic start<br>
2014/6 - [Docker](https://www.docker.com/) 1.0<br>
2014/7 - [Kubernetes](http://kubernetes.io/) start<br>
2014/7 - [CoreOS](https://coreos.com/) 367.1 first stable version<br>
2014/12 - [rkt, appc start](https://coreos.com/blog/rocket/)<br>
1014/12 - Docker machine/swarm/compose start<br>
2014/12 - [Ubuntu Snappy](http://www.markshuttleworth.com/archives/1434)<br>
2014/12 - Rancher OS<br>
2015/5 - [Omega](http://eurosys2013.tudos.org/wp-content/uploads/2013/paper/Schwarzkopf.pdf) [becomes part of](http://www.theplatform.net/2015/05/05/google-omega-to-become-part-of-borg-collective/) [borg](https://static.googleusercontent.com/media/research.google.com/zh-TW//pubs/archive/43438.pdf)<br>
2015/6 - [OCI](https://www.opencontainers.org/) start. [End of container war](http://www.theregister.co.uk/2015/05/05/coreos_fest_roundtable/)?<br>
2015/7 - Kubernetes 1.0<br>
2015/7 - [CNCF](https://cncf.io/) start<br>
2015/8 - Golang 1.5
<hr>
[Graph by Sam Ramji](https://twitter.com/solomonstre/status/634159354103488512)<br>
[Mesos](http://www.wired.com/2013/03/google-borg-twitter-mesos/)<br>
[RedHat's stand on container](http://www.redhat.com/en/about/blog/taking-stand-against-container-fragmentationwith-standards) and [rkt, appc, Docker](http://rhelblog.redhat.com/2015/05/05/rkt-appc-and-docker-a-take-on-the-linux-container-upstream/).<br>
[Immutable Infrastructure Is The Future](http://michaeldehaan.net/post/118717252307/immutable-infrastructure-is-the-future) (by creator of Ansible and Cobbler)<br>
[It’s The Future](http://blog.circleci.com/its-the-future/)
<hr>
[K8s on wired](http://www.wired.com/2015/06/google-kubernetes-says-future-cloud-computing/), [photo](https://twitter.com/jbeda/status/608703174992535552/photo/1).<br>
[K8s by Brendan Burns](https://www.youtube.com/watch?v=WwBdNXt6wO4)<br>
[Patterns for Composite Containers](http://blog.kubernetes.io/2015/06/the-distributed-system-toolkit-patterns.html) , [video](https://www.youtube.com/watch?v=Ph3t8jIt894) (Brendan Burns)<br>
[Flannel explained](https://www.youtube.com/watch?v=_HYeSaGtEYw)
<hr>
Bryan Cantrill (Cloud Native Computing Foundation)<br>
http://www.slideshare.net/bcantrill/leaping-the-chasm-from-proprietary-to-open-a-survivors-guide<br>
http://dtrace.org/blogs/bmc/2015/07/21/the-foundation-of-cloud-native-computing/
<hr>
[Why Docker is Not Yet Succeeding Widely in Production](http://sirupsen.com/production-docker/), [twitter](https://twitter.com/kelseyhightower/status/626057416463912960).<br>
[Docker security fight](https://github.com/docker/docker/issues/9719). Jonathan Rudenberg #titanous<br>
[Docker Gets Serious About Security](http://www.eweek.com/security/docker-gets-serious-about-security.html?utm_medium=email&utm_campaign=EWK_NL_LPU_20150513_STR4L1&dni=245713323&rni=24844166).<br>
http://blog.docker.com/2015/08/content-trust-docker-1-8/<br>
https://twitter.com/kelseyhightower/status/631697830487261185<br>
https://twitter.com/BrandonPhilips/status/631705281471213573<br>
https://titanous.com/posts/docker-insecurity<br>
<hr>
Shot fired at CoreOS.<br>
https://www.youtube.com/watch?v=a9lE9Urr6AQ&feature=youtu.be&t=9m40s<br>
https://www.youtube.com/watch?v=zWGFqMuEHdw<br>
https://www.youtube.com/watch?v=NnhmHpywdW0&feature=youtu.be&t=1h1m15s<br>
https://github.com/coreos/coreos-overlay/pull/777<br>
https://github.com/coreos/coreos-overlay/pull/1311<br>
<hr>
systemd by Lennart Poettering.<br>
https://www.youtube.com/watch?v=VIPonFvPlAs<br>
1) rkt uses systemd-nspawn for the actual containerization.<br>
2) docker uses http://en.wikipedia.org/wiki/Docker_%28software%29<br>
3) systemd-nspawn, systemd-machined, systemd-networkd, systemd-resolved, systemd-importd (low level container implementation)<br>
<br>
http://www.informationweek.com/software/operating-systems/controversial-lennart-poettering-finds-his-place-in-linux-community/a/d-id/1320316<br>
http://en.wikipedia.org/wiki/Unix_philosophy<br>
http://0pointer.de/blog/projects/the-biggest-myths<br>
https://www.linkedin.com/pulse/20140924071300-170035-why-you-cannot-trust-lennart-poettering-systemd<br>
<hr>
CAP theorem<br>
<br>
Please stop calling databases CP or AP (Brandon Philips, majority quorum, Martin Kleppmann).<br>
https://martin.kleppmann.com/2015/05/11/please-stop-calling-databases-cp-or-ap.html<br>
http://www.somethingsimilar.com/2013/01/14/notes-on-distributed-systems-for-young-bloods/<br>
http://henryr.github.io/cap-faq/<br>
http://codahale.com/you-cant-sacrifice-partition-tolerance/<br>
<br>
[CAP theorem creator on the future](https://medium.com/s-c-a-l-e/google-systems-guru-explains-why-containers-are-the-future-of-computing-87922af2cf95)<br>
<br>
[Head to head](https://twitter.com/martinkl/status/613038862919671808?replies_view=true&cursor=AKDWixr0gQg)<br>
<hr>
[Kelsey vs Solomon](https://twitter.com/solomonstre/status/621938165784297472)<br>
<hr>
Container Native Package System (Joe Beda)<br>
http://www.eightypercent.net/post/new-container-image-format.html<br>
https://news.ycombinator.com/item?id=9814131<br>
<hr>
Get your ops story straight<br>
Have crisp answers for<br>
1)Networking<br>
2)Logging<br>
3)Monitoring<br>
4)Security<br>
5)Upgrades<br>
<hr>
