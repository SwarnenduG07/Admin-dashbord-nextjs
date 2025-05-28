# Changelog

## 0.1.0-alpha.2 (2025-05-28)

Full Changelog: [v0.1.0-alpha.1...v0.1.0-alpha.2](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/compare/v0.1.0-alpha.1...v0.1.0-alpha.2)

### Bug Fixes

* **api:** improve type resolution when importing as a package ([#21](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/issues/21)) ([5b71dd9](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/5b71dd9890b76093d91ebf54dec53f56c929ea18))
* **mcp:** remove unused tools.ts ([#23](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/issues/23)) ([3c70b28](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/3c70b28161e1c8fe920a671d7ba2647371a216b0))


### Chores

* **ci:** add timeout thresholds for CI jobs ([08842ef](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/08842efdf98b475470c0c1b5c608ca0bf965f0b5))
* **ci:** bump node version for release workflows ([66048d5](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/66048d5427322ecf05b6aeb221e4eb2a5e50bf83))
* **ci:** only use depot for staging repos ([19dea69](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/19dea693d1b9828c6e39b482a4c0c59d9170bf5f))
* **client:** minor internal fixes ([bd58590](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/bd585903822fee96d0681621871c77ad5078bcb8))
* **docs:** grammar improvements ([3cec3c1](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/3cec3c1a184d5be42533f5d869cd2de7b989a727))
* improve publish-npm script --latest tag logic ([62a41c3](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/62a41c3500cb80fde6cd127625c07a319a988495))
* **internal:** codegen related update ([dab4039](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/dab40398c549da56ace401197ebb788f6380eb19))
* **internal:** reduce CI branch coverage ([a501080](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/a501080d87352993593c967adfb2e3f999f71c77))
* **internal:** upload builds and expand CI branch coverage ([ce0266c](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/ce0266c78a46c93a636344ae9ac095ba10040c15))
* **tests:** improve enum examples ([#25](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/issues/25)) ([f2e3e4c](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/f2e3e4c1740b46e02ad346e7031f411595577da7))


### Documentation

* add examples to tsdocs ([25ae67f](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/25ae67f0113e961d24f6517495385da18abe9d4b))
* **readme:** fix typo ([ec6d3fd](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/ec6d3fd7d1a7c7865e91ac73c8f051ee179af43e))
* swap examples used in readme ([#24](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/issues/24)) ([08333da](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/08333dab9a368d7ef24a8cb4a56b09253f9ef76b))

## 0.1.0-alpha.1 (2025-04-03)

Full Changelog: [v0.0.1-alpha.1...v0.1.0-alpha.1](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/compare/v0.0.1-alpha.1...v0.1.0-alpha.1)

### Features

* add SKIP_BREW env var to ./scripts/bootstrap ([#9](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/issues/9)) ([5d7f809](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/5d7f80944a1a8246124f44019dead7789869c817))
* **client:** accept RFC6838 JSON content types ([#11](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/issues/11)) ([12ec846](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/12ec846c124461fd4ae261b34b563b10c1c8f8c8))


### Bug Fixes

* avoid type error in certain environments ([#16](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/issues/16)) ([8b21263](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/8b21263bd0fa5a58d36799f7e057fbe17f15bb46))
* **client:** send `X-Stainless-Timeout` in seconds ([#18](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/issues/18)) ([a43a349](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/a43a349c9bb0c3a6e3ecc74529fccaa791f6e747))
* **exports:** ensure resource imports don't require /index ([#13](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/issues/13)) ([4ba4e0a](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/4ba4e0a95f7012bf012b76aa2a0efbe5c46c4a1b))
* **internal:** work around https://github.com/vercel/next.js/issues/76881 ([#17](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/issues/17)) ([6d5e2c4](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/6d5e2c48d9a910c5aa8cb7cc240e343528865d20))


### Chores

* **exports:** cleaner resource index imports ([#14](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/issues/14)) ([b6574d7](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/b6574d7c3dd7defca81c49313e42e8bd13adab78))
* **exports:** stop using path fallbacks ([#15](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/issues/15)) ([d35eb4d](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/d35eb4dbd8f8e72875143847371f492673323181))
* **internal:** add aliases for Record and Array ([#19](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/issues/19)) ([8cd0df6](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/8cd0df6c11fd0585f87106a25a1d7124f245617c))
* **internal:** remove extra empty newlines ([#12](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/issues/12)) ([81cf1b5](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/81cf1b5de74cdebd6111f615de8d6d0c6d247ca1))

## 0.0.1-alpha.1 (2025-02-28)

Full Changelog: [v0.0.1-alpha.0...v0.0.1-alpha.1](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/compare/v0.0.1-alpha.0...v0.0.1-alpha.1)

### Bug Fixes

* **client:** fix export map for index exports ([#3](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/issues/3)) ([1e60ee6](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/1e60ee615076cdff6792fd95faddb8ed97435e13))
* **client:** mark some request bodies as optional ([#5](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/issues/5)) ([f49f00e](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/f49f00ef17b10b14fd9f2bc9305f49ad2edc294f))


### Chores

* go live ([#1](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/issues/1)) ([4162467](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/41624678e0988779e46a5aff3061b94973b3f360))
* **internal:** codegen related update ([#4](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/issues/4)) ([56ee686](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/56ee686d4b2211c7324018d587c4335da16e0b0b))
* **internal:** fix devcontainers setup ([#6](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/issues/6)) ([d9b97c8](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/d9b97c8b6348a3005cebe0588ba93293d94f68b5))
* sync repo ([3f6e233](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/3f6e2339f84e0d63ffe61bc10e537cfe3b9914ae))


### Documentation

* update URLs from stainlessapi.com to stainless.com ([#7](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/issues/7)) ([7307658](https://github.com/SwarnenduG07/Admin-dashbord-nextjs/commit/730765808bb880262174bb037d667f99c2bfbcbe))
