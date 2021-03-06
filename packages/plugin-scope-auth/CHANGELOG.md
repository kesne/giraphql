# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 2.0.0-alpha.0 - 2021-02-10

#### 💥 Breaking

- you can no-longer define args on 'exposed' fields ([240162b](https://github.com/hayes/giraphql/commit/240162b))

#### 🚀 Updates

- add option to disable scope auth during build ([c4f6bee](https://github.com/hayes/giraphql/commit/c4f6bee))
- add support for  scopes ([0b10ffd](https://github.com/hayes/giraphql/commit/0b10ffd))
- add support for authScope checks on interfaces ([fa6fe1e](https://github.com/hayes/giraphql/commit/fa6fe1e))
- add support for skipping type/interface scopes on specific fields ([34c95e3](https://github.com/hayes/giraphql/commit/34c95e3))

#### 🐞 Fixes

- bump auth plugin to 2.0 ([2bbb142](https://github.com/hayes/giraphql/commit/2bbb142))

#### 📘 Docs

- add initial docs for scope auth plugin ([15b086d](https://github.com/hayes/giraphql/commit/15b086d))

#### 🛠 Internals

- add some basic scope-auth tests ([7ceb24a](https://github.com/hayes/giraphql/commit/7ceb24a))
- add some caching tests ([0a08760](https://github.com/hayes/giraphql/commit/0a08760))
- add tests for authScope functions on fields ([324eb2f](https://github.com/hayes/giraphql/commit/324eb2f))
- add tests for authScope functions on types ([aed363a](https://github.com/hayes/giraphql/commit/aed363a))
- add tests for type authScopes ([951a6cd](https://github.com/hayes/giraphql/commit/951a6cd))

**Note:** Version bump only for package @giraphql/plugin-scope-auth
