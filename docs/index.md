K8s snap documentation
======================

The K8s snap is a performant, lightweight, secure and opinionated distribution 
of Kubernetes which includes all the components needed to create and manage
a scaleable cluster suitable for all use cases.



**Snaps** are Linux app packages for **desktop**, **cloud** and **IoT** that are self-contained, simple to install,
secure, cross-platform, and dependency-free.

They **update automatically** and typically run within a **confined** and **transaction-based** environment. **Security and robustness** are their key features, alongside being **easy to install**, **easy to maintain** and **easy to upgrade**.

Snaps help **desktop** users effortlessly install and run apps like [Spotify](https://snapcraft.io/spotify) or [Slack](https://snapcraft.io/slack). They help **sysadmins** run servers like [NextCloud](<https://snapcraft.io/nextcloud>), **developers** to package and distribute their work to the global [Snap Store](https://snapcraft.io/store), and they help everyone build and deploy **IoT** devices running [Ubuntu Core](https://ubuntu.com/core).

From Linux and maker space tinkerers, to the robotics, automotive and signage industries; from your desktop to a deployment of thousands, snap can handle it.


---

## In this documentation

`````{only} diataxis

````{grid} 1 1 2 2

```{grid-item} [Tutorials](tutorial/index)

**Start here**: a hands-on introduction to LXD for new users
```

```{grid-item} [How-to guides](howto/index)

**Step-by-step guides** covering key operations and common tasks
```

````

````{grid} 1 1 2 2
:reverse:

```{grid-item} [Reference](reference/index)

**Technical information** - specifications, APIs, architecture
```

```{grid-item} [Explanation](explanation/index)

**Discussion and clarification** of key topics, for example, {ref}`Security <security>`
```

````

`````

```{filtered-toctree}
:titlesonly:
:maxdepth: 1

:topical:self
:topical:getting_started
:topical:Server and client <operation>
:topical:security
:topical:instances
:topical:images
:topical:storage
:topical:networks
:topical:projects
:topical:clustering
:topical:production-setup
:topical:migration
:topical:restapi_landing
:topical:Internals & debugging <internals>
:topical:external_resources
```

---

## Project and community

LXD is free software and released under [AGPL-3.0-only](https://www.gnu.org/licenses/agpl-3.0.en.html) (it may contain some contributions that are licensed under the Apache-2.0 license, see [License and copyright](contributing)).
It’s an open source project that warmly welcomes community projects, contributions, suggestions, fixes and constructive feedback.

The LXD project is sponsored by [Canonical Ltd](https://www.canonical.com).

- [Code of Conduct](https://github.com/canonical/lxd/blob/main/CODE_OF_CONDUCT.md)
- [Contribute to the project](contributing.md)
- [Release announcements](https://discourse.ubuntu.com/c/lxd/news/)
- [Release tarballs](https://github.com/canonical/lxd/releases/)
- [Get support](support.md)
- [Watch tutorials and announcements on YouTube](https://www.youtube.com/c/LXDvideos)
- [Discuss on IRC](https://web.libera.chat/#lxd) (see [Getting started with IRC](https://discourse.ubuntu.com/t/getting-started-with-irc/37907) if needed)
- [Ask and answer questions on the forum](https://discourse.ubuntu.com/c/lxd/)

```{filtered-toctree}
:hidden:
:titlesonly:

:diataxis:self
:diataxis:tutorial/index
:diataxis:howto/index
:diataxis:explanation/index
:diataxis:reference/index
```