## Open Source

### Preamble

Almost our entire stack is based upon open source tools and libraries and all platforms
we build upon have a strong relationship with open source and free software.

We believe that no matter how much you give to the community, you will always receive
more. This is why we try to contribute as much as possible.

### Policy

#### When should you publish your code?

You should always open source the tools you are developing at voiio.

However, there are some legal constraints and rather things or information you should
NOT publish:

1. Customer, user or any other private data.
1. Information that could compromise the security of our systems.
1. Credentials or account data.
1. Any work containing domain-specific knowledge
   or otherwise could be considered a company asset
   or intellectual property.

You should act in voiio’s best interest. If you are uncertain or feel insecure,
simply approach your supervisor.

#### How to publish code?

All public code needs to be licensed to become open source. We license all our public
work under the [3-Clause BSD License][bsd-3-clause]. You can simply select
this license when creating a new repository on GitHub.

Besides that, all public packages – as well as the private once – should have a complete
auto deployment pipeline setup.

We follow [semantic versioning 2.0 (semver)][semver] and usually every contribution and
commit gets deployed, to make new features accessible to the community as soon as
possible.

[bsd-3-clause]: https://opensource.org/license/bsd-3-clause
[semver]: https://semver.org/spec/v2.0.0.html
