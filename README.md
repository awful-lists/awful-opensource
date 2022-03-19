# Awful Open source projects

This is the list of open-source projects which is better to avoid.

## How to determine if an open-source project is awful?

- [ ] It violates its license.
- [ ] It has malicious code.
- [ ] Its code smells awful.
- [ ] It has changed the license once.
- [ ] It has additional requirements apart from the included license.
- [ ] It has changed git history for some reasons.
- [ ] It has some features removed deliberately.

## Content

### Additional requirements

#### [terraform-aws-eks](https://github.com/terraform-aws-modules/terraform-aws-eks)

Reason: one of the maintainers has added additional terms of use for users from Russia and Belarus.

Related commits:

- [commit 1](https://github.com/terraform-aws-modules/terraform-aws-eks/commit/fad350d5bf36a7e39aa3840926b4c9968e9f594c)
  - added additional terms of use for Russian and Belarusian developers.
- [commit 2](https://github.com/terraform-aws-modules/terraform-aws-eks/commit/f5511e4df1f06954229f48df1cf87f9ebc8da26a)
  - changed `terms of use` to `information`.

<br/>

---

### Malicious code

#### [node-ipc](https://github.com/RIAEvangelist/node-ipc)

Reason: the author has pushed malware, which wipes library user's disk if they happen to have Russian or Belorussian IP
address.

Related commits:

- [commit 1](https://github.com/RIAEvangelist/node-ipc/blob/847047cf7f81ab08352038b2204f0e7633449580/dao/ssl-geospec.js)
  - added obfuscated malware coded.
- [commit 1 mirror](https://github.com/awful-lists-archives/node-ipc/blob/847047cf7f81ab08352038b2204f0e7633449580/dao/ssl-geospec.js)

<br/>

#### [es5-ext](https://github.com/medikoo/es5-ext)

Reason: the author of the project has added a banner that will show up based on the user's timezone, mostly targeting
Russian territory.

Related commits:

- [commit](https://github.com/medikoo/es5-ext/commit/28de285ed433b45113f01e4ce7c74e9a356b2af2) - added the malicious
  code.

<br/>

---

### Deliberately removed features

#### [RedisDesktopManager](https://github.com/uglide/RedisDesktopManager)

Reason: removed Russian translation with a message `7th day Russia kills innocent people in Ukraine`. Interesting fact,
Russian has over 258 million total speakers worldwide and the population of Russia is about 150 million people (year 2022).

Related commits:
- [commit](https://github.com/uglide/RedisDesktopManager/commit/8b2b357d9d233100f84a69f81ed22b8caa04fa22) - removed Russian translation.  


