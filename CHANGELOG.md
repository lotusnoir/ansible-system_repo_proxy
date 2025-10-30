# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [4.0.0](https://github.com/lotusnoir/ansible-system_repo_proxy/compare/3.0.0...4.0.0) - 2025-10-29

### Commits

- add trixie (debian13) support [`797b2d2`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/797b2d23e2caf9a7f90687223f9d6c133400e452)
- update core, molecule + gitlab-ci [`1610ac1`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/1610ac16973b759c0167de63aab27ddfa1559449)
- fix lint [`361d4e5`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/361d4e557cc54b91ff305f891fc340611fc645a3)
- fix molecule paralelism and little updates [`ede0413`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/ede0413064686a8ff24b1aa3a6b1ab45a57685e2)
- add support for ubuntu24 [`f65a152`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/f65a152fb14ce29a4b800ded14736176adc29a32)
- change skip by configure [`c36856c`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/c36856c0e01383a431631ecf933f0fb329d2d174)
- update variable name and add task for redhat [`a4dce21`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/a4dce2126ceca67a3fc81ec828bcdc0c54be8628)
- add version on molecule play image to maintain support on old release [`bb1ef61`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/bb1ef6102e969070c008f6284fc41a009c2b5e6b)
- update molecule [`8a7f7de`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/8a7f7de1e9de18b85d38f4f38d929af4c4c2682e)
- add redhat 9 to default supported distrib [`00431c0`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/00431c0030d5543a8a1ab7dc01e6cbdf5f7c979e)

## [3.0.0](https://github.com/lotusnoir/ansible-system_repo_proxy/compare/2.1.0...3.0.0) - 2023-09-25

### Commits

- update vars [`cf61e74`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/cf61e74c23ef37322540af8b799c1045585c3657)
- update readme + precommit + include vars [`839cf6d`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/839cf6d663ccba243945a946190e397dd073e30d)
- change import tasks to include in order to support facts on name [`b63e470`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/b63e4705bfff8e4fe4ba8b9767f24c4c6cdf9a1f)
- remove check tasks that are useless and change proxy file method from copy to template [`5a10453`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/5a10453a9669fb4f596d50f691f675d08b312486)
- skip role with bool than inventory name [`aecf4ef`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/aecf4ef2e3386907d41721bfbf4df03fd30e2da9)

## [2.1.0](https://github.com/lotusnoir/ansible-system_repo_proxy/compare/2.0.0...2.1.0) - 2023-06-14

### Commits

- add debian12 support [`3552d75`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/3552d75447196bf97b903a14317dee0403970f1d)

## [1.0.0](https://github.com/lotusnoir/ansible-system_repo_proxy/compare/0.4.0...1.0.0) - 2023-03-22

### Commits

- add precommit for lint [`2c1ee27`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/2c1ee2705610df4af1ddee6ab2428974642e71e2)
- fix checks [`fec8970`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/fec8970d7b1992c256b1005546683e9b3d575e42)
- add new molecule all scenario [`1382045`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/138204593e076545a0e1f55c4c9fea53fb32c5d8)
- update readme [`e840a9d`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/e840a9d114987daf468498e78150d905b744e237)
- update molecule to test something since no changes by default [`18ee642`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/18ee6425debe8cb65db21a851980184d4b4c02f2)
- split distro for molecule tests on ci [`e14d2c5`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/e14d2c58502ec55e7dcb6b127d07f65647cc789f)
- update checks and Readme [`a4fddb0`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/a4fddb0171b28ce5c66a7a208a9759f622f32f5d)
- add molecule fix for ora9 [`dc45183`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/dc45183803fb6d8d416befca8a6a1a81ac042c6f)
- fix task [`d52e13c`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/d52e13c2bac4832c7fa1d96e98debc5fdedfcf80)
- fix checks [`39d9529`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/39d9529f803b5dec05247646fddcfaa346a69f6e)

## [0.4.0](https://github.com/lotusnoir/ansible-system_repo_proxy/compare/0.3.0...0.4.0) - 2022-07-01

### Commits

- minor: add oracleLinux7 support [`2399a5d`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/2399a5de03fc7381699dff5d67a0e0c151b3b533)

## [0.3.0](https://github.com/lotusnoir/ansible-system_repo_proxy/compare/0.2.0...0.3.0) - 2022-07-01

### Commits

- fix: rename yum proxy var [`ae9606f`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/ae9606f064868ca57f72fbf26d4b201c4ffc33d4)
- minor: add oracleLinux support + little fixes [`e003ccc`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/e003ccc6ced7b1eda7006cafe7c35e31f488588f)

## [0.2.0](https://github.com/lotusnoir/ansible-system_repo_proxy/compare/0.1.1...0.2.0) - 2022-06-02

### Commits

- minor: add ubuntu 22 molecule test + fix lint [`570a39e`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/570a39ece590add854b0dd18453d5e4d6008f690)
- fix: Changes on README + molecule container names [`ec00464`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/ec00464aa7c673489edd56fbbd6ec800aecb76cd)

## 0.1.0 - 2021-11-16

### Commits

- fix: add role name on molecule container names to avoid concurrent conflict on runners [`69f6ee2`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/69f6ee277e883ec3995836746e67449c9b50038c)
- minor: add changelog + automatic files checks [`9d74d3b`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/9d74d3b9e7358e624add78390b506343fec86369)
- initial commit [`4e68f22`](https://github.com/lotusnoir/ansible-system_repo_proxy/commit/4e68f228553e212ecf6b88bc0c6de2a468ddad41)
