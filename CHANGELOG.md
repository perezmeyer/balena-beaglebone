Change log
-----------

# v2.113.25+rev5
## (2023-04-29)


<details>
<summary> Update contracts to 6c6ed28d459bc48102a69cdf0850d2eb4c778ce7 [Renovate Bot] </summary>

> ## contracts-2.0.58
> ### (2023-04-27)
> 
> * jetson-agx-orin-devkit: Mention the RAM configuration in the device name [Alexandru Costache]
> 

</details>

# v2.113.25+rev4
## (2023-04-26)


<details>
<summary> Update contracts to 777cd35ffb8bebb2a9d8a2ec6b88a45b2c937193 [Renovate Bot] </summary>

> ## contracts-2.0.57
> ### (2023-04-07)
> 
> * debian/ubuntu jetson-orin-nx-xavier-nx-devkit: Add distro configs [Alexandru Costache]
> * Orin NX: Update flashing steps [Alexandru Costache]
> 
> ## contracts-2.0.56
> ### (2023-04-04)
> 
> * jetson-orin-nx-xavier-nx-devkit: Add contract for device type [Alexandru Costache]
> 

</details>

# v2.113.25+rev3
## (2023-04-25)

* Remove the redundant layers/meta-rust submodule [Florin Sarbu]

# v2.113.25+rev2
## (2023-04-24)


<details>
<summary> Update balena-yocto-scripts to 34c8434ffcaeeeb14853082bbf2b4ecc5e0ec769 [Renovate Bot] </summary>

> ## balena-yocto-scripts-1.19.27
> ### (2023-04-21)
> 
> * barys: fix removal of equals sign from argval [Joseph Kogut]
> 
> ## balena-yocto-scripts-1.19.26
> ### (2023-04-12)
> 
> * balena-lib: Do not return error if no balena user token is available [Alex Gonzalez]
> 

</details>

# v2.113.25+rev1
## (2023-03-31)


<details>
<summary> Update contracts to fa51fae4b720521334626045c25f754a046f6228 [Renovate Bot] </summary>

> ## contracts-2.0.55
> ### (2023-03-29)
> 
> * iot-gate-imx8plus: Update provisioning instructions [Alexandru]
> 

</details>

# v2.113.25
## (2023-03-23)


<details>
<summary> Update layers/meta-balena to 71c0d9581c2d5285b91c66675317edbcbb7b8ef9 [Renovate Bot] </summary>

> ## meta-balena-2.113.25
> ### (2023-03-23)
> 
> * kernel-balena: Include NFS V2, V3 and V4 client and server modules [Alexandru Costache]
> 
> ## meta-balena-2.113.24
> ### (2023-03-22)
> 
> * dunfell+: remove obsolete systemd patch [Joseph Kogut]
> * plymouth: replace duplicated patches w/ shared drop-ins [Joseph Kogut]
> * systemd: mask systemd-getty-generator instead of patching [Joseph Kogut]
> * systemd: replace duplicated patch w/ shared drop-ins [Joseph Kogut]
> 
> ## meta-balena-2.113.23
> ### (2023-03-22)
> 
> * pyro/sumo: initrdscripts: fix migrate module for older Yocto versions [Alex Gonzalez]
> * networkmanager: do not update to latest version in sumo [Alex Gonzalez]
> 
> ## meta-balena-2.113.22
> ### (2023-03-21)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to ad4f908 [Renovate Bot] </summary>
> 
>> ### leviathan-2.23.1
>> #### (2023-03-14)
>> 
>> * compose: qemu: add FLASHER_SECUREBOOT var [Joseph Kogut]
>> * swtpm: fix abort on exit [Joseph Kogut]
>> 
> 
> </details>
> 
> 
> ## meta-balena-2.113.21
> ### (2023-03-20)
> 
> * tests: os: secureboot: add integrity checks [Joseph Kogut]
> * tests: configure flasher secure boot opt-in [Joseph Kogut]
> 
> ## meta-balena-2.113.20
> ### (2023-03-20)
> 
> * tests: os: disable unwrapping [Joseph Kogut]
> * tests: hup: disable unwrapping [Joseph Kogut]
> * tests: cloud: disable unwrapping [Joseph Kogut]
> 
> ## meta-balena-2.113.19
> ### (2023-03-20)
> 
> * resin-u-boot.bbclass: Default to u-boot Kconfig support [Florin Sarbu]
> 

</details>

# v2.113.18
## (2023-03-17)


<details>
<summary> Update layers/meta-balena to 47781bdd7184f17c83523e961c7039d50e5e8775 [Renovate Bot] </summary>

> ## meta-balena-2.113.18
> ### (2023-03-16)
> 
> * Enable CI for external contributions from forks [Kyle Harding]
> 
> ## meta-balena-2.113.17
> ### (2023-03-16)
> 
> * Removed links to hub [Ryan H]
> 
> ## meta-balena-2.113.16
> ### (2023-03-16)
> 
> * balena-image-flasher: Default image type to balenaos-img [Florin Sarbu]
> 
> ## meta-balena-2.113.15
> ### (2023-03-16)
> 
> * resin-u-boot.bbclass: Replace static patch resin-specific-env-integration-kconfig.patch [Florin Sarbu]
> 
> ## meta-balena-2.113.14
> ### (2023-03-15)
> 
> 
> <details>
> <summary> Update balena-supervisor to v14.9.4 [Renovate Bot] </summary>
> 
>> ### balena-supervisor-14.9.4
>> #### (2023-03-13)
>> 
>> * Skip pin device step if release was deleted [Felipe Lalanne]
>> 
>> ### balena-supervisor-14.9.3
>> #### (2023-03-10)
>> 
>> * Use single-arch in dockerfile [Felipe Lalanne]
>> 
>> ### balena-supervisor-14.9.2
>> #### (2023-03-02)
>> 
>> * Replace BALENA-FIREWALL rule in INPUT chain instead of flushing [Christina Ying Wang]
>> 
> 
> </details>
> 
> 
> ## meta-balena-2.113.13
> ### (2023-03-15)
> 
> * update-balena-supervisor: use API request helper [Alex Gonzalez]
> * os-helpers: add test for os-helpers-api [Alex Gonzalez]
> * os-helpers: add os-helpers-api [Alex Gonzalez]
> 
> ## meta-balena-2.113.12
> ### (2023-03-14)
> 
> * Remove a bad check in Internet connection sharing test [Zahari Petkov]
> 
> ## meta-balena-2.113.11
> ### (2023-03-14)
> 
> * peak: Ship signed module when signing is enabled [Michal Toman]
> 
> ## meta-balena-2.113.10
> ### (2023-03-09)
> 
> * patch: Add balenaOS debugging docs [Vipul Gupta (@vipulgupta2048)]
> 
> ## meta-balena-2.113.9
> ### (2023-03-09)
> 
> * flasher: fix installation when in user mode w/ sb disabled [Joseph Kogut]
> 
> ## meta-balena-2.113.8
> ### (2023-03-08)
> 
> * fix ip for dummy interface to avoid ip conflicts [rcooke-warwick]
> * tests: os: NetworkManager iptables rules test for Internet sharing [Zahari Petkov]
> 
> ## meta-balena-2.113.7
> ### (2023-03-07)
> 
> * conf: distro: balena-os: use lower case for signing key names [Alex Gonzalez]
> 
> ## meta-balena-2.113.6
> ### (2023-03-07)
> 
> * recipes-core/images: Ensure redsocks sample files are deployed [Alexandru Costache]
> 
> ## meta-balena-2.113.5
> ### (2023-03-07)
> 
> * image-balena.bbclass: deploy grub-conf before building the boot partition [Michal Toman]
> 
> ## meta-balena-2.113.4
> ### (2023-03-03)
> 
> * balena-keys: do not ship certificates in DER format [Michal Toman]
> 
> ## meta-balena-2.113.3
> ### (2023-03-02)
> 
> * balena-units-conf: launch os-config on config changes [Alex Gonzalez]
> 
> ## meta-balena-2.113.2
> ### (2023-03-02)
> 
> * Refer to balenaEngine by its full name [Leandro Motta Barros]
> 
> ## meta-balena-2.113.1
> ### (2023-02-28)
> 
> * os-helpers-fs: formatting and fixing lint warning [Alex Gonzalez]
> * os-helpers-fs: fix check for media attached [Alex Gonzalez]
> * initrdscripts: migrate: use du instead of wc to calculate byte sizes [Alex Gonzalez]
> 
> ## meta-balena-2.113.0
> ### (2023-02-25)
> 
> * resin-init-flasher: use logging helper [Alex Gonzalez]
> * resin-init-flasher: replace shutdown for reboot in case of migration [Alex Gonzalez]
> * README: add installer section [Alex Gonzalez]
> * initrdscripts: Add migration module [Alex Gonzalez]
> * integration layers: use `android-tools` from Yocto Dunfell and before [Alex Gonzalez]
> * resin-init-flasher: comply with recovery mode [Alex Gonzalez]
> * initrdscritps: Move moving /run mountpoint from rootfs to migrate module [Alex Gonzalez]
> * initrdscripts: add recovery module [Alex Gonzalez]
> 
> ## meta-balena-2.112.15
> ### (2023-02-24)
> 
> * os-helpers-fs: add dependency on util-linux fdisk [Alex Gonzalez]
> 

</details>

# v2.112.14+rev3
## (2023-03-16)


<details>
<summary> Update contracts to 0ff4f419b4467349d7cb1d1202b580004067664c [Renovate Bot] </summary>

> ## contracts-2.0.54
> ### (2023-03-16)
> 
> * patch: Remove CircleCI in favor of Flowzone [Vipul Gupta (@vipulgupta2048)]
> 
> ## contracts-2.0.53
> ### (2023-03-16)
> 
> * patch: Fix fluid tags for revpi-core-3 [Vipul Gupta (@vipulgupta2048)]
> 
> ## contracts-2.0.52
> ### (2023-03-16)
> 
> * patch: Fix punctuation in partials [Vipul Gupta (@vipulgupta2048)]
> * patch: Fix spelling of eMMC [Vipul Gupta (@vipulgupta2048)]
> * patch: Fix spelling of while [Vipul Gupta (@vipulgupta2048)]
> 
> ## contracts-2.0.51
> ### (2023-02-24)
> 
> * node: do not set unsafe-perm with npm 9 and newer [Michal Toman]
> 

</details>

# v2.112.14+rev2
## (2023-03-16)

* Prevent duplicate CI workflow executions [Kyle Harding]

# v2.112.14+rev1
## (2023-03-15)


<details>
<summary> Update balena-yocto-scripts to 93f94ff88593966c1f417861b235e729d5192ba6 [Renovate Bot] </summary>

> ## balena-yocto-scripts-1.19.25
> ### (2023-03-01)
> 
> * Dockerfile: yocto-build-env: update balenaCLI to 14.5.15 [Alex Gonzalez]
> 
> ## balena-yocto-scripts-1.19.24
> ### (2023-02-28)
> 
> * balena-api: ignore quotes from API replies [Alex Gonzalez]
> 

</details>

* trigger deploy builds on multi-digit revisions too [Alex Gonzalez]

# v2.112.14
## (2023-02-22)


<details>
<summary> Update layers/meta-balena to 80ca81f9e4ec9d4b2e4d21bc1cf12bd59220be5a [Renovate Bot] </summary>

> ## meta-balena-2.112.14
> ### (2023-02-22)
> 
> * balena-config-vars: Remove dependency on fatrw [Alex Gonzalez]
> * balena-config-vars: split in two packages [Alex Gonzalez]
> * Add raid support based on machine features [Alex Gonzalez]
> * packagegroup-resin: add resin-device-progress dependency [Alex Gonzalez]
> * resin-init-flasher: remove device-register and device-progress dependencies [Alex Gonzalez]
> * resin-init-flasher: reduce dependencies [Alex Gonzalez]
> * os-helpers-fs: replace inform with info helper [Alex Gonzalez]
> * resin-init-flasher: Build time check on INTERNAL_DEVICE_KERNEL only for flasher device types [Alex Gonzalez]
> * resin-init-flasher: wait for the by-label links to be created [Alex Gonzalez]
> 

</details>

# v2.112.13+rev2
## (2023-02-22)


<details>
<summary> Update contracts to 7e5420c232e35b678f2138d9878f1d1fc921b1cf [Renovate Bot] </summary>

> ## contracts-2.0.50
> ### (2023-02-22)
> 
> * hw.device-type: Rename radxaFlash protocol to usbMassStorage [Alexandru Costache]
> 

</details>

# v2.112.13+rev1
## (2023-02-22)


<details>
<summary> Update contracts to 6acab7c69f61f6660fe5fa41ccfd617281442fb3 [Renovate Bot] </summary>

> ## contracts-2.0.49
> ### (2023-02-22)
> 
> * patch: Fix spelling for eMMC in Radxa-zero contract [Vipul Gupta (@vipulgupta2048)]
> 
> ## contracts-2.0.48
> ### (2023-02-22)
> 
> * hw.device-type: Various fixes [Alexandru Costache]
> 

</details>

# v2.112.13
## (2023-02-22)


<details>
<summary> Update layers/meta-balena to f6327ce662208faa11b250b47518a5f01679dd25 [Renovate Bot] </summary>

> ## meta-balena-2.112.13
> ### (2023-02-22)
> 
> * recipes-bsp/u-boot: Disable saveenv shell command [Alexandru Costache]
> * Update tests/leviathan digest to 771bac8 [Renovate Bot]
> 

</details>

# v2.112.12+rev2
## (2023-02-21)

* Update CI workflow to allow external contributions [Kyle Harding]

# v2.112.12+rev1
## (2023-02-21)


<details>
<summary> Update contracts to f32bce95ef31a6890812fbcf8f403a3ac2df95fd [Renovate Bot] </summary>

> ## contracts-2.0.47
> ### (2023-02-21)
> 
> * patch: Add docs to contracts for instructions partials [Vipul Gupta (@vipulgupta2048)]
> 

</details>

# v2.112.12
## (2023-02-21)


<details>
<summary> Update layers/meta-balena to 2e4f0c9530e0c8ea71b52a6e6a4f12fd01f1643b [Renovate Bot] </summary>

> ## meta-balena-2.112.12
> ### (2023-02-20)
> 
> * os-helpers-fs: get_internal_device() skip disks w/out media [Joseph Kogut]
> 

</details>

# v2.112.11
## (2023-02-20)


<details>
<summary> Update layers/meta-balena to d21da1fc034f4e0b09a457d0ed5eda47d0a18e13 [Renovate Bot] </summary>

> ## meta-balena-2.112.11
> ### (2023-02-20)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to 84c2b96 [Renovate Bot] </summary>
> 
>> ### leviathan-2.22.0
>> #### (2023-02-20)
>> 
>> * Update core/contracts digest to 93ba80c [Renovate Bot]
>> 
> 
> </details>
> 
> 

</details>

# v2.112.10
## (2023-02-20)


<details>
<summary> Update layers/meta-balena to c7ef4ad6fe401699d0c24960ab27a8d10511697f [Renovate Bot] </summary>

> ## meta-balena-2.112.10
> ### (2023-02-20)
> 
> * tests: os: secureboot: skip if system is not locked down [Joseph Kogut]
> 

</details>

# v2.112.9
## (2023-02-20)


<details>
<summary> Update layers/meta-balena to 5cc1aa23062247235a71dee20760fd188cd68651 [Renovate Bot] </summary>

> ## meta-balena-2.112.9
> ### (2023-02-20)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to 8a7bdcc [Renovate Bot] </summary>
> 
>> ### leviathan-2.21.0
>> #### (2023-02-20)
>> 
>> * Update core/contracts digest to 103037c [Renovate Bot]
>> 
>> ### leviathan-2.20.1
>> #### (2023-02-20)
>> 
>> * client: throw errors instead of blanket handling [Joseph Kogut]
>> 
> 
> </details>
> 
> 

</details>

# v2.112.8+rev2
## (2023-02-20)


<details>
<summary> Update contracts to 93ba80ca1ffeced474d0567cc58703cdbeb629d5 [Renovate Bot] </summary>

> ## contracts-2.0.46
> ### (2023-02-20)
> 
> * <owa5X logo> Updated owa5X logo. [Alvaro Guzman]
> 

</details>

# v2.112.8+rev1
## (2023-02-18)


<details>
<summary> Update contracts to 103037ca9624070c01ed388e8fd425bef609e924 [Renovate Bot] </summary>

> ## contracts-2.0.45
> ### (2023-02-18)
> 
> * Add node v19.6.1 v18.14.1 v16.19.1 and v14.21.3 [Trong Nghia Nguyen]
> 

</details>

# v2.112.8
## (2023-02-17)


<details>
<summary> Update layers/meta-balena to 70d37200e8af95b6a784ead0682708c7e7f3acfb [Renovate Bot] </summary>

> ## meta-balena-2.112.8
> ### (2023-02-17)
> 
> 
> <details>
> <summary> Update balena-supervisor to v14.9.1 [Renovate Bot] </summary>
> 
>> ### balena-supervisor-14.9.1
>> #### (2023-02-15)
>> 
>> * Always lower case the cpu id to avoid bouncing between casing when reporting [Pagan Gazzard]
>> 
> 
> </details>
> 
> 

</details>

# v2.112.7
## (2023-02-16)


<details>
<summary> Update layers/meta-balena to 9fdf1011b4061ed579c71dfb58f22a97f904a50b [Renovate Bot] </summary>

> ## meta-balena-2.112.7
> ### (2023-02-16)
> 
> * renovate: Only consider github releases when bumping engine [Kyle Harding]
> 

</details>

# v2.112.6
## (2023-02-16)


<details>
<summary> Update layers/meta-balena to fd42070393600c11ae162b35f126b2632c3bb694 [Renovate Bot] </summary>

> ## meta-balena-2.112.6
> ### (2023-02-16)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to 92cb71a [Renovate Bot] </summary>
> 
>> ### leviathan-2.20.0
>> #### (2023-02-16)
>> 
>> * Update core/contracts digest to 9b8811f [Renovate Bot]
>> 
>> ### leviathan-2.19.2
>> #### (2023-02-15)
>> 
>> * patch: Improve Getting Started instructions [Vipul Gupta (@vipulgupta2048)]
>> 
> 
> </details>
> 
> 

</details>

# v2.112.5
## (2023-02-16)


<details>
<summary> Update layers/meta-balena to beb261875db907bcfa9ad8604100860c362d9ebe [Renovate Bot] </summary>

> ## meta-balena-2.112.5
> ### (2023-02-16)
> 
> * grub: Add chain module to support multiboot [Alex Gonzalez]
> 

</details>

# v2.112.4+rev1
## (2023-02-16)


<details>
<summary> Update contracts to 9b8811faee63c0884f367537d3411a8d70f0fcd0 [Renovate Bot] </summary>

> ## contracts-2.0.44
> ### (2023-02-16)
> 
> * Add Golang v1.20.1 and v1.19.6 [Trong Nghia Nguyen]
> 

</details>

# v2.112.4
## (2023-02-15)


<details>
<summary> Update layers/meta-balena to e9e5601e6bb0c4ee4ab51094714f88ce074b4b09 [Renovate Bot] </summary>

> ## meta-balena-2.112.4
> ### (2023-02-15)
> 
> * Update backports with current 2.102.x [BalenaCI github workflow]
> 
> ## meta-balena-2.112.3
> ### (2023-02-15)
> 
> * workflows: update-backports: remove skipping tests [Alex Gonzalez]
> 
> ## meta-balena-2.112.2
> ### (2023-02-15)
> 
> * workflows: add update-backports [Alex Gonzalez]
> 

</details>

# v2.112.1
## (2023-02-15)


<details>
<summary> Update layers/meta-balena to dcef4ce75f4f77bdcf941d0c095487bc4bc128f4 [Renovate Bot] </summary>

> ## meta-balena-2.112.1
> ### (2023-02-15)
> 
> * Update aufs5 kernel patches for 5.10 versions [Florin Sarbu]
> 

</details>

# v2.112.0
## (2023-02-14)


<details>
<summary> Update layers/meta-balena to 7cc56305880ded60850c3440840dcdba823bd179 [Renovate Bot] </summary>

> ## meta-balena-2.112.0
> ### (2023-02-14)
> 
> 
> <details>
> <summary> Update balena-supervisor to v14.9.0 [Renovate Bot] </summary>
> 
>> ### balena-supervisor-14.9.0
>> #### (2023-02-14)
>> 
>> * Find and remove duplicate networks [Felipe Lalanne]
>> * Reference networks by Id instead of by name [Felipe Lalanne]
>> 
> 
> </details>
> 
> 

</details>

# v2.111.4
## (2023-02-14)


<details>
<summary> Update layers/meta-balena to b48ce7abc1eb2506eb81ebbb18a1c4b90e55c4d4 [Renovate Bot] </summary>

> ## meta-balena-2.111.4
> ### (2023-02-14)
> 
> * tests: hup: fix flashing for tx2 [rcooke-warwick]
> 

</details>

# v2.111.3
## (2023-02-14)


<details>
<summary> Update layers/meta-balena to a1621d4de1730a4f943f758b7fd7896d870ef9f7 [Renovate Bot] </summary>

> ## meta-balena-2.111.3
> ### (2023-02-14)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to 975e8ca [Renovate Bot] </summary>
> 
>> ### leviathan-2.19.1
>> #### (2023-02-14)
>> 
>> * docker-compose: qemu: remove dep on swtpm [Joseph Kogut]
>> 
> 
> </details>
> 
> 

</details>

# v2.111.2
## (2023-02-13)


<details>
<summary> Update layers/meta-balena to 3e652503831c517ed60bc838c250d2910f2de8fe [Renovate Bot] </summary>

> ## meta-balena-2.111.2
> ### (2023-02-13)
> 
> * docs: add section for sb/fde opt-in [Joseph Kogut]
> 

</details>

# v2.111.1
## (2023-02-13)


<details>
<summary> Update layers/meta-balena to ad77fa3dacfa32044deb80c2266e3c2d8e1e13dd [Renovate Bot] </summary>

> ## meta-balena-2.111.1
> ### (2023-02-13)
> 
> * resin-init-flasher: do not report progress if unprovisioned [Alex Gonzalez]
> * resin-init-flasher: check splash configuration exists before copying [Alex Gonzalez]
> * resin-init-flasher: Move configuration data definitions to config file [Alex Gonzalez]
> 

</details>

# v2.111.0
## (2023-02-11)


<details>
<summary> Update layers/meta-balena to 18d3baaee23803f2b15e45c1ce3b1446e7a87eb1 [Renovate Bot] </summary>

> ## meta-balena-2.111.0
> ### (2023-02-11)
> 
> 
> <details>
> <summary> Update balena-supervisor to v14.8.0 [Renovate Bot] </summary>
> 
>> ### balena-supervisor-14.8.0
>> #### (2023-02-10)
>> 
>> * Remove dependent devices content in codebase [Christina Ying Wang]
>> 
> 
> </details>
> 
> 

</details>

# v2.110.4
## (2023-02-10)


<details>
<summary> Update layers/meta-balena to 152fe5b0fde438279bf0bc05e8f51d2cafb28fc0 [Renovate Bot] </summary>

> ## meta-balena-2.110.4
> ### (2023-02-10)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to 589449d [Renovate Bot] </summary>
> 
>> ### leviathan-2.19.0
>> #### (2023-02-10)
>> 
>> * Update core/contracts digest to 35f4223 [Renovate Bot]
>> 
> 
> </details>
> 
> 

</details>

# v2.110.3+rev1
## (2023-02-10)


<details>
<summary> Update contracts to 35f42232b2c24e9a43c4b0e171f9644b1b12a686 [Renovate Bot] </summary>

> ## contracts-2.0.43
> ### (2023-02-10)
> 
> * Add Fedora 37 (latest) and 38 [Trong Nghia Nguyen]
> * Add Python v3.11.2 and v3.10.10 [Trong Nghia Nguyen]
> 

</details>

# v2.110.3
## (2023-02-09)


<details>
<summary> Update layers/meta-balena to 2c4c90350f1748a5b8d11441d84023c65069f01d [Renovate Bot] </summary>

> ## meta-balena-2.110.3
> ### (2023-02-09)
> 
> * os-helpers: remove shebangs as these are not meant to be executed [Alex Gonzalez]
> * resindataexpander: Fix formatting [Alex Gonzalez]
> * resin-init-flasher: Extract code that resolved internal device [Alex Gonzalez]
> * os-helpers-fs: Add shared code from resin-init-flasher [Alex Gonzalez]
> * resin-init-flasher: remove unused variable [Alex Gonzalez]
> * resin-init-flasher: Use the default for the external boot partition mount [Alex Gonzalez]
> * resin-init-flasher: search for images to copy instead of hardcoding paths [Alex Gonzalez]
> * resin-init-flasher: Do not  hardcode the path to the internal boot device [Alex Gonzalez]
> * resin-init-flasher: remove systemd dependency [Alex Gonzalez]
> * resin-init-flasher: Do not hardcode path to the raw image [Alex Gonzalez]
> * initrdscript: prepare: expose path to initramfs logs [Alex Gonzalez]
> * initrdscript: resindataexpander: skip for flasher images [Alex Gonzalez]
> * docs: add initramfs overview [Alex Gonzalez]
> 
> ## meta-balena-2.110.2
> ### (2023-02-07)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to 4f63a2d [Renovate Bot] </summary>
> 
>> ### leviathan-2.18.1
>> #### (2023-02-07)
>> 
>> * patch: Automate docs deployment with Flowzone [Vipul Gupta (@vipulgupta2048)]
>> 
>> ### leviathan-2.18.0
>> #### (2023-02-07)
>> 
>> * Update core/contracts digest to 7797750 [Renovate Bot]
>> 
>> ### leviathan-2.17.6
>> #### (2023-02-07)
>> 
>> * patch: Update client lockfile [Vipul Gupta (@vipulgupta2048)]
>> * patch: Update core lockfile [Vipul Gupta (@vipulgupta2048)]
>> 
>> ### leviathan-2.17.5
>> #### (2023-02-06)
>> 
>> * patch: Update core dependencies [Vipul Gupta (@vipulgupta2048)]
>> 
> 
> </details>
> 
> 
> ## meta-balena-2.110.1
> ### (2023-02-07)
> 
> * renovate: Include to and from versions for supervisor and engine [Kyle Harding]
> 
> ## meta-balena-2.110.0
> ### (2023-02-07)
> 
> * Update balena-supervisor to v14.7.1 [Renovate Bot]
> 
> ## meta-balena-2.109.2
> ### (2023-02-07)
> 
> * efitools: backport patch to fix build failure [Joseph Kogut]
> * efitools: fix cross-compilation on arm [Joseph Kogut]
> * Only include EFI tools if the machine feature is defined [Alex Gonzalez]
> 
> ## meta-balena-2.109.1
> ### (2023-02-06)
> 
> * resin-extra-udev-rules: Remove after all device types have been updated [Alex Gonzalez]
> 
> ## meta-balena-2.109.0
> ### (2023-02-05)
> 
> * kernel-balena: Remove apparmor support [Alex Gonzalez]
> 
> ## meta-balena-2.108.39
> ### (2023-02-03)
> 
> * flasher: handle user mode system w/out secure boot [Joseph Kogut]
> * flasher: fix keys not enrolling with secure boot enabled [Joseph Kogut]
> * flasher: fix secure boot setup with enrolled keys [Joseph Kogut]
> 
> ## meta-balena-2.108.38
> ### (2023-02-03)
> 
> 
> <details>
> <summary> Update leviathan to v2.17.4 [Kyle Harding] </summary>
> 
>> ### leviathan-2.17.4
>> #### (2023-01-28)
>> 
>> * patch: Upgrade client to v18 [Vipul Gupta (@vipulgupta2048)]
>> 
>> ### leviathan-2.17.3
>> #### (2023-01-26)
>> 
>> * patch: Update client dependencies [Vipul Gupta (@vipulgupta2048)]
>> 
>> ### leviathan-2.17.2
>> #### (2023-01-19)
>> 
>> * chore(deps): update alpine docker tag to v3.17.1 [renovate[bot]]
>> 
>> ### leviathan-2.17.1
>> #### (2023-01-19)
>> 
>> * patch: Convert balenaCloudInteractor to JS [Vipul Gupta (@vipulgupta2048)]
>> 
>> ### leviathan-2.17.0
>> #### (2023-01-19)
>> 
>> * chore(deps): update dependency json5 [security] [renovate[bot]]
>> 
>> ### leviathan-2.16.1
>> #### (2023-01-19)
>> 
>> * split swtpm service into separate compose file [Joseph Kogut]
>> 
>> ### leviathan-2.16.0
>> #### (2023-01-18)
>> 
>> * chore(deps): update core/contracts digest to 8392bb2 [renovate[bot]]
>> 
>> ### leviathan-2.15.1
>> #### (2023-01-17)
>> 
>> * patch: Drop config NPM package [Vipul Gupta (@vipulgupta2048)]
>> 
>> ### leviathan-2.15.0
>> #### (2023-01-14)
>> 
>> * chore(deps): update dependency ansi-regex [security] [renovate[bot]]
>> 
>> ### leviathan-2.14.9
>> #### (2023-01-05)
>> 
>> * compose: qemu: add swtpm service [Joseph Kogut]
>> 
> 
> </details>
> 
> 
> ## meta-balena-2.108.37
> ### (2023-02-02)
> 
> * Update balena-engine to v20.10.26 [Renovate Bot]
> 
> ## meta-balena-2.108.36
> ### (2023-02-02)
> 
> * flasher: remove duplicate EFI boot entries [Joseph Kogut]
> * flasher: create EFI boot entry [Joseph Kogut]
> * common: os-helpers-fs: fix get_dev_path_from_label w/ luks [Joseph Kogut]
> * flasher: make secure boot opt-in [Joseph Kogut]
> * flasher: ensure image is signed before enrollment [Joseph Kogut]
> * flasher: refactor secure boot block [Joseph Kogut]
> 
> ## meta-balena-2.108.35
> ### (2023-02-01)
> 
> * renovate: Add regex manager for balena-engine [Kyle Harding]
> 
> ## meta-balena-2.108.34
> ### (2023-02-01)
> 
> * docs: Add secure boot and disk encryption overview [Alex Gonzalez]
> * hostapp-update-hooks: Fail if new keys are used [Alex Gonzalez]
> * resin-init-flasher: In setupmode program new keys [Alex Gonzalez]
> 
> ## meta-balena-2.108.33
> ### (2023-02-01)
> 
> * tests: os: skip persistent logging test for pi0 [rcooke-warwick]
> 
> ## meta-balena-2.108.32
> ### (2023-02-01)
> 
> * efitools: Allow builds for ARM architecture [Alex Gonzalez]
> 
> ## meta-balena-2.108.31
> ### (2023-02-01)
> 
> * rollback-health: bind-mount EFI partition when split from boot [Michal Toman]
> 
> ## meta-balena-2.108.30
> ### (Invalid date)
> 
> * redsocks: Deploy README and sample configration file [Alexandru Costache]
> * recipes-bsp/u-boot: Import extra uboot environment from scanned devices [Alexandru Costache]
> 
> ## meta-balena-2.108.29
> ### (2023-01-28)
> 
> * bluez: Update to v5.66 [Alex Gonzalez]
> 
> ## meta-balena-2.108.28
> ### (2023-01-26)
> 
> * patch: Update balenaOS docs title [Vipul Gupta (@vipulgupta2048)]
> 
> ## meta-balena-2.108.27
> ### (2023-01-20)
> 
> * tests: os: fix tests that use glider on rpi0 [rcooke-warwick]
> 
> ## meta-balena-2.108.26
> ### (2023-01-20)
> 
> * Enable back connectivity check in NetworkManager [Zahari Petkov]
> 
> ## meta-balena-2.108.25
> ### (2023-01-18)
> 
> * tests: os: add basic SB/FDE tests [Joseph Kogut]
> 
> ## meta-balena-2.108.24
> ### (2023-01-18)
> 
> * networkmanager: Make iptables wait for xtables.lock [Zahari Petkov]
> 
> ## meta-balena-2.108.23
> ### (2023-01-16)
> 
> * balena-keys: rebuild if keys change [Alex Gonzalez]
> * classes: sign-*: resign if keys change [Alex Gonzalez]
> 
> ## meta-balena-2.108.22
> ### (2023-01-16)
> 
> * workflows: esr: use semver compatible versions [Alex Gonzalez]
> 
> ## meta-balena-2.108.21
> ### (2023-01-14)
> 
> * efitools: Package lock down EFI image into its own package [Alex Gonzalez]
> 
> ## meta-balena-2.108.20
> ### (2023-01-12)
> 
> * workflows: meta-balena-esr: Fix version calculation [Alex Gonzalez]
> 
> ## meta-balena-2.108.19
> ### (2023-01-10)
> 
> * redsocks: Increase maximum number of open files [Alex Gonzalez]
> 

</details>

# v2.108.18+rev4
## (2023-02-09)


<details>
<summary> Update contracts to 79998a238ca981b890dfb9206f50bde2d367ff7c [Renovate Bot] </summary>

> ## contracts-2.0.42
> ### (2023-02-06)
> 
> * Add golang v1.20 [Trong Nghia Nguyen]
> * Add node v19.6.0 and v18.14.0 [Trong Nghia Nguyen]
> 
> ## contracts-2.0.41
> ### (2023-02-01)
> 
> * Add support for latest dotnet releases v7 (7.0.102) and v6 (6.0.113) [Trong Nghia Nguyen]
> * Add node v19.5.0 [Trong Nghia Nguyen]
> 
> ## contracts-2.0.40
> ### (2023-01-18)
> 
> * Add golang v1.19.5 and v1.18.10 [Trong Nghia Nguyen]
> 
> ## contracts-2.0.39
> ### (2023-01-12)
> 
> * hw.device-type: Add Radxa CM3 on Raspberry Pi Compute Module 4 IO Board [Florin Sarbu]
> 
> ## contracts-2.0.38
> ### (2023-01-07)
> 
> * Forecr DSBOARD NX2 Xavier NX eMMC: Add community device-type [Alexandru Costache]
> 
> ## contracts-2.0.37
> ### (2023-01-07)
> 
> * Add node v18.13.0 and v19.4.0 [Trong Nghia Nguyen]
> 

</details>

# v2.108.18+rev3
## (2023-02-09)


<details>
<summary> Update balena-yocto-scripts to fe6beafdcfa7406b20257cf67a6b74cd8f59142f [Renovate Bot] </summary>

> ## balena-yocto-scripts-1.19.23
> ### (2023-01-28)
> 
> * balena-generate-ami: increase import snapshot timeout [Alex Gonzalez]
> * balena-generate-ami: remove s3 temporary image if snapshot import times out [Alex Gonzalez]
> * balena-generate-ami: match instance type with image type [Alex Gonzalez]
> * balena-generate-ami: fix linter warnings [Alex Gonzalez]
> 
> ## balena-yocto-scripts-1.19.22
> ### (2023-01-25)
> 
> * balena-generate-ami: allow for staging deployments [Alex Gonzalez]
> * jenkins_generate_ami: allow for staging deployment [Alex Gonzalez]
> 
> ## balena-yocto-scripts-1.19.21
> ### (2023-01-19)
> 
> * balene-generate-ami: remove key name [Alex Gonzalez]
> 
> ## balena-yocto-scripts-1.19.20
> ### (2023-01-18)
> 
> * jenkins_generate_ami: default to pull cloud-config apps from balena_os [Alex Gonzalez]
> 
> ## balena-yocto-scripts-1.19.19
> ### (2023-01-14)
> 
> * balena-generate-ami: do not remove AMI snapshot [Alex Gonzalez]
> * jenkins_generate_ami: use balena_os tokens instead of org specific token [Alex Gonzalez]
> * jenkins_build: respect the preserve build flag [Alex Gonzalez]
> * balena-generate-ami: cleanup images after deployment [Alex Gonzalez]
> * balena-generate-ami: test image before making it public [Alex Gonzalez]
> 

</details>

# v2.108.18+rev2
## (2023-01-26)

* add meta-perl to bblayers.conf [Alex Gonzalez]

# v2.108.18+rev1
## (2023-01-13)

* Add ESR workflow [Alex Gonzalez]

# v2.108.18
## (2023-01-10)


<details>
<summary> Update layers/meta-balena to 7b8d9a8b591487aefcdcd522d385ec14abaa1be6 [renovate[bot]] </summary>

> ## meta-balena-2.108.18
> ### (2023-01-09)
> 
> * Revert "flasher: output logs to serial console" [Joseph Kogut]
> 

</details>

# v2.108.17+rev1
## (2023-01-10)


<details>
<summary> Update balena-yocto-scripts to 56bb055d91481023a6b6cff92d61ebfffa884139 [renovate[bot]] </summary>

> ## balena-yocto-scripts-1.19.18
> ### (2023-01-09)
> 
> * balena-generate-ami: Enable TPM support on x86_64 only [Michal Toman]
> 

</details>

# v2.108.17
## (2023-01-09)


<details>
<summary> Update layers/meta-balena to 8347887ab69018c1e4bcf0a7aecbf6faf85af2bd [renovate[bot]] </summary>

> ## meta-balena-2.108.17
> ### (2023-01-09)
> 
> * Update balena-os/balena-supervisor to v14.4.10 [renovate[bot]]
> 
> ## meta-balena-2.108.16
> ### (2023-01-09)
> 
> * balena-supervisor: Set the supervisor package version [Kyle Harding]
> 
> ## meta-balena-2.108.15
> ### (2023-01-05)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to e23c1bb [renovate[bot]] </summary>
> 
>> ### leviathan-2.14.8
>> #### (2023-01-05)
>> 
>> * chore(deps): update dependency eslint-config-standard to 17.0.0 [renovate[bot]]
>> 
>> ### leviathan-2.14.7
>> #### (2023-01-05)
>> 
>> * worker: Deprecate the WORKER_RELEASE env var [Kyle Harding]
>> 
>> ### leviathan-2.14.6
>> #### (2023-01-05)
>> 
>> * e2e: Switch from rpi4 to rpi3 for e2e tests [Kyle Harding]
>> * core: Increase the default timeout for worker connections to 30s [Kyle Harding]
>> 
>> ### leviathan-2.14.5
>> #### (2023-01-04)
>> 
>> * renovate: Disable automerge for major and minor updates [Kyle Harding]
>> 
>> ### leviathan-2.14.4
>> #### (2023-01-04)
>> 
>> * chore(deps): update dependency typedoc to 0.23.23 [renovate[bot]]
>> 
> 
> </details>
> 
> 
> ## meta-balena-2.108.14
> ### (2023-01-04)
> 
> * tests: os: chrony: disable NTP w/ dnsmasq dbus API [Joseph Kogut]
> 

</details>

# v2.108.13
## (2023-01-04)


<details>
<summary> Update layers/meta-balena to 7aaa2abec902574d9e777a88464eda5be2810666 [renovate[bot]] </summary>

> ## meta-balena-2.108.13
> ### (2023-01-04)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to 44dceb4 [renovate[bot]] </summary>
> 
>> ### leviathan-2.14.3
>> #### (2023-01-04)
>> 
>> * chore(deps): update dependency eslint to 8.31.0 [renovate[bot]]
>> 
> 
> </details>
> 
> 
> <details>
> <summary> Update tests/leviathan digest to 4383482 [renovate[bot]] </summary>
> 
>> ### leviathan-2.14.3
>> #### (2023-01-04)
>> 
>> * chore(deps): update dependency eslint to 8.31.0 [renovate[bot]]
>> 
> 
> </details>
> 
> 
> ## meta-balena-2.108.12
> ### (2023-01-04)
> 
> * tests/hup: Avoid an old engine bug when pulling multiarch images on rpi [Kyle Harding]
> 

</details>

# v2.108.11
## (2023-01-04)


<details>
<summary> Update layers/meta-balena to df321d4ad4831d27188ac9bf538600ccaaabc9b3 [renovate[bot]] </summary>

> ## meta-balena-2.108.11
> ### (2023-01-03)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to d3485ab [renovate[bot]] </summary>
> 
>> ### leviathan-2.13.0
>> #### (2023-01-03)
>> 
>> * Revert "minor: Add @balena/leviathan-test-helpers package" [Kyle Harding]
>> 
>> ### leviathan-2.12.4
>> #### (Invalid date)
>> 
>> * chore(deps): update dependency eslint-plugin-standard to 4.1.0 [renovate[bot]]
>> 
> 
> </details>
> 
> 
> ## meta-balena-2.108.10
> ### (Invalid date)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to 7d6326d [renovate[bot]] </summary>
> 
>> ### leviathan-2.12.3
>> #### (Invalid date)
>> 
>> * chore(deps): update dependency eslint-plugin-node to 11.1.0 [renovate[bot]]
>> 
>> ### leviathan-2.12.2
>> #### (2022-12-29)
>> 
>> * Run out-of-band e2e tests after Flowzone passes [Kyle Harding]
>> 
>> ### leviathan-2.12.1
>> #### (2022-12-29)
>> 
>> * chore(deps): update dependency eslint-plugin-jsdoc to 39.6.4 [renovate[bot]]
>> 
>> ### leviathan-2.12.0
>> #### (2022-12-29)
>> 
>> * chore(deps): update core/contracts digest to 4698e4e [renovate[bot]]
>> 
>> ### leviathan-2.11.9
>> #### (2022-12-29)
>> 
>> * chore(deps): update dependency balena-os/leviathan-worker to 2.6.13 [renovate[bot]]
>> 
> 
> </details>
> 
> 

</details>

# v2.108.9
## (2022-12-29)


<details>
<summary> Update layers/meta-balena to 95d8b0c5bfb36a164081f417b52c8de16f2dc474 [renovate[bot]] </summary>

> ## meta-balena-2.108.9
> ### (2022-12-29)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to 1dcb432 [renovate[bot]] </summary>
> 
>> ### leviathan-2.11.8
>> #### (2022-12-28)
>> 
>> * chore(deps): update dependency eslint-config-prettier to 8.5.0 [renovate[bot]]
>> 
> 
> </details>
> 
> 
> ## meta-balena-2.108.8
> ### (2022-12-28)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to e09fae4 [renovate[bot]] </summary>
> 
>> ### leviathan-2.11.7
>> #### (2022-12-28)
>> 
>> * renovate: Remove v prefix from leviathan-worker github-tags [Kyle Harding]
>> 
> 
> </details>
> 
> 

</details>

# v2.108.7
## (2022-12-28)


<details>
<summary> Update layers/meta-balena to 68ec8ca1388c8e442acf1235dc573aeb12ff385a [renovate[bot]] </summary>

> ## meta-balena-2.108.7
> ### (2022-12-28)
> 
> * tests: os: fix modem test teardown [rcooke-warwick]
> 

</details>

# v2.108.6
## (2022-12-28)


<details>
<summary> Update layers/meta-balena to 3a45aa111217e64ef6ab8cbd16d34a12ece49a3c [renovate[bot]] </summary>

> ## meta-balena-2.108.6
> ### (2022-12-27)
> 
> * flasher: output logs to serial console [Joseph Kogut]
> 

</details>

# v2.108.5+rev2
## (2022-12-24)


<details>
<summary> Update contracts to 4698e4ef55fdc61aa3df8d8494f2cbbd306b26c9 [renovate[bot]] </summary>

> ## contracts-2.0.36
> ### (2022-12-22)
> 
> * Fix owa5x slug [Trong Nghia Nguyen]
> 

</details>

# v2.108.5+rev1
## (2022-12-23)


<details>
<summary> Update balena-yocto-scripts to 0f1d0265bbabdb2b869f6cf9363d418b52681ffc [renovate[bot]] </summary>

> ## balena-yocto-scripts-1.19.17
> ### (2022-12-23)
> 
> * jenkins_generate_ami: support using both live and installer images as AMIs [Alex Gonzalez]
> * balena-generate-ami: Enable nitroTPM support [Alex Gonzalez]
> * jenkins_build: add argument to build OS development images [Alex Gonzalez]
> 
> ## balena-yocto-scripts-1.19.16
> ### (2022-12-16)
> 
> * dockerfile: balena-push-env: update balena CLI version to v14.5.15 [Alex Gonzalez]
> * jenkins_generate_ami: add balena org for preloaded app [Alex Gonzalez]
> * jenkins_generate_ami: distinguish between staging and production [Alex Gonzalez]
> 
> ## balena-yocto-scripts-1.19.15
> ### (2022-12-16)
> 
> * workflows: add flowzone [Alex Gonzalez]
> 

</details>

# v2.108.5
## (2022-12-22)


<details>
<summary> Update layers/meta-balena to 4f5dc08a949432990996fbb0e9955d261c1282b3 [renovate[bot]] </summary>

> ## meta-balena-2.108.5
> ### (2022-12-21)
> 
> * Engine healthcheck: deal with empty uuid file [Leandro Motta Barros]
> 

</details>

# v2.108.4+rev1
## (2022-12-21)


<details>
<summary> Update contracts to b65d5bd372587d4aaabba526d34f67c3f63ea90b [renovate[bot]] </summary>

> ## contracts-2.0.35
> ### (2022-12-20)
> 
> * hw.device-type: Add Owasys owa5X device [Alvaro Guzman]
> 
> ## contracts-2.0.34
> ### (2022-12-16)
> 
> * Flowzone: Allow external contributions [Florin Sarbu]
> 
> ## contracts-2.0.33
> ### (2022-12-16)
> 
> * Flowzone: Use inherited secrets [Florin Sarbu]
> 
> ## contracts-2.0.32
> ### (2022-12-15)
> 
> * Add node v19.3.0 v16.19.0 and v14.21.2 [Trong Nghia Nguyen]
> 
> ## contracts-2.0.31
> ### (2022-12-10)
> 
> * Add partials for dotnet v7 [Trong Nghia Nguyen]
> 
> ## contracts-2.0.30
> ### (2022-12-09)
> 
> * Add support for Alpine Linux v3.17 [Trong Nghia Nguyen]
> * Add dotnet v7, update v6.x and v3.x to latest versions [Trong Nghia Nguyen]
> * Add Python v3.11.1 v3.10.9 v3.9.16 v3.8.16 and v3.7.16 [Trong Nghia Nguyen]
> * Add Golang v1.19.4 and v1.18.9 [Trong Nghia Nguyen]
> 

</details>

# v2.108.4
## (2022-12-20)


<details>
<summary> Update layers/meta-balena to d8168e9bcdba5a017acb33a611182b9889e4c50b [renovate[bot]] </summary>

> ## meta-balena-2.108.4
> ### (2022-12-20)
> 
> * distro: For OS development, enable serial console [Alex Gonzalez]
> 
> ## meta-balena-2.108.3
> ### (2022-12-20)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to f06d285 [renovate[bot]] </summary>
> 
>> ### leviathan-2.11.6
>> #### (2022-12-16)
>> 
>> * Fix renovate extends syntax to include balena-io config [Kyle Harding]
>> 
>> ### leviathan-2.11.5
>> #### (2022-12-16)
>> 
>> * renovate: Inherit settings from balena-io/renovate-config [Kyle Harding]
>> 
>> ### leviathan-2.11.4
>> #### (2022-12-16)
>> 
>> * add logging and timeout to balena push [rcooke-warwick]
>> 
> 
> </details>
> 
> 
> ## meta-balena-2.108.2
> ### (2022-12-19)
> 
> * Update balena-os/balena-supervisor to v14.4.9 [renovate[bot]]
> 
> ## meta-balena-2.108.1
> ### (2022-12-18)
> 
> * common: signing: improve debug output on failure [Joseph Kogut]
> 

</details>

# v2.108.0+rev1
## (2022-12-19)

* Add am335x-boneblack-uboot-univ to rootfs for people using gpios on BeagleBone Black [Aodhan Murray]

# v2.108.0
## (2022-12-17)


<details>
<summary> Update layers/meta-balena to 1b3b0a273b8aeb2ac69805253657c7ec2ec670b4 [renovate[bot]] </summary>

> ## meta-balena-2.108.0
> ### (2022-12-16)
> 
> * Update NetworkManager to 1.40.4 [Zahari Petkov]
> 
> ## meta-balena-2.107.40
> ### (2022-12-16)
> 
> * Add upstream resolvconf 1.91 recipe for kirkstone [Zahari Petkov]
> 
> ## meta-balena-2.107.39
> ### (2022-12-16)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to f44bbbd [renovate[bot]] </summary>
> 
>> ### leviathan-2.11.3
>> #### (2022-12-16)
>> 
>> * Disable renovate config for now [Kyle Harding]
>> * Restore worker release env var [Kyle Harding]
>> 
>> ### leviathan-2.11.2
>> #### (2022-12-15)
>> 
>> * Update Node.js to v12.22.12 [Renovate Bot]
>> 
>> ### leviathan-2.11.1
>> #### (2022-12-15)
>> 
>> * Remove dependabot as renovate is enabled in balena-io/renovate-config [Kyle Harding]
>> * Pin worker to a release and add renovate regex template [Kyle Harding]
>> 
>> ### leviathan-2.11.0
>> #### (2022-12-15)
>> 
>> * Update core/contracts digest to 08f029b [Renovate Bot]
>> 
>> ### leviathan-2.10.12
>> #### (2022-12-15)
>> 
>> * Revert "Avoid conflicting docker subnets" [Vipul Gupta]
>> 
> 
> </details>
> 
> 
> ## meta-balena-2.107.38
> ### (2022-12-16)
> 
> * Update balena-os/balena-supervisor to v14.4.8 [renovate[bot]]
> 
> ## meta-balena-2.107.37
> ### (2022-12-15)
> 
> * tests: cloud: simplify apps to speedup suite [rcooke-warwick]
> 
> ## meta-balena-2.107.36
> ### (2022-12-15)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to 48ffd13 [renovate[bot]] </summary>
> 
>> ### leviathan-2.10.11
>> #### (2022-12-14)
>> 
>> * Avoid conflicting docker networks [Kyle Harding]
>> 
> 
> </details>
> 
> 

</details>

# v2.107.35
## (2022-12-15)


<details>
<summary> Update layers/meta-balena to 6bba8a6b779d93ad1765708ca6704db90ec81769 [renovate[bot]] </summary>

> ## meta-balena-2.107.35
> ### (2022-12-15)
> 
> * patch: Add default debug object to test config [Vipul Gupta (@vipulgupta2048)]
> 
> ## meta-balena-2.107.34
> ### (2022-12-14)
> 
> * initrdscripts: Wait for udev processing to complete when unlocking LUKS devices [Michal Toman]
> 
> ## meta-balena-2.107.33
> ### (2022-12-14)
> 
> * tests: hup: clean up inactive partition pre hup [rcooke-warwick]
> 
> ## meta-balena-2.107.32
> ### (2022-12-14)
> 
> * tests/cloud: Increase the wait time for services to start [Kyle Harding]
> 
> ## meta-balena-2.107.31
> ### (2022-12-14)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to 27b78a4 [renovate[bot]] </summary>
> 
>> ### leviathan-2.10.10
>> #### (2022-12-13)
>> 
>> * Enable external contributions via flowzone [Kyle Harding]
>> 
> 
> </details>
> 
> 
> ## meta-balena-2.107.30
> ### (2022-12-13)
> 
> * extra-udev-rules: Update teensy.rules [Alex Gonzalez]
> * extra-udev-rules: Rename recipe [Alex Gonzalez]
> 
> ## meta-balena-2.107.29
> ### (2022-12-13)
> 
> * balena-image-initramfs: disable redundant compression [Joseph Kogut]
> 
> ## meta-balena-2.107.28
> ### (2022-12-12)
> 
> * initrdscripts: Only unlock LUKS partitions on the OS drive [Michal Toman]
> 
> ## meta-balena-2.107.27
> ### (2022-12-12)
> 
> * chrony: disable reverse dns lookups in healthcheck [Ken Bannister]
> 
> ## meta-balena-2.107.26
> ### (2022-12-12)
> 
> * connectivity: Add linux firmware for iwlwifi 9260 [Alex Gonzalez]
> 
> ## meta-balena-2.107.25
> ### (2022-12-11)
> 
> * image_types_balena: fix inconsistency with flasher image partition naming [Alex Gonzalez]
> 
> ## meta-balena-2.107.24
> ### (2022-12-09)
> 
> * Update balena-os/balena-supervisor to v14.4.6 [renovate[bot]]
> 
> ## meta-balena-2.107.23
> ### (2022-12-09)
> 
> * patch: Add product documentation [Vipul Gupta (@vipulgupta2048)]
> 
> ## meta-balena-2.107.22
> ### (2022-12-09)
> 
> * tests: os: fsck: make compatible with old yocto releaes [rcooke-warwick]
> 
> ## meta-balena-2.107.21
> ### (2022-12-08)
> 
> * tests/connectivity: Run the proxy tests with the actual redsocks uid of the DUT [Florin Sarbu]
> 
> ## meta-balena-2.107.20
> ### (2022-12-07)
> 
> * kernel-balena: enable zstd compression [Joseph Kogut]
> 
> ## meta-balena-2.107.19
> ### (2022-12-06)
> 
> * image_types_balena: generate bmap file [Joseph Kogut]
> * flasher: write disk image skipping sparse blocks [Joseph Kogut]
> * image_types_balena: create sparse disk image [Joseph Kogut]
> 
> ## meta-balena-2.107.18
> ### (2022-12-04)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to fe4d6a1 [renovate[bot]] </summary>
> 
>> ### leviathan-2.10.9
>> #### (2022-12-02)
>> 
>> * Revert "docker-compose: stop using the default docker bridge" [Kyle Harding]
>> 
> 
> </details>
> 
> 
> ## meta-balena-2.107.17
> ### (2022-12-02)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to de97fa2 [renovate[bot]] </summary>
> 
>> ### leviathan-2.10.8
>> #### (Invalid date)
>> 
>> * patch: Improve archivelogs journalctl command [Vipul Gupta (@vipulgupta2048)]
>> * core: Reduce to 30 the retries number when trying to get the IP address of the DUT [Florin Sarbu]
>> 
>> ### leviathan-2.10.7
>> #### (Invalid date)
>> 
>> * docker-compose: stop using the default docker bridge [Alex Gonzalez]
>> 
>> ### leviathan-2.10.6
>> #### (2022-11-29)
>> 
>> * os/balenaos: Remove hidden attribute from DUT wireless connection file [Alexandru Costache]
>> 
>> ### leviathan-2.10.5
>> #### (2022-11-29)
>> 
>> * patch: Add debug: unstable to docs [Vipul Gupta (@vipulgupta2048)]
>> 
> 
> </details>
> 
> 
> ## meta-balena-2.107.16
> ### (2022-12-01)
> 
> * Refactor and clean up the purge data tests [Kyle Harding]
> 
> ## meta-balena-2.107.15
> ### (2022-12-01)
> 
> * Updated CBS Docs Updated link to the CDS Product Repo [Ryan H]
> 

</details>

# v2.107.14+rev1
## (2022-12-01)


<details>
<summary> Update contracts to 5d83fa7ad3a0c95db49ee465c9a77845611f3a3b [renovate[bot]] </summary>

> ## contracts-2.0.29
> ### (Invalid date)
> 
> * Add node v19.2.0 [Trong Nghia Nguyen]
> 
</details>

# v2.107.14
## (2022-11-30)


<details>
<summary> Update layers/meta-balena to 8ea20f929eeb3f52b23874c3bd951c961329ad29 [renovate[bot]] </summary>

> ## meta-balena-2.107.14
> ### (Invalid date)
> 
> * test: os: fix search for active interface [rcooke-warwick]
> 
> ## meta-balena-2.107.13
> ### (2022-11-29)
> 
> * balena-image-flasher: Include LUKS variant of GRUB config with FDE in place [Michal Toman]
> 
> ## meta-balena-2.107.12
> ### (2022-11-28)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to 61016ad [renovate[bot]] </summary>
> 
>> ### leviathan-2.10.4
>> #### (2022-11-25)
>> 
>> * bump contracts to 2.0.27 [rcooke-warwick]
>> 
>> ### leviathan-2.10.3
>> #### (2022-11-24)
>> 
>> * On Apple Silicon we should install balena CLI via npm [Kyle Harding]
>> 
> </details>
> 
> 
> ## meta-balena-2.107.11
> ### (2022-11-25)
> 
> * add os testing docs [rcooke-warwick]
> 
</details>


<details>
<summary> Update layers/meta-balena to fbf651fead37336e826d709f48255897962bdbd5 [renovate[bot]] </summary>

> ## meta-balena-2.107.14
> ### (Invalid date)
> 
> * test: os: fix search for active interface [rcooke-warwick]
> 
> ## meta-balena-2.107.13
> ### (2022-11-29)
> 
> * balena-image-flasher: Include LUKS variant of GRUB config with FDE in place [Michal Toman]
> 
> ## meta-balena-2.107.12
> ### (2022-11-28)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to 61016ad [renovate[bot]] </summary>
> 
>> ### leviathan-2.10.4
>> #### (2022-11-25)
>> 
>> * bump contracts to 2.0.27 [rcooke-warwick]
>> 
>> ### leviathan-2.10.3
>> #### (2022-11-24)
>> 
>> * On Apple Silicon we should install balena CLI via npm [Kyle Harding]
>> 
> </details>
> 
> 
> ## meta-balena-2.107.11
> ### (2022-11-25)
> 
> * add os testing docs [rcooke-warwick]
> 
</details>

# v2.107.9
## (2022-11-24)


<details>
<summary> Update layers/meta-balena to f54177209d23bcc33c32aac8dea7fa40273f3156 [renovate[bot]] </summary>

> ## meta-balena-2.107.9
> ### (2022-11-24)
> 
> * resin-init-flasher: Fix double /dev/ prefix when encrypting partitions [Michal Toman]
> * grub-conf: fix partition indexes in LUKS config [Michal Toman]
> * os-helpers-fs: add dependency on parted [Michal Toman]
> * hostapp-update-hooks: use stage2 bootloader GRUB config when using LUKS [Michal Toman]
> * balena-rollback: Fix partition index detection for luks devices [Michal Toman]
> * balena-rollback: Find following symbolic links [Alex Gonzalez]
> * hostapp-update-hooks: Find following symlinks [Alex Gonzalez]
> * hostapp-update-hooks: Fix partition index detection for luks devices [Alex Gonzalez]
> 
</details>

# v2.107.8
## (2022-11-24)


<details>
<summary> Update layers/meta-balena to ce3b3d7d17723fd03a4df278c6baff10b29be22e [renovate[bot]] </summary>

> ## meta-balena-2.107.8
> ### (2022-11-24)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to bdf8eb2 [renovate[bot]] </summary>
> 
>> ### leviathan-2.10.2
>> #### (2022-11-23)
>> 
>> * add high level architecture overview [rcooke-warwick]
>> 
>> ### leviathan-2.10.1
>> #### (2022-11-23)
>> 
>> * Add conditions for Apple Silicon workstations [Kyle Harding]
>> 
> </details>
> 
> 
> ## meta-balena-2.107.7
> ### (2022-11-23)
> 
> * tests: ssh-auth: rework local authentication with cloud keys to work in testbots [Alex Gonzalez]
> * ssh-auth: do not use a separate custom key [Alex Gonzalez]
> * Revert "test: ssh-auth: fix test cases using custom keys" [Alex Gonzalez]
> 
</details>

# v2.107.6
## (2022-11-23)


<details>
<summary> Update layers/meta-balena to 1add3a4b003475a96b0414a5dec83152eab58bf3 [renovate[bot]] </summary>

> ## meta-balena-2.107.6
> ### (2022-11-22)
> 
> * Update balena-os/balena-supervisor to v14.4.4 [renovate[bot]]
> 
</details>

# v2.107.5
## (2022-11-22)


<details>
<summary> Update layers/meta-balena to d91e674a5bffd7f35944265d244b360bf6e3e8b9 [renovate[bot]] </summary>

> ## meta-balena-2.107.5
> ### (2022-11-22)
> 
> * Update balena-os/balena-supervisor to v14.4.2 [renovate[bot]]
> 
</details>

# v2.107.4
## (2022-11-20)


<details>
<summary> Update layers/meta-balena to 62205779cf90d2ea1c05e95c0a27074822e6e10f [renovate[bot]] </summary>

> ## meta-balena-2.107.4
> ### (2022-11-19)
> 
> * Update balena-os/balena-supervisor to v14.4.1 [renovate[bot]]
> 
</details>

# v2.107.3
## (2022-11-19)


<details>
<summary> Update layers/meta-balena to 8aed005616dd0baa4605440cca234be049354070 [renovate[bot]] </summary>

> ## meta-balena-2.107.3
> ### (2022-11-19)
> 
> * kernel-balena: Kernel version check should include provided version [Alex Gonzalez]
> 
</details>

# v2.107.2
## (2022-11-18)


<details>
<summary> Update layers/meta-balena to a2d882935a9f80b1b685784d7f83d9d81c9805ee [renovate[bot]] </summary>

> ## meta-balena-2.107.2
> ### (2022-11-18)
> 
> * chronyd: allow service status notification socket access to all [Alex Gonzalez]
> * chrony: update to version 4.2 [Alex Gonzalez]
> 
</details>

# v2.107.1
## (2022-11-18)


<details>
<summary> Update layers/meta-balena to df352d2fcc6c70f7eb00e5276208510fe7ec9822 [renovate[bot]] </summary>

> ## meta-balena-2.107.1
> ### (2022-11-17)
> 
> * docs: add RAID setup info [Joseph Kogut]
> 
> ## meta-balena-2.107.0
> ### (2022-11-17)
> 
> * Update balena-os/balena-supervisor to v14.4.0 [renovate[bot]]
> 
</details>

# v2.106.8
## (2022-11-17)


<details>
<summary> Update layers/meta-balena to 8c48d6b05236f1ab2fe8b081181947ed8683b0f1 [renovate[bot]] </summary>

> ## meta-balena-2.106.8
> ### (2022-11-17)
> 
> * classes: kernel-balena: add wireguard module [Alex Gonzalez]
> 
</details>

# v2.106.7
## (2022-11-15)


<details>
<summary> Update layers/meta-balena to f64f63370e54d5ed14e124578ed9193c765ade92 [renovate[bot]] </summary>

> ## meta-balena-2.106.7
> ### (2022-11-15)
> 
> * test: ssh-auth: fix test cases using custom keys [Alex Gonzalez]
> 
</details>

# v2.106.6
## (2022-11-15)


<details>
<summary> Update layers/meta-balena to 0bcd2db1e6e5bf04ad2882028aa26cbab0ee49ea [renovate[bot]] </summary>

> ## meta-balena-2.106.6
> ### (2022-11-15)
> 
> * Update balena-os/balena-supervisor to v14.3.3 [renovate[bot]]
> 
</details>

# v2.106.5+rev1
## (2022-11-15)


<details>
<summary> Update balena-yocto-scripts to 3fbd0884bd7d599664587d0ab25fea22d77323ba [renovate[bot]] </summary>

> ## balena-yocto-scripts-1.19.14
> ### (2022-11-10)
> 
> * jenkins_generate_ami: use a different token [Alex Gonzalez]
> 
</details>

# v2.106.5
## (2022-11-14)


<details>
<summary> Update layers/meta-balena to af180bb6f4c61940cbf23d0b92dbceadea10aa3f [renovate[bot]] </summary>

> ## meta-balena-2.106.5
> ### (2022-11-14)
> 
> * openvpn: fix a race condition that leaves system with no running supervisor [Alex Gonzalez]
> 
</details>

# v2.106.4
## (2022-11-12)


<details>
<summary> Update layers/meta-balena to 5f789c7e57c7be71b8e333ac7127a809d2161935 [renovate[bot]] </summary>

> ## meta-balena-2.106.4
> ### (2022-11-12)
> 
> * ssh-auth: setConfig: run synchronously [Alex Gonzalez]
> * cloud: ssh-auth: use custom path for custom key [Alex Gonzalez]
> * balena-config-vars: Set permissions for cache file [Alex Gonzalez]
> 
> ## meta-balena-2.106.3
> ### (2022-11-11)
> 
> * common: kernel-devsrc: fix pseudo abort [Joseph Kogut]
> 
</details>

# v2.106.2
## (2022-11-11)


<details>
<summary> Update layers/meta-balena to 301f76a3232fb25463f89f6382eb0e14189dcc0e [renovate[bot]] </summary>

> ## meta-balena-2.106.2
> ### (2022-11-10)
> 
> * flasher: minor formatting [Joseph Kogut]
> * flasher: fix detection and exclusion of installation media [Joseph Kogut]
> * flasher: properly expand device_pattern globs [Joseph Kogut]
> 
</details>

# v2.106.1
## (2022-11-10)


<details>
<summary> Update layers/meta-balena to bf237c4f76c4026ed3aea2f30edc7c6a484fcef6 [renovate[bot]] </summary>

> ## meta-balena-2.106.1
> ### (2022-11-10)
> 
> * tests: cloud: use cloud ssh to avoid race cond [rcooke-warwick]
> 
</details>

# v2.106.0
## (2022-11-10)


<details>
<summary> Update layers/meta-balena to c5f580c7bd8e7d1391331c1611ab340be68d8d6a [renovate[bot]] </summary>

> ## meta-balena-2.106.0
> ### (2022-11-10)
> 
> * Update balena-os/balena-supervisor to v14.3.0 [renovate[bot]]
> 
</details>

# v2.105.32
## (2022-11-09)


<details>
<summary> Update layers/meta-balena to b6e5de2abcadd369a37891b17494048d6a82b1cc [renovate[bot]] </summary>

> ## meta-balena-2.105.32
> ### (2022-11-09)
> 
> * Enable network access for tasks talking to the signing service [Michal Toman]
> 
</details>

# v2.105.31+rev2
## (2022-11-09)


<details>
<summary> Update contracts to b20827d63cbe7b1168f2b63b3bde216231e1b4ba [renovate[bot]] </summary>

> ## contracts-2.0.28
> ### (2022-11-09)
> 
> * Add node v18.12.1 [Trong Nghia Nguyen]
> 
</details>

# v2.105.31+rev1
## (2022-11-09)


<details>
<summary> Update contracts to 29ecc3f3077027524ea9540cbaa81a12b265d42c [renovate[bot]] </summary>

> ## contracts-2.0.27
> ### (2022-11-07)
> 
> * Add go v1.19.3 and v1.18.8 [Trong Nghia Nguyen]
> * Add node v19.0.1 v16.18.1 and v14.21.1 [Trong Nghia Nguyen]
> 
</details>

# v2.105.31
## (2022-11-09)


<details>
<summary> Update layers/meta-balena to 072a02ba1b9b2f5cb4f1a520c7d321e17dca1eb5 [renovate[bot]] </summary>

> ## meta-balena-2.105.31
> ### (2022-11-08)
> 
> * Add meta-balena-esr workflow [Alex Gonzalez]
> 
</details>

# v2.105.30
## (2022-11-08)


<details>
<summary> Update layers/meta-balena to 0d399dcb9ac7ece013f76a119e8643228eb114b7 [renovate[bot]] </summary>

> ## meta-balena-2.105.30
> ### (2022-11-08)
> 
> * tests: os: ensure by-state links are created [Joseph Kogut]
> 
> ## meta-balena-2.105.29
> ### (2022-11-07)
> 
> * prepare-openvpn: do not use cached configuration [Alex Gonzalez]
> 
</details>

# v2.105.28+rev1
## (2022-11-07)

* Update contracts to c33f181741d3a3a8eb1d99fe24360c38114db96f [renovate[bot]]

# v2.105.28
## (2022-11-06)


<details>
<summary> Update layers/meta-balena to 496bde37adf3bdabcf3baa3c3dbbaba8ed2c59e1 [renovate[bot]] </summary>

> ## meta-balena-2.105.28
> ### (2022-11-06)
> 
> * patch: Delete conf.js for test suites [Vipul Gupta (@vipulgupta2048)]
> 
</details>

# v2.105.27
## (2022-11-04)


<details>
<summary> Update layers/meta-balena to 4f26a52c25bd3b246cc623b271873891da2fd737 [renovate[bot]] </summary>

> ## meta-balena-2.105.27
> ### (2022-11-04)
> 
> * wpa-supplicant: Sync with v2.10 from upstream [Zahari Petkov]
> 
</details>

# v2.105.26
## (2022-11-04)


<details>
<summary> Update layers/meta-balena to 397943469235f9eb67a55ce5c98e01e8afbc641e [renovate[bot]] </summary>

> ## meta-balena-2.105.26
> ### (2022-11-04)
> 
> * patch: Skip HUP suite if no releases found [Vipul Gupta (@vipulgupta2048)]
> 
</details>

# v2.105.25
## (2022-11-04)


<details>
<summary> Update layers/meta-balena to 81cdced65f90570af857c9cf012775558003c1c5 [renovate[bot]] </summary>

> ## meta-balena-2.105.25
> ### (2022-11-04)
> 
> * Update balena-os/balena-supervisor to v14.2.20 [renovate[bot]]
> 
</details>

# v2.105.24
## (2022-11-03)


<details>
<summary> Update layers/meta-balena to 912634a99a4ae09855c2c517c620ec16f843dd95 [renovate[bot]] </summary>

> ## meta-balena-2.105.24
> ### (2022-11-03)
> 
> * Update balena-os/balena-supervisor to v14.2.18 [renovate[bot]]
> 
</details>

# v2.105.23
## (2022-11-01)


<details>
<summary> Update layers/meta-balena to a2b5edbaf873fce9fb0dbe6564aaa590af9849dc [renovate[bot]] </summary>

> ## meta-balena-2.105.23
> ### (2022-11-01)
> 
> * tests: hup: handle exception when unwrapping non-flasher image [Joseph Kogut]
> 
</details>

# v2.105.22
## (2022-10-31)


<details>
<summary> Update layers/meta-balena to 24deb5194be2c96b14f8bd4343555bf855f6ca06 [renovate[bot]] </summary>

> ## meta-balena-2.105.22
> ### (2022-11-01)
> 
> * Update Docs Link Updated the link in the docs to the device-type listings (on hub as SOT) [Ryan H]
> 
</details>

# v2.105.21+rev1
## (2022-10-31)


<details>
<summary> Update contracts to edff7336f8c7fd074aed1fd087a595ee2ca05651 [renovate[bot]] </summary>

> ## contracts-2.0.26
> ### (2022-11-01)
> 
> * Add Python v3.11.0 v3.10.8 v3.9.15 v3.8.15 and v3.7.15 [Trong Nghia Nguyen]
> 
> ## contracts-2.0.25
> ### (2022-10-27)
> 
> * Fix incorrect partials in device type contracts [Micah Halter]
> 
> ## contracts-2.0.24
> ### (2022-10-27)
> 
> * Add node v18.12.0 [Trong Nghia Nguyen]
> 
</details>

# v2.105.21
## (2022-10-27)


<details>
<summary> Update layers/meta-balena to 2e9f69012d326b5925304c9d25427c5cc46dfbd4 [renovate[bot]] </summary>

> ## meta-balena-2.105.21
> ### (2022-10-27)
> 
> * openssh: allow RSA signatures with SHA1 algorithms [Alex Gonzalez]
> 
</details>

# v2.105.20
## (2022-10-26)


<details>
<summary> Update layers/meta-balena to 6fe97ecc67ba4dc83fb5ff21d801e9062d4179d4 [renovate[bot]] </summary>

> ## meta-balena-2.105.20
> ### (2022-10-26)
> 
> * meta-resin-sumo: libical: Fix build QA error [Alex Gonzalez]
> 
</details>

# v2.105.19
## (2022-10-26)


<details>
<summary> Update layers/meta-balena to 38055be70d9113801797d97ddeac00012c5b151c [renovate[bot]] </summary>

> ## meta-balena-2.105.19
> ### (2022-10-26)
> 
> * meta-resin-sumo: keep tpm2-tools in 5.0 [Alex Gonzalez]
> 
> ## meta-balena-2.105.18
> ### (2022-10-25)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to f83df7d [renovate[bot]] </summary>
> 
>> ### leviathan-2.10.0
>> #### (2022-10-25)
>> 
>> * minor: Add @balena/leviathan-test-helpers package [Vipul Gupta (@vipulgupta2048)]
>> 
> </details>
> 
> 
</details>

# v2.105.17+rev3
## (2022-10-25)


<details>
<summary> Update contracts to c311e6f8a9832587b3bb687b22a92574b790c688 [renovate[bot]] </summary>

> ## contracts-2.0.23
> ### (2022-10-25)
> 
> * sw.os+hw.device-type: Add distro-config.tpl for jetson-agx-orin-devkit [Alexandru Costache]
> 
</details>

# v2.105.17+rev2
## (2022-10-24)


<details>
<summary> Update balena-yocto-scripts to 7c5b9c44fbd4039c3387c8b74e8efae8fa9f37d6 [renovate[bot]] </summary>

> ## balena-yocto-scripts-1.19.13
> ### (2022-10-21)
> 
> * jenkins_build: Only deploy AMI after deploying a final release [Alex Gonzalez]
> 
</details>

# v2.105.17+rev1
## (2022-10-24)


<details>
<summary> Update contracts to 67fb73772ae7ecfb93109e9e42e8b33465a61ec0 [renovate[bot]] </summary>

> ## contracts-2.0.22
> ### (2022-10-24)
> 
> * hw+device-type: Add jetson-agx-orin-devkit device type [Alexandru Costache]
> 
</details>

# v2.105.17
## (2022-10-21)


<details>
<summary> Update layers/meta-balena to 5c78a62b8409752294e244bd1ecc111b4b969da7 [renovate[bot]] </summary>

> ## meta-balena-2.105.17
> ### (2022-10-21)
> 
> * tests: hup: reduce num. flashes and  hostapp sends [rcooke-warwick]
> 
</details>

# v2.105.16+rev1
## (2022-10-20)


<details>
<summary> Update contracts to 38de093f2a5afdb1948b295ba11a18b6ebe626e9 [renovate[bot]] </summary>

> ## contracts-2.0.21
> ### (2022-10-20)
> 
> * Add node v19.0.0 [Trong Nghia Nguyen]
> 
</details>

# v2.105.16
## (2022-10-20)


<details>
<summary> Update layers/meta-balena to 0c378990ffead64c9141e82f76299914c416436d [renovate[bot]] </summary>

> ## meta-balena-2.105.16
> ### (2022-10-20)
> 
> * common: openvpn: remove resin.conf [Joseph Kogut]
> 
</details>

# v2.105.15
## (2022-10-19)


<details>
<summary> Update layers/meta-balena to ec41853b477877d096d2eff72db59668f58b684b [renovate[bot]] </summary>

> ## meta-balena-2.105.15
> ### (2022-10-19)
> 
> * Revert "chrony: update to version 4.1 to match kirkstone's version" [Alex Gonzalez]
> 
</details>

# v2.105.14
## (2022-10-18)


<details>
<summary> Update layers/meta-balena to 85705947f289798d36c534aae5dc3582627e2a99 [renovate[bot]] </summary>

> ## meta-balena-2.105.14
> ### (2022-10-18)
> 
> * patch: Enable RPi3-64 for Device tree tests [Vipul Gupta (@vipulgupta2048)]
> 
</details>

# v2.105.13
## (2022-10-18)


<details>
<summary> Update layers/meta-balena to b33d3aa9a17eabe4f88f6086fce008862ad43ba1 [renovate[bot]] </summary>

> ## meta-balena-2.105.13
> ### (2022-10-18)
> 
> * ntp: Remove race condition from directory creation [Alex Gonzalez]
> 
</details>

# v2.105.12
## (2022-10-17)


<details>
<summary> Update layers/meta-balena to bfb53e361ce9a3205e9c468f7c83b614acb3c52e [renovate[bot]] </summary>

> ## meta-balena-2.105.12
> ### (2022-10-17)
> 
> * classes: kernel-balena: Allow aufs patching to use network [Alex Gonzalez]
> 
</details>

# v2.105.11+rev2
## (2022-10-15)

* Update build and deploy workflow to v0.0.12 [Alex Gonzalez]

# v2.105.11+rev1
## (2022-10-15)


<details>
<summary> Update contracts to f9e017074a7d7e26f5b56642fa86d2533f349f33 [renovate[bot]] </summary>

> ## contracts-2.0.20
> ### (2022-10-14)
> 
> * Add Golang v1.19.2 and v1.18.7 [Trong Nghia Nguyen]
> * Add node v18.11.0 and v16.18.0 [Trong Nghia Nguyen]
> 
</details>

# v2.105.11
## (2022-10-15)


<details>
<summary> Update layers/meta-balena to 433b72275aa61da736904aa3f55c7b987824d523 [renovate[bot]] </summary>

> ## meta-balena-2.105.11
> ### (2022-10-13)
> 
> * Update balena-os/balena-supervisor to v14.2.10 [renovate[bot]]
> 
> ## meta-balena-2.105.10
> ### (2022-10-12)
> 
> * classes: kernel-balena: improve aufs branch selection [Alex Gonzalez]
> 
</details>

# v2.105.9+rev2
## (2022-10-14)

* Switch from balenaCI to flowzone [Alex Gonzalez]

# v2.105.9+rev1
## (2022-10-12)


<details>
<summary> Update contracts to 6f3ccc3060c64de164d6fd60a0bc65b2d8ceb5d3 [renovate[bot]] </summary>

> ## contracts-2.0.19
> ### (2022-10-05)
> 
> * Update dotnet 6.0 and 3.1 to latest version [Trong Nghia Nguyen]
> * Add Python v3.10.7 v3.9.14 v3.8.14 and v3.7.14 [Trong Nghia Nguyen]
> 
> ## contracts-2.0.18
> ### (2022-10-05)
> 
> * Switch from balenaCI to flowzone [Trong Nghia Nguyen]
> 
</details>

# v2.105.9
## (2022-10-11)


<details>
<summary> Update layers/meta-balena to cf01401eff54d9fd3a4fd1247f4d3f059619c2d3 [renovate[bot]] </summary>

> ## meta-balena-2.105.9
> ### (2022-10-11)
> 
> * meta-balena-rust: Fix ABI for arm [Alex Gonzalez]
> 
</details>

# v2.105.8
## (2022-10-11)


<details>
<summary> Update layers/meta-balena to ee77950ea892204938cf5681c9550952b423ede0 [renovate[bot]] </summary>

> ## meta-balena-2.105.8
> ### (2022-10-11)
> 
> * meta-balena-thud: Enable GOCACHE [Alex Gonzalez]
> 
> ## meta-balena-2.105.7
> ### (2022-10-06)
> 
> * Update balena-os/balena-supervisor to v14.2.8 [renovate[bot]]
> 
> ## meta-balena-2.105.6
> ### (2022-10-06)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to 4482393 [renovate[bot]] </summary>
> 
>> ### leviathan-2.9.9
>> #### (2022-10-05)
>> 
>> * Revert "worker: Pin to stable release 2.5.10 prior to md support" [Kyle Harding]
>> 
>> ### leviathan-2.9.8
>> #### (2022-10-05)
>> 
>> * Switch to Flowzone for CI [Kyle Harding]
>> * Remove leftover balena.yml file [Kyle Harding]
>> 
> </details>
> 
> 
> ## meta-balena-2.105.5
> ### (2022-10-01)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to a2079bd [renovate[bot]] </summary>
> 
>> ### leviathan-2.9.7
>> #### (Invalid date)
>> 
>> * Splie interface name into config [rcooke-warwick]
>> * core: Specify wireless interface name for the 243390 device type [Alexandru Costache]
>> 
> </details>
> 
> 
> ## meta-balena-2.105.4
> ### (2022-10-01)
> 
> * Update balena-os/balena-supervisor to v14.2.7 [renovate[bot]]
> 
> ## meta-balena-2.105.3
> ### (Invalid date)
> 
> * flowzone: Run also for pull requests into ESR branches [Alex Gonzalez]
> * Switch from balenaCI to flowzone [Pagan Gazzard]
> 
</details>

# v2.105.2+rev1
## (2022-09-27)


<details>
<summary> Update contracts to 766eb7591fe2b2f2cbc36af68d58627057f38193 [renovate[bot]] </summary>

> ## contracts-2.0.17
> ### (2022-09-27)
> 
> * Add node v18.9.1, v16.17.1 and v14.20.1 [Trong Nghia Nguyen]
> * Add Golang v1.19.1 and v1.18.6 [Trong Nghia Nguyen]
> 
</details>

# v2.105.2
## (2022-09-22)


<details>
<summary> Update layers/meta-balena to d17b08668a56aa67c7b55594c3c910e66fbd4baf [renovate[bot]] </summary>

> ## meta-balena-2.105.2
> ### (2022-09-22)
> 
> * contributing-device-support.md: Clarify repo set-up in balenaOS org [Florin Sarbu]
> 
</details>

# v2.105.1
## (2022-09-21)


<details>
<summary> Update layers/meta-balena to ce91b3f1807f5dc1d1ee861a164957215757d8a0 [renovate[bot]] </summary>

> ## meta-balena-2.105.1
> ### (2022-09-21)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to 15d608b [renovate[bot]] </summary>
> 
>> ### leviathan-2.9.6
>> #### (2022-09-21)
>> 
>> * core/contracts: bump contracts to v2.0.16 [Alexandru Costache]
>> 
> </details>
> 
> 
</details>

# v2.105.0
## (2022-09-21)


<details>
<summary> Update contracts to f2ace726406411ac4202d114ec8264a1a2c7af97 [renovate[bot]] </summary>

> ## contracts-2.0.16
> ### (2022-09-21)
> 
> * hw.device-type: Remove led for RockPro64 [Alexandru Costache]
> 
</details>

* Update layers/meta-balena to d767299d6d830f3c310a691ca8b5fc543a4215e5 [renovate[bot]]

# v2.104.1
## (2022-09-20)


<details>
<summary> Update layers/meta-balena to 226aa0d60a8e7d69ae2b17c5bc3efff1559a6bda [renovate[bot]] </summary>

> ## meta-balena-2.104.1
> ### (2022-09-20)
> 
> * balena: remove kernel-module-nf-nat-native dependency for host build [Alexandru Costache]
> 
</details>


<details>
<summary> Update layers/meta-balena to 09435bc8b96abc8fcd245eaa5e1ead0fe626cae5 [renovate[bot]] </summary>

> ## meta-balena-2.104.1
> ### (2022-09-20)
> 
> * balena: remove kernel-module-nf-nat-native dependency for host build [Alexandru Costache]
> 
</details>

# v2.103.5
## (2022-09-19)


<details>
<summary> Update layers/meta-balena to 33e0b4caf72baa5b416574b91ddcf603eded1188 [renovate[bot]] </summary>

> ## meta-balena-2.103.5
> ### (2022-09-19)
> 
> * Update balena-os/balena-supervisor to v14.0.25 [renovate[bot]]
> 
</details>


<details>
<summary> Update layers/meta-balena to 0dc61866fa0970f997f60955ab1a4c3dd48783a5 [renovate[bot]] </summary>

> ## meta-balena-2.103.5
> ### (2022-09-19)
> 
> * Update balena-os/balena-supervisor to v14.0.25 [renovate[bot]]
> 
</details>

# v2.103.3
## (2022-09-17)


<details>
<summary> Update layers/meta-balena to a17b3251407b74e424a6bcf7850783975c366cf0 [renovate[bot]] </summary>

> ## meta-balena-2.103.3
> ### (2022-09-15)
> 
> * resin-init-flasher: skip array members not matching a named array [Joseph Kogut]
> * resin-init-flasher: support pattern matching of devices [Joseph Kogut]
> 
> ## meta-balena-2.103.2
> ### (2022-09-14)
> 
> * mobynit: allow compile task to use network [Joseph Kogut]
> 
</details>

# v2.103.1+rev1
## (2022-09-14)


<details>
<summary> Update contracts to 7ea918011dc38f509a7ae3bce30c3391bc839dd9 [renovate[bot]] </summary>

> ## contracts-2.0.15
> ### (2022-09-14)
> 
> * hw.device-type: Set LED to false for rockpi-4b [Alexandru Costache]
> 
</details>

# v2.103.1
## (2022-09-14)


<details>
<summary> Update layers/meta-balena to 2f207a3dbc3f142d4d1e0b9fdbd6136bcfb40dac [renovate[bot]] </summary>

> ## meta-balena-2.103.1
> ### (2022-09-13)
> 
> * tests: os: only do hdmi test if has capture device [rcooke-warwick]
> 
> ## meta-balena-2.103.0
> ### (2022-09-12)
> 
> * README: Add kirkstone support [Alex Gonzalez]
> * layer.conf: Add kirkstone support [Alex Gonzalez]
> * kernel-balena-noimage: Remove kernel-image packages from image [Alex Gonzalez]
> * meta-balena-kirkstone: plymouth: Adapt custom patches [Alex Gonzalez]
> * meta-balena-kirkstone: systemd: Ammend patches to remove fuzziness warning [Alex Gonzalez]
> * meta-balena-kirkstone: replace honister with kirkstone [Alex Gonzalez]
> * meta-balena-kirkstone: use upstream kernel-devsrc recipe [Alex Gonzalez]
> * meta-balena-kirkstone: use the procps recipe from upstream [Alex Gonzalez]
> * meta-balena-kirkstone: Add kirkstone integration layer [Alex Gonzalez]
> * classes: image-balena: Fix journal blocks calculation [Alex Gonzalez]
> * packagegroup-resin: Move libnss-ato out of packagegroup to avoid build error [Alex Gonzalez]
> * openvpn: update to version 2.5.6 [Alex Gonzalez]
> * balena-supervisor: Allow network use in install task [Alex Gonzalez]
> * docker-disk: Allow compile task to use network [Alex Gonzalez]
> * chrony: update to version 4.1 to match kirkstone's version [Alex Gonzalez]
> * os-config: Adapt to kirkstone [Alex Gonzalez]
> * healthdog: Adapt to kirkstone [Alex Gonzalez]
> * compatibility: Do not update tpm2-tss below Dunfell [Alex Gonzalez]
> * tpm2-tss: update to kirkstone [Alex Gonzalez]
> * tpm2-tools: update to kirkstone [Alex Gonzalez]
> * tpm2-abrmd: update to kirkstone [Alex Gonzalez]
> * meta-balena-common: Assure all recipes have branch and protocol in SRC_URI [Alex Gonzalez]
> * bluez5: update to 5.64 [Alex Gonzalez]
> * efi-tools: Replace SSTATE_DUPWHITELIST with SSTATE_ALLOW_OVERLAP_FILES [Alex Gonzalez]
> 
</details>

# v2.102.6
## (2022-09-08)


<details>
<summary> Update layers/meta-balena to 6e63144eb5d665dc51958e0aa791256c48cc0522 [renovate[bot]] </summary>

> ## meta-balena-2.102.6
> ### (2022-09-07)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to 7fe3c5f [renovate[bot]] </summary>
> 
>> ### leviathan-2.8.4
>> #### (2022-09-07)
>> 
>> * core: Copy all files/directories except those in dockerignore [Kyle Harding]
>> * core: Move contracts submodule back to original path [Kyle Harding]
>> 
>> ### leviathan-2.8.3
>> #### (2022-09-07)
>> 
>> * patch: Migrate away from config package [Vipul Gupta (@vipulgupta2048)]
>> 
>> ### leviathan-2.8.2
>> #### (2022-09-06)
>> 
>> * worker: Pin to stable release 2.5.10 prior to md support [Kyle Harding]
>> 
>> ### leviathan-2.8.1
>> #### (2022-09-03)
>> 
>> * patch: Fix contracts name [Vipul Gupta (@vipulgupta2048)]
>> 
>> ### leviathan-2.8.0
>> #### (2022-08-26)
>> 
>> * patch: Accept 429 HTTP codes using config file [Vipul Gupta (@vipulgupta2048)]
>> * minor: Add support for Private Contracts [Vipul Gupta (@vipulgupta2048)]
>> 
>> ### leviathan-2.7.4
>> #### (2022-08-24)
>> 
>> * Fix "Declaration emit" error during `npm run docs` [Leandro Motta Barros]
>> 
> </details>
> 
> 
</details>

# v2.102.5
## (2022-09-06)


<details>
<summary> Update layers/meta-balena to 827a6fc341fc806ff065bbe1940c9a0f046cc373 [renovate[bot]] </summary>

> ## meta-balena-2.102.5
> ### (2022-09-06)
> 
> * patch: Add package-lock.json files for tests [Vipul Gupta (@vipulgupta2048)]
> 
</details>

# v2.102.4+rev1
## (2022-09-06)


<details>
<summary> Update contracts to e7520599758cae5f507d7189a3415e95e2ff0309 [renovate[bot]] </summary>

> ## contracts-2.0.14
> ### (2022-09-06)
> 
> * Add node v18.8.0 [Trong Nghia Nguyen]
> 
</details>

# v2.102.4
## (2022-09-03)


<details>
<summary> Update layers/meta-balena to 608994976c4d5d4f1f4558245f6abc375ac0c0c7 [renovate[bot]] </summary>

> ## meta-balena-2.102.4
> ### (Invalid date)
> 
> * udev: run resin-update-state after md assemble [Joseph Kogut]
> * resin_update_state_probe: do not skip md devices [Joseph Kogut]
> 
</details>

# v2.102.3
## (2022-08-30)


<details>
<summary> Update layers/meta-balena to a24e52592b2fbc1c60e6a6fc39c61470219f61b1 [renovate[bot]] </summary>

> ## meta-balena-2.102.3
> ### (Invalid date)
> 
> * renovate: Restore default commit body [Kyle Harding]
> 
> ## meta-balena-2.102.2
> ### (2022-08-29)
> 
> * Renovate: Fix package rules for balena supervisor [Kyle Harding]
> 
> ## meta-balena-2.102.1
> ### (2022-08-29)
> 
> * meta-balena-thud: initramfs: Fix building with latest meta-balena [Alex Gonzalez]
> 
> ## meta-balena-2.102.0
> ### (2022-08-25)
> 
> * meta-balena-common: distro: Add rust preferred versions [Alex Gonzalez]
> * meta-balena-common: os-config: Update to v1.2.11 [Alex Gonzalez]
> * meta-balena-integration: Replace parallel_make_argument() [Alex Gonzalez]
> * meta-balena-integration: Update cmake for versions below Zeus [Alex Gonzalez]
> * meta-balena-rust: Add condition check for parallel_make_argument() use [Alex Gonzalez]
> * meta-balena-rust: Provide crate fetcher for Yocto versions without it [Alex Gonzalez]
> * meta-balena-rust: Modify to use without oe.rust.arch_to_rust_arch() support [Alex Gonzalez]
> * meta-balena-rust: Add rust recipes to keep the rust version a distribution config [Alex Gonzalez]
> * meta-balena-rust: Add compatibility layer [Alex Gonzalez]
> 
</details>

# v2.101.11+rev1
## (2022-08-26)


<details>
<summary> Update contracts to 3bd4b2097a2796afc9a56a580e555982aad4f10b [renovate[bot]] </summary>

> ## contracts-2.0.13
> ### (2022-08-26)
> 
> * imx8mm-var-som: Add device type [Alexandru Costache]
> 
</details>

# v2.101.11
## (2022-08-25)


<details>
<summary> Update layers/meta-balena to 094cc1766365844e9e4dcf46f4f247cad0231715 [renovate[bot]] </summary>

> ## meta-balena-2.101.11
> ### (2022-08-24)
> 
> * renovate: Fix nested changelogs and change-type for SV updates [Kyle Harding]
> 
</details>


<details>
<summary> Update layers/meta-balena to a1084cfc437eb601cbb9f3de7822d916e08351de [renovate[bot]] </summary>

> ## meta-balena-2.101.11
> ### (2022-08-24)
> 
> * renovate: Fix nested changelogs and change-type for SV updates [Kyle Harding]
> 
</details>

# v2.101.9
## (2022-08-23)


<details>
<summary> Update layers/meta-balena to f2de8e3d438671ac740bfa2119ab881afc5d2101 [renovate[bot]] </summary>

> ## meta-balena-2.101.9
> ### (2022-08-23)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to f7533c1 [renovate[bot]] </summary>
> 
>> ### leviathan-2.7.3
>> #### (2022-08-16)
>> 
>> * compose: qemu: enable loopback and metadata devices [Joseph Kogut]
>> 
> </details>
> 
> 
</details>


<details>
<summary> Update layers/meta-balena to ab80d0fbfbd28e10b7aa14739203a680d37815bd [renovate[bot]] </summary>

> ## meta-balena-2.101.9
> ### (2022-08-23)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to f7533c1 [renovate[bot]] </summary>
> 
>> ### leviathan-2.7.3
>> #### (2022-08-16)
>> 
>> * compose: qemu: enable loopback and metadata devices [Joseph Kogut]
>> 
> </details>
> 
> 
</details>

# v2.101.7+rev1
## (2022-08-19)


<details>
<summary> Update contracts to 39a79c43f1b8ab4426d7a9c1cdeb9a9514101061 [renovate[bot]] </summary>

> ## contracts-2.0.12
> ### (2022-08-19)
> 
> * Add golang v1.19 and v1.18.5 [Trong Nghia Nguyen]
> * Add node v16.17.0 [Trong Nghia Nguyen]
> 
</details>

# v2.101.7
## (2022-08-18)

* Modify layer ordering [Alex Gonzalez]
* Update layers/meta-balena to 61b53fbb8b667de54707cc6aa94fd79674958856 [renovate[bot]]

# v2.101.6
## (2022-08-16)


<details>
<summary> Update layers/meta-balena to 7dfa6d2abc3795d47a8a6cdb30bc540ee110e7ee [renovate[bot]] </summary>

> ## meta-balena-2.101.6
> ### (2022-08-15)
> 
> * tests/cloud: fix ssh prod test for physical duts [rcooke-warwick]
> 
</details>

# v2.101.5
## (2022-08-15)


<details>
<summary> Update layers/meta-balena to 771593f49920c4ae0ef101d2328f03f033449a9e [renovate[bot]] </summary>

> ## meta-balena-2.101.5
> ### (2022-08-12)
> 
> * meta-balena-rust: Link to meta-rust [Alex Gonzalez]
> 
</details>

# v2.101.4+rev2
## (2022-08-11)


<details>
<summary> Update contracts to 91807ae538dccedb69877eed28ae6752287e2f21 [renovate[bot]] </summary>

> ## contracts-2.0.11
> ### (2022-08-10)
> 
> * generic-amd64: update logo to be vendor agnostic [Joseph Kogut]
> 
</details>

# v2.101.4+rev1
## (2022-08-11)


<details>
<summary> Update balena-yocto-scripts to 99807501efffc8c5034c88361049650a02511a78 [renovate[bot]] </summary>

> ## balena-yocto-scripts-1.19.12
> ### (2022-08-08)
> 
> * barys: Add balena-rust to syntax conversion step [Alex Gonzalez]
> 
</details>

# v2.101.4
## (2022-08-11)


<details>
<summary> Update layers/meta-balena to 9d73da96e59bcbef4b626a090436caefb2834584 [renovate[bot]] </summary>

> ## meta-balena-2.101.4
> ### (2022-08-08)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to c2c68d2 [renovate[bot]] </summary>
> 
>> ### leviathan-2.7.2
>> #### (2022-08-05)
>> 
>> * exit with failure if suite doesn't start [rcooke-warwick]
>> 
>> ### leviathan-2.7.1
>> #### (2022-08-02)
>> 
>> * Regenerate docs [Leandro Motta Barros]
>> * Document proper worker config for QEMU workers [Leandro Motta Barros]
>> * Fix a couple of typos in the docs [Leandro Motta Barros]
>> 
>> ### leviathan-2.7.0
>> #### (2022-07-26)
>> 
>> * minor: Add Unstable tests debug feature [Vipul Gupta (@vipulgupta2048)]
>> 
> </details>
> 
> 
</details>

# v2.101.3+rev1
## (2022-08-10)


<details>
<summary> Update contracts to d82f4b2d9f182bab4f5b39b4906e0ca17154fa04 [renovate[bot]] </summary>

> ## contracts-2.0.10
> ### (2022-08-10)
> 
> * generic-amd64: disable private [Joseph Kogut]
> 
</details>

# v2.101.3
## (2022-08-06)


<details>
<summary> Update layers/meta-balena to afcbee0c5dad04f02ba2a3ecb5d6d7db21f7ebe4 [renovate[bot]] </summary>

> ## meta-balena-2.101.3
> ### (2022-08-05)
> 
> * Update balena-io/balena-supervisor to v14.0.13 [renovate[bot]]
> 
</details>

# v2.101.2
## (2022-08-05)


<details>
<summary> Update layers/meta-balena to 3c505918b2cbf72f607a3ccc65cc3853fd3a636e [renovate[bot]] </summary>

> ## meta-balena-2.101.2
> ### (2022-08-05)
> 
> * DRY the HUP smoke tests [Leandro Motta Barros]
> * Check volume contents over HUPs [Leandro Motta Barros]
> 
</details>

# v2.101.1+rev1
## (2022-08-05)


<details>
<summary> Update contracts to 3d133659481f38ee1bba63d3835a231c70c11eec [renovate[bot]] </summary>

> ## contracts-2.0.9
> ### (2022-08-04)
> 
> * generic-amd64: match genericx86-64-ext connectivity [Joseph Kogut]
> * generic-amd64: update name to include GPT qualifier [Joseph Kogut]
> * genericx86-64-ext: update name to include MBR qualifier [Joseph Kogut]
> 
</details>

# v2.101.1
## (2022-08-03)


<details>
<summary> Update layers/meta-balena to 7a62296718a363abd393107933f30e611ec27d1e [renovate[bot]] </summary>

> ## meta-balena-2.101.1
> ### (2022-08-01)
> 
> * os-config: Update os-config from v1.2.1 to v1.2.10 [Zahari Petkov]
> 
</details>

# v2.101.0+rev3
## (2022-08-03)

* Remove final argument from build and deploy workflow [Alex Gonzalez]
* Update build and deploy workflow to v0.0.9 [Alex Gonzalez]

# v2.101.0+rev2
## (2022-08-03)


<details>
<summary> Update contracts to b48eaf24e3b0cf67116e4adbe1a12d349825fda5 [renovate[bot]] </summary>

> ## contracts-2.0.8
> ### (2022-08-03)
> 
> * Update dotnet contract to latest v6.x and v3.x [Trong Nghia Nguyen]
> * Add node v18.7.0 [Trong Nghia Nguyen]
> 
</details>

# v2.101.0+rev1
## (2022-08-02)


<details>
<summary> Update balena-yocto-scripts to 09e4514953fed499a69c224b47969fd2c3fb7ab8 [renovate[bot]] </summary>

> ## balena-yocto-scripts-1.19.11
> ### (2022-07-25)
> 
> * balena-api: On hostapp creation, set class to app [Alex Gonzalez]
> 
</details>

# v2.101.0
## (2022-07-30)


<details>
<summary> Update layers/meta-balena to c233b4107fc25b08e963e2419b40263409d2de9e [renovate[bot]] </summary>

> ## meta-balena-2.101.0
> ### (2022-07-29)
> 
> * resin-device-register: Use fatrw to access the boot partition [Alex Gonzalez]
> * hostapp-update-hooks: Use fatrw to access the boot partition [Alex Gonzalez]
> * balena-unique-key: Use fatrw to access the boot partition [Alex Gonzalez]
> * balena-rollback: Use fatrw if available [Alex Gonzalez]
> * update-hostapp-extensions: Use fatrw if available [Alex Gonzalez]
> * balena-config-vars: Provide FAT safe filesystem access alternatives [Alex Gonzalez]
> * fatrw: Add recipe [Alex Gonzalez]
> 
> ## meta-balena-2.100.11
> ### (2022-07-25)
> 
> * test: os: chrony: Double the wait for time skew test [Kyle Harding]
> * os: tests: chrony: Wrap disable/enable NTP in test conditions [Kyle Harding]
> * tests: os: Add helper to write or remove properties in config.json [Kyle Harding]
> 
> ## meta-balena-2.100.10
> ### (2022-07-24)
> 
> * tests: cloud: preload: fix no-return-await [Joseph Kogut]
> * tests: cloud: preload: reduce waitUntil interval [Joseph Kogut]
> * tests: cloud: multicontainer: reduce waitUntil interval [Joseph Kogut]
> 
> ## meta-balena-2.100.9
> ### (2022-07-22)
> 
> * tests: os: engine-socket - wait for response [rcooke-warwick]
> 
> ## meta-balena-2.100.8
> ### (2022-07-21)
> 
> * tests/os: Add 243390 unmanged Wifi HATs tests from testLodge [Alexandru Costache]
> 
> ## meta-balena-2.100.7
> ### (2022-07-21)
> 
> * tests: hup: Clear inactive storage partition before HUP [Kyle Harding]
> * tests: hup: Add root partition tests [Kyle Harding]
> * tests: hup: Replace custom steps with tests and verify exit code [Kyle Harding]
> * tests: hup: Wait for rollback files to be removed or created [Kyle Harding]
> 
> ## meta-balena-2.100.6
> ### (2022-07-21)
> 
> * balena-config-vars: Do not use cache in flasher images [Alex Gonzalez]
> 
> ## meta-balena-2.100.5
> ### (2022-07-21)
> 
> * Update balena-io/balena-supervisor to v14.0.12 [renovate[bot]]
> 
> ## meta-balena-2.100.4
> ### (2022-07-20)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to d3c6489 [renovate[bot]] </summary>
> 
>> ### leviathan-2.6.8
>> #### (2022-07-20)
>> 
>> * core: Reduce logging in failed SSH attempts [Kyle Harding]
>> 
>> ### leviathan-2.6.7
>> #### (2022-07-18)
>> 
>> * Revert "patch: Increase timeout for worker connections" [Kyle Harding]
>> * core: Update node-tap to 14.10.8 [Kyle Harding]
>> 
> </details>
> 
> 
> ## meta-balena-2.100.3
> ### (2022-07-20)
> 
> * tests: ssh-auth: Rework to prevent race conditions [Kyle Harding]
> 
> ## meta-balena-2.100.2
> ### (2022-07-15)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to c2755a1 [renovate[bot]] </summary>
> 
>> ### leviathan-2.6.6
>> #### (2022-07-15)
>> 
>> * core: worker: add retryOptions to executeCommand methods [Joseph Kogut]
>> 
> </details>
> 
> 
> ## meta-balena-2.100.1
> ### (2022-07-15)
> 
> * tests: cloud: fix production mode ssh test [Joseph Kogut]
> 
> ## meta-balena-2.100.0
> ### (2022-07-14)
> 
> * docs: Add configuration overview [Alex Gonzalez]
> * Create empty configuration units [Alex Gonzalez]
> * Make configuration units storage path a distro setting [Alex Gonzalez]
> * balena-configurable: Generate initial unit configuration file [Alex Gonzalez]
> * balena-units-conf: Add script to generate configuration units [Alex Gonzalez]
> * balena-units-conf: Rename configuration directory [Alex Gonzalez]
> * balena-units-conf: Process static configuration unit files at build time [Alex Gonzalez]
> * os-helpers-config: Extract functions from os-config-json to helper file [Alex Gonzalez]
> * os-helpers: Rename os-helpers-devmode to os-helpers-config [Alex Gonzalez]
> * balena-config-vars: Split static defaults into a different file [Alex Gonzalez]
> * os-config-json: Log configuration changes [Alex Gonzalez]
> * os-config-json: Recreate environment cache file [Alex Gonzalez]
> * balena-config-vars: Cache environment in memory file [Alex Gonzalez]
> 
> ## meta-balena-2.99.30
> ### (2022-07-14)
> 
> * Update backport for current being 2.98.x [Alex Gonzalez]
> 
> ## meta-balena-2.99.29
> ### (2022-07-14)
> 
> * Update balena-io/balena-supervisor to v14.0.10 [renovate[bot]]
> 
> ## meta-balena-2.99.28
> ### (2022-07-13)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to d57299a [renovate[bot]] </summary>
> 
>> ### leviathan-2.6.5
>> #### (2022-07-12)
>> 
>> * core: Reduce the interval for sdk.executeCommandInHostOS [Kyle Harding]
>> * Revert "reduce ssh retries" [Kyle Harding]
>> 
>> ### leviathan-2.6.4
>> #### (2022-07-07)
>> 
>> * remove parallel suites across multiple workers [rcooke-warwick]
>> 
>> ### leviathan-2.6.3
>> #### (2022-07-06)
>> 
>> * reduce ssh retries [rcooke-warwick]
>> 
>> ### leviathan-2.6.2
>> #### (2022-07-04)
>> 
>> * Makefile: Fix unique container names when running on Jenkins [Kyle Harding]
>> * Makefile: Ignore failures when cleaning up [Kyle Harding]
>> 
>> ### leviathan-2.6.1
>> #### (2022-07-01)
>> 
>> * patch: Remove testing step of purging old volumes [Kyle Harding]
>> * patch: Increase timeout for worker connections [Kyle Harding]
>> 
>> ### leviathan-2.6.0
>> #### (Invalid date)
>> 
>> * minor: Improve e2e serial test for Leviathan v2 [Vipul Gupta (@vipulgupta2048)]
>> 
>> ### leviathan-2.5.7
>> #### (Invalid date)
>> 
>> * patch: Limit e2e execution time to 2 hours [Kyle Harding]
>> 
>> ### leviathan-2.5.6
>> #### (Invalid date)
>> 
>> * patch: Use ubuntu-latest GH runners for e2e [Kyle Harding]
>> 
> </details>
> 
> 
> ## meta-balena-2.99.27
> ### (Invalid date)
> 
> * tests: os: fingerprint: fix errant promise [Joseph Kogut]
> 
</details>

# v2.99.26+rev3
## (2022-07-27)


<details>
<summary> Update contracts to 9db49d2fbb34542f53bf496135c32cccf5df487c [renovate[bot]] </summary>

> ## contracts-2.0.7
> ### (2022-07-19)
> 
> * hw.device-type: fix tdpzu9 device name [Francois]
> 
</details>

# v2.99.26+rev2
## (2022-07-17)


<details>
<summary> Update contracts to 4df6bf241e40b34e4d7051c97ba4f9cf1945c45f [renovate[bot]] </summary>

> ## contracts-2.0.6
> ### (2022-07-17)
> 
> * hw.device-type: Add correct tdpzu9 board [Florin Sarbu]
> 
> ## contracts-2.0.5
> ### (2022-07-14)
> 
> * Add node v18.6.0 [Trong Nghia Nguyen]
> * Add golang v1.8.4 and v1.17.12 [Trong Nghia Nguyen]
> * Add node v18.5.0 v16.16.0 and v14.20.0 [Trong Nghia Nguyen]
> * Remove Debian Stretch as it is EOL [Trong Nghia Nguyen]
> 
</details>

# v2.99.26+rev1
## (2022-07-08)

* Update build and deploy workflow to support ESR tags [Alex Gonzalez]

# v2.99.26
## (2022-06-29)


<details>
<summary> Update layers/meta-balena to 1f79bcbb751f8715c49b207fdf737a2a089aff4c [renovate[bot]] </summary>

> ## meta-balena-2.99.26
> ### (2022-06-29)
> 
> * tests: cloud: Wait for random triggers to be updated [Kyle Harding]
> 
</details>

# v2.99.25
## (2022-06-29)


<details>
<summary> Update balena-yocto-scripts to 5e003d52ac8e118af3cce662362d45f780ade704 [renovate[bot]] </summary>

> ## balena-yocto-scripts-1.19.10
> ### (2022-06-29)
> 
> * balena-deploy: Use balena-img instead of resin-img [Alex Gonzalez]
> * Global rename from dockerhub resin to balena accounts [Alex Gonzalez]
> * automation: Stop deploying images to dockerhub [Alex Gonzalez]
> 
</details>

* Update layers/meta-balena to b76de1e01b5e49196a800340335a3fb2c814b931 [renovate[bot]]

# v2.99.23+rev1
## (2022-06-29)


<details>
<summary> Update balena-yocto-scripts to 29b218350eb1553f0f2c4da2753e9f6722226f41 [renovate[bot]] </summary>

> ## balena-yocto-scripts-1.19.9
> ### (2022-06-28)
> 
> * balena-deploy: pin balena-img to v4.1.2 [Joseph Kogut]
> * balena-deploy: s/resin-img/balena-img [Joseph Kogut]
> 
</details>

# v2.99.23
## (2022-06-28)


<details>
<summary> Update layers/meta-balena to d44b153e75f61c8a18d5149f37412f1fc1e577d9 [renovate[bot]] </summary>

> ## meta-balena-2.99.23
> ### (2022-06-27)
> 
> * Update: update balena-io/balena-supervisor to v14.0.8 [renovate[bot]]
> 
> ## meta-balena-2.99.22
> ### (2022-06-27)
> 
> * balena-supervisor: Replace BOOT_MOUNTPOINT with BALENA_BOOT_MOUNTPOINT [Alex Gonzalez]
> * balena-config-vars: Remove BOOT_MOUNTPOINT from configuration environment [Alex Gonzalez]
> 
> ## meta-balena-2.99.21
> ### (2022-06-27)
> 
> * balena-config-vars: Do not use systemctl to list unit files [Alex Gonzalez]
> 
</details>

# v2.99.20
## (2022-06-25)


<details>
<summary> Update layers/meta-balena to 34e139b190f7aef385f9d7a831fe90e5efee007d [renovate[bot]] </summary>

> ## meta-balena-2.99.20
> ### (2022-06-24)
> 
> * tests: os: make apiKey an optional parameter [Joseph Kogut]
> 
> ## meta-balena-2.99.19
> ### (2022-06-24)
> 
> * tests: os: purge-data: reduce intervals in waitUntil [Joseph Kogut]
> 
</details>

# v2.99.18
## (2022-06-24)


<details>
<summary> Update layers/meta-balena to 16898dbf4b204482fc0018bef3d823599a504c36 [renovate[bot]] </summary>

> ## meta-balena-2.99.18
> ### (2022-06-23)
> 
> * tests: os: config-json: fix race in udevRules test [Joseph Kogut]
> 
> ## meta-balena-2.99.17
> ### (2022-06-22)
> 
> * Update balena-io/balena-supervisor to v14.0.7 [renovate[bot]]
> 
> ## meta-balena-2.99.16
> ### (2022-06-22)
> 
> * tests: os: modem: reduce time taken scanning for modems [Joseph Kogut]
> 
> ## meta-balena-2.99.15
> ### (2022-06-21)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to 9e0ab34 [renovate[bot]] </summary>
> 
>> ### leviathan-2.5.4
>> #### (2022-06-17)
>> 
>> * core: worker: simplify rebootDut [Joseph Kogut]
>> * core: worker: reduce interval in executeCommandInHostOS [Joseph Kogut]
>> 
> </details>
> 
> 
> ## meta-balena-2.99.14
> ### (2022-06-21)
> 
> * tests: os: chrony: simplify error handling [Joseph Kogut]
> * tests: os: chrony: use waitForServiceState [Joseph Kogut]
> * tests: os: chrony: block NTP by disabling DNS resolution [Joseph Kogut]
> 
> ## meta-balena-2.99.13
> ### (2022-06-21)
> 
> * Update balena-io/balena-supervisor to v14 [renovate[bot]]
> 
> ## meta-balena-2.99.12
> ### (2022-06-20)
> 
> * renovate: Add regex manager for balena-supervisor [Kyle Harding]
> 
> ## meta-balena-2.99.11
> ### (2022-06-20)
> 
> * tests: cloud: check preloaded app starts w/o api [rcooke-warwick]
> 
> ## meta-balena-2.99.10
> ### (2022-06-18)
> 
> * Update backport for current being 2.88.x [Alex Gonzalez]
> 
> ## meta-balena-2.99.9
> ### (2022-06-17)
> 
> * hostapp-update-hooks: Rework bootfiles blacklist [Florin Sarbu]
> 
> ## meta-balena-2.99.8
> ### (2022-06-17)
> 
> * base-files: Fix syntax in mdns.allow addition [Alex Gonzalez]
> * efitools: Fix append syntax [Alex Gonzalez]
> 
> ## meta-balena-2.99.7
> ### (2022-06-17)
> 
> * resindataexpander: Move get_part_table_type to os-helpers-fs [Michal Toman]
> 
> ## meta-balena-2.99.6
> ### (2022-06-17)
> 
> * balena-efi.service: Mount if /mnt/boot/EFI is a symlink [Michal Toman]
> 
> ## meta-balena-2.99.5
> ### (2022-06-17)
> 
> * grub-efi: disable shim_lock when in secure boot mode [Michal Toman]
> 
</details>

# v2.99.4+rev1
## (2022-06-23)


<details>
<summary> Update contracts to 98c8c8ef3039bb927ce39f77eed4479f12c77fac [renovate[bot]] </summary>

> ## contracts-2.0.4
> ### (2022-06-21)
> 
> * Add libffi3.4 linked python binaries [Trong Nghia Nguyen]
> 
</details>

# v2.99.4
## (2022-06-17)


<details>
<summary> Update layers/meta-balena to c1656294fcae050821257383049e4b608765516e [Renovate Bot] </summary>

> ## meta-balena-2.99.4
> ### (2022-06-16)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to 6934150 [Renovate Bot] </summary>
> 
>> ### leviathan-2.5.3
>> #### (2022-06-16)
>> 
>> * patch: Fix failFast options [Vipul Gupta (@vipulgupta2048)]
>> 
>> ### leviathan-2.5.2
>> #### (2022-06-15)
>> 
>> * core: worker: handle all local connections the same [Joseph Kogut]
>> 
>> ### leviathan-2.5.1
>> #### (2022-06-14)
>> 
>> * core: catch ssh errors correctly [rcooke-warwick]
>> 
>> ### leviathan-2.5.0
>> #### (2022-06-13)
>> 
>> * make: Disable buildkit and add --pull to worker flags [Kyle Harding]
>> * patch: Replace worker Dockerfile with bh.cr reference [Kyle Harding]
>> * patch: Remove testbot worker compose file [Kyle Harding]
>> * patch: Remove balena-ci workflow for deploying to rigs [Kyle Harding]
>> * Remove worker references from package.json [Kyle Harding]
>> * Remove worker source files [Kyle Harding]
>> 
> </details>
> 
> 
> ## meta-balena-2.99.3
> ### (2022-06-16)
> 
> * tests: os: Run os suite before hup and cloud [Kyle Harding]
> * tests: os: Refactor config-json tests to wait for passing results [Kyle Harding]
> * tests: os: chrony: Avoid conflicts with supervisor firewall [Kyle Harding]
> 
</details>

# v2.99.2
## (2022-06-14)


<details>
<summary> Update layers/meta-balena to ee8110bd257ff145acba793720ea739f14f2429a [Renovate Bot] </summary>

> ## meta-balena-2.99.2
> ### (2022-06-13)
> 
> * tests: os: chrony: reduce retry interval [Joseph Kogut]
> 
</details>

# v2.99.1+rev1
## (2022-06-13)


<details>
<summary> Update contracts to b2bddbdc896e6c628231512b363e5c93d16f5b15 [Renovate Bot] </summary>

> ## contracts-2.0.3
> ### (2022-06-13)
> 
> * Add Python v3.10.5 and v3.9.13 [Trong Nghia Nguyen]
> * Add support for Alpine Linux 3.16 [Trong Nghia Nguyen]
> * Add support for Ubuntu Jammy and Kinetic [Trong Nghia Nguyen]
> 
</details>

# v2.99.1
## (2022-06-11)


<details>
<summary> Update layers/meta-balena to 1aee182ad517f4dd6f24c643bdee1b4db883ffb3 [Renovate Bot] </summary>

> ## meta-balena-2.99.1
> ### (2022-06-11)
> 
> * tests: hup: gzip hostapp before transfer to DUT [rcooke-warwick]
> 
> ## meta-balena-2.99.0
> ### (2022-06-10)
> 
> * chronyd: Add time synchronization healthcheck [Alex Gonzalez]
> 
</details>

# v2.98.45
## (2022-06-10)


<details>
<summary> Update layers/meta-balena to 466c0e3a56da6605f033d8fd1b37c301c96af979 [Renovate Bot] </summary>

> ## meta-balena-2.98.45
> ### (2022-06-09)
> 
> * tests: os: chrony: fix formatting of this.worker [Joseph Kogut]
> * tests: os: chrony: reduce delays and retries [Joseph Kogut]
> 
> ## meta-balena-2.98.44
> ### (2022-06-09)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to ea72650 [Renovate Bot] </summary>
> 
>> ### leviathan-2.4.1
>> #### (2022-06-09)
>> 
>> * catch error in executeCommandInhostOs [rcooke-warwick]
>> 
>> ### leviathan-2.4.0
>> #### (2022-06-07)
>> 
>> * get ssh to work with ed25519 algorithm [rcooke-warwick]
>> 
> </details>
> 
> 
> ## meta-balena-2.98.43
> ### (2022-06-09)
> 
> * tests: cloud: update container names [rcooke-warwick]
> 
</details>

# v2.98.42+rev1
## (2022-06-08)

* Add build and deploy workflow [Alex Gonzalez]

# v2.98.42
## (2022-06-07)


<details>
<summary> Update layers/meta-balena to 3a62a83ec12b05377b46d46bee9661b8b6b4a090 [Renovate Bot] </summary>

> ## meta-balena-2.98.42
> ### (2022-06-05)
> 
> * tests:cloud: Register teardown only when DUT is reachable [Florin Sarbu]
> 
> ## meta-balena-2.98.41
> ### (2022-06-05)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to 4fbc1b8 [Renovate Bot] </summary>
> 
>> ### leviathan-2.3.10
>> #### (2022-06-05)
>> 
>> * worker: Expose additional QEMU runtime args via docker-compose [Kyle Harding]
>> 
> </details>
> 
> 
</details>

* Update contracts to 58bcfbc0b0237177c51db2d7120e61d70e9c415b [Renovate Bot]

# v2.98.40
## (2022-06-04)


<details>
<summary> Update layers/meta-balena to efd8306a7a838b600d2cbf77a4ecfbd30ba9324a [Renovate Bot] </summary>

> ## meta-balena-2.98.40
> ### (2022-06-04)
> 
> * tests: hup: reduce delay between retries [Joseph Kogut]
> 
</details>

# v2.98.39
## (2022-06-04)


<details>
<summary> Update layers/meta-balena to 82f6128a170dd68e671e30278a4f98398f5d1034 [Renovate Bot] </summary>

> ## meta-balena-2.98.39
> ### (2022-06-04)
> 
> * tests: cloud: reduce waitUntil interval [Joseph Kogut]
> 
> ## meta-balena-2.98.38
> ### (2022-06-03)
> 
> * Added all device support options [Ryan H]
> 
</details>

# v2.98.37
## (2022-06-04)


<details>
<summary> Update layers/meta-balena to bef2872f224d9483910a5cc58110f269faf483c7 [Renovate Bot] </summary>

> ## meta-balena-2.98.37
> ### (2022-06-03)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to 8976bdb [Renovate Bot] </summary>
> 
>> ### leviathan-2.3.9
>> #### (2022-06-02)
>> 
>> * core: bump node 12 -> 14 [Joseph Kogut]
>> 
>> ### leviathan-2.3.8
>> #### (2022-06-02)
>> 
>> * core: suiteSubprocess: replace this.state.log w/ console.log [Joseph Kogut]
>> 
> </details>
> 
> 
</details>

# v2.98.36
## (2022-06-03)


<details>
<summary> Update layers/meta-balena to 17a4e839adefeedbe603b9b007800656588c6d77 [Renovate Bot] </summary>

> ## meta-balena-2.98.36
> ### (2022-06-03)
> 
> * os: waitForServiceState: fix missing rejectionFail [Joseph Kogut]
> 
</details>

# v2.98.35
## (2022-06-03)


<details>
<summary> Update contracts to bba65f2a1904e5ccc61e25793c8b4be1f02f3942 [Renovate Bot] </summary>

> ## contracts-2.0.1
> ### (2022-06-03)
> 
> * Update QEMU to v7.0.0+balena1 [Trong Nghia Nguyen]
> * Remove the wrapper shim that base images have around sh on first run [Trong Nghia Nguyen]
> * Add golang v1.18.3 and v1.17.11 [Trong Nghia Nguyen]
> * Add node v18.3.0 v17.9.1 and v16.15.1 [Trong Nghia Nguyen]
> 
</details>

* Update layers/meta-balena to ff147b2a19933df0c16fb37cb7bb294e77caa985 [Renovate Bot]

# v2.98.34
## (2022-06-01)


<details>
<summary> Update layers/meta-balena to 5bd9f32d3ac9eb7eafb6eca9dd7ccc700fdacea3 [Renovate Bot] </summary>

> ## meta-balena-2.98.34
> ### (2022-06-01)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to b3b1b48 [Renovate Bot] </summary>
> 
>> ### leviathan-2.3.7
>> #### (2022-06-01)
>> 
>> * worker: qemu: remove debug print statements [Joseph Kogut]
>> 
>> ### leviathan-2.3.6
>> #### (2022-05-26)
>> 
>> * core: worker: shorten getDutIp interval [Joseph Kogut]
>> * worker: helpers: memoize resolveLocalTarget [Joseph Kogut]
>> * worker: helpers: resolveLocalTarget: increase timeout [Joseph Kogut]
>> 
> </details>
> 
> 
</details>

# v2.98.33+rev2
## (2022-06-01)


<details>
<summary> Update balena-yocto-scripts to 8cce34e9763389eb59e4e375c532c81eb592fc1e [Renovate Bot] </summary>

> ## balena-yocto-scripts-1.19.8
> ### (2022-06-01)
> 
> * balena-lib: release_finalize: Do not retag phase for ESR branch patch [Alex Gonzalez]
> 
> ## balena-yocto-scripts-1.19.7
> ### (2022-06-01)
> 
> * balena-lib: balena_lib_release_finalize: Pass the correct arguments [Alex Gonzalez]
> * balena-lib: Tag ESR fleets with patch independent tags [Alex Gonzalez]
> 
</details>

# v2.98.33+rev1
## (2022-05-30)


<details>
<summary> Update balena-yocto-scripts to 7b2a89987f196ec4261d240a88c1790c55b366b0 [Renovate Bot] </summary>

> ## balena-yocto-scripts-1.19.6
> ### (2022-05-24)
> 
> * balena-lib: Check versions before finalizing [Alex Gonzalez]
> * balena-deploy-block: Do not always finalise on deploy [Alex Gonzalez]
> * balena-deploy-block: Add OS version to contract [Alex Gonzalez]
> * balena-deploy: Generate OS contract if not available [Alex Gonzalez]
> * balena-lib: Build contracts [Alex Gonzalez]
> * Add generate-oscontract script [Alex Gonzalez]
> 
> ## balena-yocto-scripts-1.19.5
> ### (2022-05-19)
> 
> * jenkins_build: Finalize when required [Alex Gonzalez]
> * balena-lib: Finalise release before tagging [Alex Gonzalez]
> * balena-api: Add function to get final state of release [Alex Gonzalez]
> * balena-lib: Extract release finalization as function [Alex Gonzalez]
> * Update balena-cli version to latest [Alex Gonzalez]
> * balena-deploy: Fix header on balena_deploy_block() [Alex Gonzalez]
> 
</details>

# v2.98.33
## (2022-05-30)


<details>
<summary> Update layers/meta-balena to 95c96e0624507fd9701912c67d3ae5ec5dbdf6f9 [Renovate Bot] </summary>

> ## meta-balena-2.98.33
> ### (2022-05-27)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to 95649fb [Renovate Bot] </summary>
> 
>> ### leviathan-2.3.5
>> #### (2022-05-25)
>> 
>> * workers: qemu: fix vars path for x86_64 [Joseph Kogut]
>> 
> </details>
> 
> 
> ## meta-balena-2.98.32
> ### (2022-05-27)
> 
> * supervisor: Update balena-supervisor to v13.1.11 [Felipe Lalanne]
> 
> ## meta-balena-2.98.31
> ### (2022-05-26)
> 
> * tests: os: config-json: fix race by waiting for InvocationID change [Joseph Kogut]
> * tests: os: reformat config-json tests [Joseph Kogut]
> 
> ## meta-balena-2.98.30
> ### (2022-05-24)
> 
> * Remove localMode setting from standalone image configuration [Alex Gonzalez]
> 
> ## meta-balena-2.98.29
> ### (2022-05-23)
> 
> 
> <details>
> <summary> Update balena-engine to v20.10.17 [Leandro Motta Barros] </summary>
> 
>> ### balena-engine-20.10.17
>> #### (2022-05-17)
>> 
>> * Fix "slice bounds out of range" while applying deltas [Leandro Motta Barros]
>> 
> </details>
> 
> 
> ## meta-balena-2.98.28
> ### (2022-05-20)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to 727ba9f [Renovate Bot] </summary>
> 
>> ### leviathan-2.3.4
>> #### (2022-05-20)
>> 
>> * worker: qemu: add new qemu firmware paths [Joseph Kogut]
>> * worker: install edk2 firmware for aarch64 [Joseph Kogut]
>> * worker: Change default qemu memory from 2G to 512M [Kyle Harding]
>> * make: Do not assume qemu DUT arch will match the host [Kyle Harding]
>> * make: Allow passed env vars to replace any .env values [Kyle Harding]
>> 
> </details>
> 
> 
</details>

# v2.98.27+rev2
## (2022-05-28)


<details>
<summary> Update contracts to 35dea15031cf273d469171f81ed24c394332caf5 [Renovate Bot] </summary>

> ## contracts-2.0.0
> ### (2022-05-27)
> 
> * Clean up installation method and add instruction partials [Micah Halter]
> 
> ## contracts-1.13.76
> ### (2022-05-23)
> 
> * sw.os-image: Add balena-image software image [Alex Gonzalez]
> * sw.os: Add balenaOS contract [Alex Gonzalez]
> 
> ## contracts-1.13.75
> ### (2022-05-21)
> 
> * jetson-xavier-agx: Update L4T in base images [Alexandru Costache]
> 
</details>

# v2.98.27+rev1
## (2022-05-20)

* Add contracts submodule [Alex Gonzalez]

# v2.98.27
## (2022-05-18)


<details>
<summary> Update layers/meta-balena to 7ca0039a8faf417f55cbd72b85a346e6407da04f [Renovate Bot] </summary>

> ## meta-balena-2.98.27
> ### (2022-05-18)
> 
> * patch: Fix heading anchor links in CDS doc index [Vipul Gupta]
> 
</details>

# v2.98.26
## (2022-05-17)


<details>
<summary> Update layers/meta-balena to 5399363b3758860b22ac93a4406d62de5d88b229 [Renovate Bot] </summary>

> ## meta-balena-2.98.26
> ### (2022-05-17)
> 
> * balena-supervisor: Randomize the updater timer period [Alex Gonzalez]
> 
</details>

# v2.98.25
## (2022-05-17)


<details>
<summary> Update layers/meta-balena to b6e9352e8784e433c647811d532d7ab3e2ee05e2 [Renovate Bot] </summary>

> ## meta-balena-2.98.25
> ### (2022-05-16)
> 
> * patch: Get CDS doc ready for docs sync [Vipul Gupta]
> * test: os-config: Use common code to wait for service state [Alex Gonzalez]
> 
</details>


<details>
<summary> Update layers/meta-balena to 5804aabaac3d665b39d0da3e02d8f20c5d6d5db4 [Renovate Bot] </summary>

> ## meta-balena-2.98.25
> ### (2022-05-16)
> 
> * patch: Get CDS doc ready for docs sync [Vipul Gupta]
> * test: os-config: Use common code to wait for service state [Alex Gonzalez]
> 
</details>

# v2.98.23
## (2022-05-13)


<details>
<summary> Update layers/meta-balena to 5e9ec7690114640a5a7c3f6c94bb7e3ed37977ab [Renovate Bot] </summary>

> ## meta-balena-2.98.23
> ### (2022-05-11)
> 
> * linux-firmware: Fix quz-a0-hr-b0 and quz-a0-jf-b0 packaging for compression [Michal Toman]
> 
</details>

# v2.98.22
## (2022-05-11)


<details>
<summary> Update layers/meta-balena to b66f92f791bee0527107453183f60fa9d659dbf9 [Renovate Bot] </summary>

> ## meta-balena-2.98.22
> ### (2022-05-11)
> 
> 
> <details>
> <summary> Update tests/leviathan digest to 01719b5 [Renovate Bot] </summary>
> 
>> ### leviathan-2.3.3
>> #### (2022-05-09)
>> 
>> * Fixes spelling and grammar in e2e [Alex]
>> 
>> ### leviathan-2.3.2
>> #### (2022-05-02)
>> 
>> * Record environment variables to file for client env [Kyle Harding]
>> 
>> ### leviathan-2.3.1
>> #### (2022-05-02)
>> 
>> * patch: Remove development shortcuts [Vipul Gupta (@vipulgupta2048)]
>> 
>> ### leviathan-2.3.0
>> #### (2022-04-29)
>> 
>> * minor: Add support for debug object [Vipul Gupta (@vipulgupta2048)]
>> 
>> ### leviathan-2.2.14
>> #### (2022-04-29)
>> 
>> * patch: Remove Express server port config [Vipul Gupta (@vipulgupta2048)]
>> 
> </details>
> 
> 
</details>

# v2.98.21
## (2022-05-11)


<details>
<summary> Update layers/meta-balena to 96599b31001fc8f7e4eac7fc650a12d43ca39d21 [Renovate Bot] </summary>

> ## meta-balena-2.98.21
> ### (2022-05-11)
> 
> * contributing-device-support.md: Enhance device contribution guide [Florin Sarbu]
> 
</details>

# v2.98.20
## (2022-05-11)


<details>
<summary> Update layers/meta-balena to c98cda89f0be6c168599a2a155ec42a148d0a6cc [Renovate Bot] </summary>

> ## meta-balena-2.98.20
> ### (2022-05-10)
> 
> * renovate: Override commit body for meta-balena to Change-type [Kyle Harding]
> * renovate: Remove extra leviathan package rules [Kyle Harding]
> 
> ## meta-balena-2.98.19
> ### (2022-05-10)
> 
> * tests/connectivity: Force proxy tests to use IPv4 [Kyle Harding]
> * tests/connectivity: Fix compose warnings for expected string [Kyle Harding]
> 
> ## meta-balena-2.98.18
> ### (2022-05-10)
> 
> 
> <details>
> <summary> supervisor: Update balena-supervisor to v13.1.6 [Alex Gonzalez] </summary>
> 
>> ### balena-supervisor-13.1.6
>> #### (2022-05-06)
>> 
>> * Avoid splash image failures if image is corrupt [Felipe Lalanne]
>> 
>> ### balena-supervisor-13.1.5
>> #### (2022-05-03)
>> 
>> * Use write + sync when writing configs to /mnt/boot [Felipe Lalanne]
>> 
> </details>
> 
> 
</details>

# v2.98.17
## (2022-05-06)


<details>
<summary> Update layers/meta-balena to 42c71bfea112ba44e59488fe93284a583654622f [Renovate Bot] </summary>

> ## meta-balena-2.98.17
> ### (2022-05-06)
> 
> * renovate: Override default package rules to enable leviathan [Kyle Harding]
> 
</details>

# v2.98.16
## (2022-05-06)


<details>
<summary> Update layers/meta-balena to 23c6581bee55a61231cdc61e108418e743b7df3e [Renovate Bot] </summary>

> ## meta-balena-2.98.16
> ### (2022-05-05)
> 
> * renovate: Replace tests with tests/suites in default ignorePaths [Kyle Harding]
> 
</details>

# v2.98.15
## (2022-05-04)


<details>
<summary> Update layers/meta-balena to 9685efd5bf2ae5b12d307b2f879c51bd6dbab82e [Renovate Bot] </summary>

> ## meta-balena-2.98.15
> ### (2022-05-04)
> 
> * Rename renovate config [Kyle Harding]
> 
</details>

# v2.98.14
## (2022-05-04)


<details>
<summary> Update layers/meta-balena to 2e10b2d1990f200f5854b2317a71c2272e755df1 [Renovate Bot] </summary>

> ## meta-balena-2.98.14
> ### (2022-05-04)
> 
> 
> <details>
> <summary> supervisor: Update balena-supervisor to v13.1.4 [Kyle Harding] </summary>
> 
>> ### balena-supervisor-13.1.4
>> #### (2022-04-28)
>> 
>> * Use delay instead of interval to recursively report state [20k-ultra]
>> 
>> ### balena-supervisor-13.1.3
>> #### (2022-04-20)
>> 
>> * Remove in memory storage of started/stopped containers [20k-ultra]
>> * Only start a container once in its lifetime This will ensure the restart policy specified is not violated [20k-ultra]
>> 
>> ### balena-supervisor-13.1.2
>> #### (2022-04-18)
>> 
>> * Explain /v2/state/status's status field in its response [Christina Wang]
>> 
>> ### balena-supervisor-13.1.1
>> #### (2022-04-13)
>> 
>> * Do not fail lockfile cleanup if files do not exist [Felipe Lalanne]
>> 
>> ### balena-supervisor-13.1.0
>> #### (2022-04-12)
>> 
>> * Add lockfile binary and internal lib for interfacing with it [Christina Wang]
>> 
>> ### balena-supervisor-13.0.3
>> #### (2022-04-08)
>> 
>> * Add system id/model support for Compulab IOT-gate [Felipe Lalanne]
>> 
>> ### balena-supervisor-13.0.2
>> #### (2022-04-08)
>> 
>> * Correctly evaluate downloadProgress when computing current state [20k-ultra]
>> 
>> ### balena-supervisor-13.0.1
>> #### (2022-04-01)
>> 
>> * Fix database migration for legacyApps [Felipe Lalanne]
>> 
>> ### balena-supervisor-13.0.0
>> #### (2022-03-23)
>> 
>> * Add support for GET v3 target state [Felipe Lalanne]
>> 
>> ### balena-supervisor-12.11.43
>> #### (2022-03-21)
>> 
>> * Always add status to image download report [Felipe Lalanne]
>> 
>> ### balena-supervisor-12.11.42
>> #### (2022-03-18)
>> 
>> * Moved test setup into file included for all tests [20k-ultra]
>> 
>> ### balena-supervisor-12.11.41
>> #### (2022-03-16)
>> 
>> * Added PR template doc [20k-ultra]
>> 
>> ### balena-supervisor-12.11.40
>> #### (2022-03-16)
>> 
>> * Only count report connectivity errors for healthcheck [Felipe Lalanne]
>> * update packages for vulnerabilities [20k-ultra]
>> 
>> ### balena-supervisor-12.11.39
>> #### (2022-03-16)
>> 
>> * Move report throttle out of reporting logic [20k-ultra]
>> * Update npm dep sinon to v11.1.2 [20k-ultra]
>> 
> </details>
> 
> 
</details>

# v2.98.13
## (2022-05-04)


<details>
<summary> Update layers/meta-balena to 393f57d8695ff3d349370f730cabe31d927fc530 [Renovate Bot] </summary>

> ## meta-balena-2.98.13
> ### (2022-05-03)
> 
> * os: tests: optimize connectivity tests [Joseph Kogut]
> 
</details>

# v2.98.12
## (2022-05-03)


<details>
<summary> Update layers/meta-balena to 0c96705ba26cda1062eff0b128eccb4f9388f9cc [Renovate Bot] </summary>

> ## meta-balena-2.98.12
> ### (2022-05-02)
> 
> * tests/hup: Test hostapp-update from current release [Kyle Harding]
> 
</details>

# v2.98.11
## (2022-04-29)


<details>
<summary> Update layers/meta-balena to e13f4afb2c6311450db3fc4e9cb74ef31132e8d6 [Renovate Bot] </summary>

> ## meta-balena-2.98.11
> ### (2022-04-29)
> 
> * tests: os: create swap test [Joseph Kogut]
> 
</details>

# v2.98.10
## (2022-04-29)


<details>
<summary> Update layers/meta-balena to 45726c6e1009bd1988071131762c483193a5ef59 [Renovate Bot] </summary>

> ## meta-balena-2.98.10
> ### (2022-04-28)
> 
> * tests: bump leviathan to 2.13 [rcooke-warwick]
> 
</details>

# v2.98.9+rev1
## (2022-04-28)


<details>
<summary> Update balena-yocto-scripts to fe688d2bfbb121401830ec804fa423619048a224 [Renovate Bot] </summary>

> ## balena-yocto-scripts-1.19.4
> ### (2022-04-28)
> 
> * balena-api.inc: fix 'fatal: unsafe repository' [Florin Sarbu]
> 
</details>

# v2.98.9
## (2022-04-28)


<details>
<summary> Update layers/meta-balena to fc45fb36cc79e5b7eab1017f4e5713773aba7ed1 [Renovate Bot] </summary>

> ## meta-balena-2.98.9
> ### (2022-04-28)
> 
> * tests: bump leviathan to 2.2.11 [rcooke-warwick]
> 
</details>

# v2.98.8
## (2022-04-28)


<details>
<summary> Update layers/meta-balena to 87fb338552e3cfdfcb3500ed65940be897b99bbc [Renovate Bot] </summary>

> ## meta-balena-2.98.8
> ### (2022-04-28)
> 
> * tests/cloud: fix ssh test for testbot workers [rcooke-warwick]
> 
</details>

# v2.98.7
## (2022-04-27)


<details>
<summary> Update layers/meta-balena to 9431a0dcafd13d0218b875f40e7e642d042ae4aa [Renovate Bot] </summary>

> ## meta-balena-2.98.7
> ### (2022-04-27)
> 
> * linux-firmware: package QuZ-a0-jf-b0 separately [Michal Toman]
> 
</details>

# v2.98.6
## (2022-04-27)


<details>
<summary> Update layers/meta-balena to 798e236d25380d70e7be09d8d5dbb0349c05f413 [Renovate Bot] </summary>

> ## meta-balena-2.98.6
> ### (2022-04-26)
> 
> * timeinit/timesync-https: Update rtc after setting system time [Alexandru Costache]
> 
</details>

# v2.98.5
## (2022-04-26)


<details>
<summary> Update layers/meta-balena to edda207aee705431cd02443bdfe8d6271228b96d [Renovate Bot] </summary>

> ## meta-balena-2.98.5
> ### (2022-04-26)
> 
> * networkmanager: Use default DHCP timeout [Zahari Petkov]
> 
</details>

# v2.98.4+rev1
## (2022-04-26)


<details>
<summary> Update balena-yocto-scripts to 13da1d2fd4483ba9a2cf9d3d7146985bbd720c6b [Renovate Bot] </summary>

> ## balena-yocto-scripts-1.19.3
> ### (2022-04-26)
> 
> * balena-lib: fix 445d6d1fcfce97f85ffcfedc0083eb658a734321 [Florin Sarbu]
> 
</details>

# v2.98.4
## (2022-04-26)


<details>
<summary> Update layers/meta-balena to 0d70942b143215aa0c350705d74a71a87d42870a [Renovate Bot] </summary>

> ## meta-balena-2.98.4
> ### (2022-04-25)
> 
> * Disable Engine startup timeouts [Leandro Motta Barros]
> 
</details>

# v2.98.3
## (2022-04-25)


<details>
<summary> Update layers/meta-balena to c71a9ac922091069e6fa736a07213685555ff21c [Renovate Bot] </summary>

> ## meta-balena-2.98.3
> ### (2022-04-25)
> 
> * Add renovate configuration [Kyle Harding]
> 
</details>

# v2.98.2
## (2022-04-25)


<details>
<summary> Update layers/meta-balena to b6b6fc6c137e42a4184d46432c23cd20a35edd6c [Renovate Bot] </summary>

> ## meta-balena-2.98.2
> ### (2022-04-25)
> 
> * balena-config-vars: unit-conf: Correct description [Alex Gonzalez]
> * tests: os: Remove sshKeys test [Alex Gonzalez]
> * tests: cloud: Add SSH authentication tests [Alex Gonzalez]
> * os-sshkeys: When ssh keys change, regenerate development configuration [Alex Gonzalez]
> * development-features: use os-helpers-devmode include file [Alex Gonzalez]
> * os-helpers: Add os-helpers-devmode [Alex Gonzalez]
> 
</details>

# v2.98.1
## (2022-04-24)


<details>
<summary> Update layers/meta-balena to 54c754e97eb0ba3dcb4119908cc368e200c2f4ca [Renovate Bot] </summary>

> ## meta-balena-2.98.1
> ### (2022-04-23)
> 
> * tests/leviathan: Update leviathan to v2.2.4 [Kyle Harding]
> 
</details>


<details>
<summary> Update layers/meta-balena to 5498ce099c7316a58d21c35d970292f1e2443d97 [Renovate Bot] </summary>

> ## meta-balena-2.98.1
> ### (2022-04-23)
> 
> * tests/leviathan: Update leviathan to v2.2.4 [Kyle Harding]
> 
</details>

# v2.97.0
## (2022-04-23)


<details>
<summary> Update layers/meta-balena to a06697e55f26a36c296e51a8eddb81c3dbc1ae51 [Renovate Bot] </summary>

> ## meta-balena-2.97.0
> ### (2022-04-23)
> 
> 
> <details>
> <summary> Update balena-engine to v20.10.16 [Leandro Motta Barros] </summary>
> 
>> ### balena-engine-20.10.16
>> #### (2022-04-07)
>> 
>> * contrib/init/systemd: update balena-engine.service [TIAN Yuanhao]
>> 
>> ### balena-engine-20.10.15
>> #### (2022-04-05)
>> 
>> * Log more info upon when raising errRootFSMismatch [Leandro Motta Barros]
>> 
>> ### balena-engine-20.10.14
>> #### (2022-04-01)
>> 
>> * Add more integration tests for deltas [Leandro Motta Barros]
>> 
>> ### balena-engine-20.10.13
>> #### (2022-03-09)
>> 
>> * Add link to post to test landr [andrew]
>> 
> </details>
> 
> 
</details>


<details>
<summary> Update layers/meta-balena to 0a58c6cdfc324e3fca540c48a119084669f99558 [Renovate Bot] </summary>

> ## meta-balena-2.97.0
> ### (2022-04-23)
> 
> 
> <details>
> <summary> Update balena-engine to v20.10.16 [Leandro Motta Barros] </summary>
> 
>> ### balena-engine-20.10.16
>> #### (2022-04-07)
>> 
>> * contrib/init/systemd: update balena-engine.service [TIAN Yuanhao]
>> 
>> ### balena-engine-20.10.15
>> #### (2022-04-05)
>> 
>> * Log more info upon when raising errRootFSMismatch [Leandro Motta Barros]
>> 
>> ### balena-engine-20.10.14
>> #### (2022-04-01)
>> 
>> * Add more integration tests for deltas [Leandro Motta Barros]
>> 
>> ### balena-engine-20.10.13
>> #### (2022-03-09)
>> 
>> * Add link to post to test landr [andrew]
>> 
> </details>
> 
> 
</details>

# v2.96.0
## (2022-04-22)


<details>
<summary> Update layers/meta-balena to b7490ca45f22591b1e6f7fddc1bf5853f373c125 [Renovate Bot] </summary>

> ## meta-balena-2.96.0
> ### (2022-04-22)
> 
> * mobynit: Update to v0.2.0 [Alex Gonzalez]
> 
</details>

# v2.95.17
## (2022-04-22)


<details>
<summary> Update layers/meta-balena to 7730a5a3808f7d154b47831f930adedecde1cbba [Renovate Bot] </summary>

> ## meta-balena-2.95.17
> ### (2022-04-22)
> 
> * resin-device-register: avoid blocking the flasher when not connected [Alexandru Costache]
> 
</details>

# v2.95.16+rev1
## (2022-04-22)


<details>
<summary> Update balena-yocto-scripts to 63e2b61fa462be4f68a2b7d8ca5084fd2d7d09b2 [Renovate Bot] </summary>

> ## balena-yocto-scripts-1.19.2
> ### (2022-04-21)
> 
> * balena-lib: fix 'fatal: unsafe repository' [Joseph Kogut]
> 
</details>

# v2.95.16
## (2022-04-22)


<details>
<summary> Update layers/meta-balena to 29b972bc69f5ab1778b9b255c0c0554c3407db32 [Renovate Bot] </summary>

> ## meta-balena-2.95.16
> ### (2022-04-19)
> 
> * Package iwlwifi-QuZ-a0-hr-b0 firmware separately [Florin Sarbu]
> 
</details>

# v2.95.15+rev1
## (2022-04-14)


<details>
<summary> Update balena-yocto-scripts to ff9465a20e32843b3b01ec3efa0d8a5390e6d66c [Renovate Bot] </summary>

> ## balena-yocto-scripts-1.19.1
> ### (2022-04-14)
> 
> * deploy: ensure deployRawArtifact is empty instead of null [Joseph Kogut]
> 
> ## balena-yocto-scripts-1.19.0
> ### (2022-04-13)
> 
> * deploy: push image variant artifacts [Joseph Kogut]
> 
</details>

# v2.95.15
## (2022-04-06)


<details>
<summary> Update layers/meta-balena to 831819bead130a779bfa204b7d1df483486f0eaf [Renovate Bot] </summary>

> ## meta-balena-2.95.15
> ### (2022-04-06)
> 
> * kernel-headers-test: clean tools like fixdep [Alexandru Costache]
> 
</details>

# v2.95.14
## (2022-04-06)


<details>
<summary> Update layers/meta-balena to e13a2dbf4bee982f03b709d25b172d670fb7f4f1 [Renovate Bot] </summary>

> ## meta-balena-2.95.14
> ### (2022-04-06)
> 
> * Updates SIM info for soracom and provides docs. [Alex]
> 
</details>

# v2.95.13
## (2022-04-06)


<details>
<summary> Update layers/meta-balena to 93481e8aae8a46c292eb6d4dd628992cedbf7757 [Renovate Bot] </summary>

> ## meta-balena-2.95.13
> ### (2022-04-06)
> 
> * test/hup: fix unmounting error [rcooke-warwick]
> 
</details>

# v2.95.12
## (2022-04-05)


<details>
<summary> Update layers/meta-balena to 8797487542bebf28f89bcb5251437f12c117dec7 [Renovate Bot] </summary>

> ## meta-balena-2.95.12
> ### (2022-04-01)
> 
> * grub-efi: Remove patch passing secure boot status to the kernel [Michal Toman]
> 
> ## meta-balena-2.95.11
> ### (Invalid date)
> 
> * hostapp-update: Mount data partition on target balena/tmp [Kyle Harding]
> 
> ## meta-balena-2.95.10
> ### (Invalid date)
> 
> * tests/os: check supervisor is pulled  after purge [rcooke-warwick]
> 
> ## meta-balena-2.95.9
> ### (2022-03-28)
> 
> * tests: update leviathan to 2.0.4 [rcooke-warwick]
> * tests: update config for new leviathan version [rcooke-warwick]
> 
> ## meta-balena-2.95.8
> ### (2022-03-25)
> 
> * resindataexpander: Check and fix end GPT if necessary [Alexandru Costache]
> 
> ## meta-balena-2.95.7
> ### (2022-03-23)
> 
> * hostapp-update-hooks: Always update legacy development variants to development mode [Alex Gonzalez]
> 
> ## meta-balena-2.95.6
> ### (2022-03-22)
> 
> * balena-supervisor: Use architecture instead of device type to query API [Alex Gonzalez]
> * update-balena-supervisor: Support passing command line image argument [Alex Gonzalez]
> 
> ## meta-balena-2.95.5
> ### (2022-03-21)
> 
> * tests/kernel-overlap: Prevent test run failure on older kernels [Alexandru Costache]
> 
> ## meta-balena-2.95.4
> ### (2022-03-17)
> 
> * tests/os: wait for osconfig service to be inactive [rcooke-warwick]
> 
> ## meta-balena-2.95.3
> ### (2022-03-15)
> 
> * balena-supervisor: Update balena-supervisor to v12.11.38 Ensure preloaded applications are ran when no internet is available on first run [20k-ultra]
> 
> ## meta-balena-2.95.2
> ### (2022-03-11)
> 
> * kernel-balena: Disable building gcc plugins [Alexandru Costache]
> 
</details>

# v2.95.1+rev2
## (2022-04-01)


<details>
<summary> Update balena-yocto-scripts to a5b7cacc6dd4e3a3e03c77513760b6d3a89a68d0 [Renovate Bot] </summary>

> ## balena-yocto-scripts-1.18.0
> ### (2022-04-01)
> 
> * Bump balena-cli to v.Latest [ab77]
> 
> ## balena-yocto-scripts-1.17.12
> ### (2022-03-29)
> 
> * Remove superfluous preload flag [ab77]
> 
> ## balena-yocto-scripts-1.17.11
> ### (2022-03-29)
> 
> * Unattended preload operation [ab77]
> 
> ## balena-yocto-scripts-1.17.10
> ### (2022-03-28)
> 
> * Pass environment to docker [ab77]
> 
> ## balena-yocto-scripts-1.17.9
> ### (2022-03-25)
> 
> * automation: ami: make BALENA_PRELOAD_COMMIT optional [Joseph Kogut]
> 
> ## balena-yocto-scripts-1.17.8
> ### (2022-03-15)
> 
> * balena-deploy: s/resin-flasher/balena-flasher [Joseph Kogut]
> 
> ## balena-yocto-scripts-1.17.7
> ### (2022-03-15)
> 
> * jenkins_generate_ami: surface preload app commit as variable [Joseph Kogut]
> 
</details>

# v2.95.1+rev1
## (2022-03-29)

* Specify full path in repo.yml upstreams [Alex Gonzalez]
* Add renovate configuration [Alex Gonzalez]

# v2.95.1
## (2022-03-11)


<details>
<summary> Update meta-balena from v2.94.3 to v2.95.1 [Florin Sarbu] </summary>

> ## meta-balena-2.95.1
> ### (2022-03-08)
> 
> * tests: Add leviathan v2.0.0 as a submodule [Kyle Harding]
> * tests/cloud: Cleanup wait until loops in cloud suite [Kyle Harding]
> * tests/hup: Remove bluebird and this.context.get references [Kyle Harding]
> * tests/os: Remove bluebird and this.context.get references [Kyle Harding]
> * tests/cloud: Remove bluebird and this.context.get references [Kyle Harding]
> * tests: Cleanup suites config to support both testbot and qemu workers [Kyle Harding]
> * tests/cloud: Update cloud suite to support core on client [Kyle Harding]
> * tests/hup: Update hup suite to support core on client [Kyle Harding]
> * tests/os: Update os suite to support core on client [Kyle Harding]
> 
> ## meta-balena-2.95.0
> ### (2022-03-04)
> 
> * Adds modem test suite [Alex]
> 
> ## meta-balena-2.94.5
> ### (2022-03-04)
> 
> * Use by-state symlink for mounting the EFI partition when split [Michal Toman]
> * os-helpers: add TPM2 helpers [Michal Toman]
> * Add PCR protection policy to TPM operation unlocking LUKS passphrase [Michal Toman]
> 
> ## meta-balena-2.94.4
> ### (2022-03-04)
> 
> * balena-supervisor: Fix supervisor tagging command [Florin Sarbu]
> 
</details>


<details>
<summary> Update balena-yocto-scripts to v1.17.6 [Florin Sarbu] </summary>

> ## balena-yocto-scripts-1.17.6
> ### (2022-03-08)
> 
> * barys: Remove RESINHUP setting [Alex Gonzalez]
> 
> ## balena-yocto-scripts-1.17.5
> ### (2022-03-08)
> 
> * balena-deploy: Avoid patching test suites config.js during deploy [Kyle Harding]
> 
> ## balena-yocto-scripts-1.17.4
> ### (2022-03-03)
> 
> * Init and update submodules when switching meta-balena branches [Kyle Harding]
> 
</details>

* linux-beagleboard: Include aufs module for devices that have been using aufs [Florin Sarbu]

# v2.94.3
## (2022-03-03)


<details>
<summary> Update meta-balena from v2.88.17 to v2.94.3 [Florin Sarbu] </summary>

> ## meta-balena-2.94.3
> ### (2022-03-02)
> 
> * tests/os: fix bracket in bbb overlay test [rcooke-warwick]
> 
> ## meta-balena-2.94.2
> ### (2022-03-02)
> 
> * tests: Enhance BeagleBone Black u-boot overlay test [Florin Sarbu]
> 
> ## meta-balena-2.94.1
> ### (2022-03-01)
> 
> * balena-image: Default image type to balenaos-img [Alex Gonzalez]
> * Remove legacy resinhup images. [Alex Gonzalez]
> 
> ## meta-balena-2.94.0
> ### (2022-03-01)
> 
> 
> <details>
> <summary> Update balena-supervisor to v12.11.36 [Robert Günzler] </summary>
> 
>> ### balena-supervisor-12.11.36
>> #### (2022-02-23)
>> 
>> * Ignore selinux security opts when comparing services [Felipe Lalanne]
>> 
>> ### balena-supervisor-12.11.35
>> #### (2022-02-16)
>> 
>> * Add troubleshooting notice for macOS [fisehara]
>> 
>> ### balena-supervisor-12.11.34
>> #### (2022-02-15)
>> 
>> * Create `touch` and `getBootTime` utility functions [Felipe Lalanne]
>> * Add update lock check to PATCH /v1/device/host-config [Christina Wang]
>> 
>> ### balena-supervisor-12.11.33
>> #### (2022-02-09)
>> 
>> * Add support for local ipv6 reporting [Felipe Lalanne]
>> 
> </details>
> 
> * meta-resin-pyro: make sure $GO is set [Robert Günzler]
> * Refactor balena-engine recipe to more closely resemble upstream [Robert Günzler]
> * Update Golang recipes to 1.16.2 [Robert Günzler]
> 
> <details>
> <summary> Update balena-engine to v20.10.12 [Robert Günzler] </summary>
> 
>> ### balena-engine-20.10.12
>> #### (2022-02-18)
>> 
>> * storagemigration: keep going if migration fails [Robert Günzler]
>> * graphdriver/copy: fix handling of sockets [Robert Günzler]
>> * pkg/storagemigration: use graphdriver/copy.DirCopy [Robert Günzler]
>> * Prune Jenkinsfile [Robert Günzler]
>> * Backport platform-detection fixes from containerd [Robert Günzler]
>> * storagemigration: capture failcleanup logs in logfile [Robert Günzler]
>> * storagemigration: move logic to package [Robert Günzler]
>> * prevent slice oob access in concatReadSeekCloser [Martin Rauscher]
>> * Make layer download resuming more resilient [Leandro Motta Barros]
>> * Drop CODEOWNERS [Robert Günzler]
>> * pkg/storagemigration: poperly handle errors during state creation [Robert Günzler]
>> * pkg/storagemigration: allow writing logs to separate file [Robert Günzler]
>> * storagemigration: defer commit to next start [Robert Günzler]
>> * Lock destination layers while delta is being processed [Robert Günzler]
>> * Add aufs to overlay2 migrator [Robert Günzler]
>> * Update the README [Robert Günzler]
>> * Cleanup repo [Robert Günzler]
>> * Add a SECURITY.md [Robert Günzler]
>> * top_unix.go: allow busybox ps with no args [Kyle Harding]
>> * Bump balena-os/balena-containerd to 1da48a8 [Tian Yuanhao]
>> * Add changelog template to allow generating nested changelogs [Robert Günzler]
>> * Update github issue and pr templates [Robert Günzler]
>> * Update codeowners [Robert Günzler]
>> * hack: Fix CLI versioning [Robert Günzler]
>> * Fixed typos in getting-started.md docs [Miguel Casqueira]
>> * Add integration tests for hostapp handling [Robert Günzler]
>> * Fix container data deletion [Roman Mazur]
>> * overlay2: Add List support [Roman Mazur]
>> * aufs: Add List support [Roman Mazur]
>> * layer: Remove unreferenced driver layers on create [Roman Mazur]
>> * layer: Prune unused data on layer store creation [Roman Mazur]
>> * layer: Persist cacheID early on transaction start [Roman Mazur]
>> * pkg/authorization: Fix test failures on macOS [Roman Mazur]
>> * Move ci to balenaCI [Robert Günzler]
>> * contrib: Add balena-engine version of dind container [Robert Günzler]
>> * build.sh: Disable btrfs,zfs,devicemapper graphdrivers [Robert Günzler]
>> * Bump CLI dependency to include fix for #178 [Robert Günzler]
>> * Bump CLI dependency to include --cidenv flag [Robert Günzler]
>> * Allow passing container ID to container via environment variable [Robert Günzler]
>> * contrib/install.sh: Add details to the success message [Robert Günzler]
>> * contrib/install.sh: Rename balena to balenaEngine in ASCII art output [Robert Günzler]
>> * contrib/install.sh: Fail on error [Robert Günzler]
>> * Add daemon flags to configure max download/upload attempts during pull/push [Robert Günzler]
>> * aufs,overlay2: Add driver opts for disk sync [Robert Günzler]
>> * Fix double locking in the event handling code of OOM events [Robert Günzler]
>> * integration-tests: Add test for containers with memory,cpu constraints [Robert Günzler]
>> * Update Dockerfiles used for build to Go 1.10.8 [Robert Günzler]
>> * travis: Use the minimal machine [Robert Günzler]
>> * Add cli for tagging delta images [Robert Günzler]
>> * Allow tagging of image deltas on creation [Robert Günzler]
>> * docs: Fix Docker capitalisation in balenaEngine docs [Paulo Castro]
>> * Update balenaEngine logo in README.md [Paulo Castro]
>> * Disable incompatible integration tests [Paulo Castro]
>> 
>> ### balena-engine-20.10.11
>> #### (2021-12-09)
>> 
>> * Merge upstream v20.10.11 [Robert Günzler]
>> 
> </details>
> 
> 
> ## meta-balena-2.93.2
> ### (2022-03-01)
> 
> * prepare-openvpn: Make configurable [Alex Gonzalez]
> 
> ## meta-balena-2.93.1
> ### (2022-02-28)
> 
> * tests/cloud: Use deviceID returned from pre-registration [Kyle Harding]
> 
> ## meta-balena-2.93.0
> ### (2022-02-26)
> 
> * resin-device-register: Use supervisor version label instead of tag [Alex Gonzalez]
> * balena-supervisor: Rename repository/tag to fleet/version [Alex Gonzalez]
> * docker-disk: entry.sh: Rename repository/tag to fleet/version [Alex Gonzalez]
> 
> ## meta-balena-2.92.0
> ### (2022-02-25)
> 
> * Update ModemManager to v1.18.4 [Zahari Petkov]
> 
> ## meta-balena-2.91.6
> ### (2022-02-25)
> 
> * resin-device-register: Regenerate VPN credentials on registration [Alex Gonzalez]
> * resin-init-flasher: Wait for resin-device-register to start [Alex Gonzalez]
> 
> ## meta-balena-2.91.5
> ### (2022-02-24)
> 
> * suites/os: Add testcase for RPi device-tree [Alexandru Costache]
> 
> ## meta-balena-2.91.4
> ### (2022-02-24)
> 
> * openvpn: Remove dependency on timesync-http target [Alex Gonzalez]
> 
> ## meta-balena-2.91.3
> ### (2022-02-24)
> 
> * tests/os: Wait for os-config-json service to be inactive [Kyle Harding]
> 
> ## meta-balena-2.91.2
> ### (2022-02-23)
> 
> * contributing-device-support.md: Updates to board support instructions [Florin Sarbu]
> 
> ## meta-balena-2.91.1
> ### (2022-02-21)
> 
> * tests/cloud: wait for update lock message in logs [rcooke-warwick]
> * tests/cloud: register teardown before  online [rcooke-warwick]
> 
> ## meta-balena-2.91.0
> ### (2022-02-14)
> 
> * openssh: Add a dependency on os-sshkeys [Alex Gonzalez]
> * balena-supervisor: Add dependency on root CA [Alex Gonzalez]
> * balena: Add dependency on balena-hostname [Alex Gonzalez]
> * Make services configurable [Alex Gonzalez]
> * classes: Add balena-configurable [Alex Gonzalez]
> * balena-config-vars: Split config.json configuration on write [Alex Gonzalez]
> * Remove config-json.target [Alex Gonzalez]
> 
> ## meta-balena-2.90.0
> ### (2022-02-13)
> 
> * resin-init-flasher: check for UEFI mode and set config variables [Mark Corbin]
> * resin-init-flasher: Fix flashing progress reporting for LUKS [Michal Toman]
> * resin-init-flasher: Use flasher kernel to emulate stage2 bootloader with LUKS [Michal Toman]
> * resin-init-flasher: Add support for opt-in full disk encryption [Michal Toman]
> 
> ## meta-balena-2.89.19
> ### (2022-02-13)
> 
> * README: Update versioning information [Alex Gonzalez]
> 
> ## meta-balena-2.89.18
> ### (2022-02-11)
> 
> * fix cloud suite teardown [rcooke-warwick]
> 
> ## meta-balena-2.89.17
> ### (2022-02-09)
> 
> * suites/hup: Add under-voltage test before and after HUP [Alexandru Costache]
> 
> ## meta-balena-2.89.16
> ### (2022-02-07)
> 
> * balena-supervisor: Update balena-supervisor to v12.11.32 [Felipe Lalanne]
> 
> ## meta-balena-2.89.15
> ### (2022-02-07)
> 
> * resindataexpander: do not return after resizing the partition only [Michal Toman]
> 
> ## meta-balena-2.89.14
> ### (2022-02-03)
> 
> * resin-u-boot.bbclass: Do not error if no config_defaults.h [Florin Sarbu]
> 
> ## meta-balena-2.89.13
> ### (2022-02-01)
> 
> * docker-disk: Tag the supervisor digest with the repo name [Kyle Harding]
> 
> ## meta-balena-2.89.12
> ### (2022-02-01)
> 
> * resindataexpander: expand fs independent of partition [Joseph Kogut]
> 
> ## meta-balena-2.89.11
> ### (2022-01-29)
> 
> * image_types_balena: Augment dependency on u-boot do_deploy task [Florin Sarbu]
> 
> ## meta-balena-2.89.10
> ### (2022-01-28)
> 
> * tests: relax boot splash screen check [rcooke-warwick]
> 
> ## meta-balena-2.89.9
> ### (2022-01-27)
> 
> * archive logs using local ssh [rcooke-warwick]
> * put archiver in the right place [rcooke-warwick]
> * Enable UART serial console for supported devices [Kyle Harding]
> * archive image on teardown [rcooke-warwick]
> * put device in dev mode [rcooke-warwick]
> * tests: add extra logging to cloud suite [rcooke-warwick]
> 
> ## meta-balena-2.89.8
> ### (2022-01-27)
> 
> * u-boot: Move config fragments merging code out of common layer [Florin Sarbu]
> 
> ## meta-balena-2.89.7
> ### (2022-01-26)
> 
> * explain balenaRootCA better [Martin Rauscher]
> 
> ## meta-balena-2.89.6
> ### (2022-01-26)
> 
> * classes/kernel-balena: Update aufs patches for kernel 5.10.82 [Alexandru Costache]
> 
> ## meta-balena-2.89.5
> ### (2022-01-24)
> 
> * os: tests: optimize fingerprint tests [Joseph Kogut]
> 
> ## meta-balena-2.89.4
> ### (2022-01-21)
> 
> * tests: add cloud test suite [rcooke-warwick]
> 
> ## meta-balena-2.89.3
> ### (2022-01-20)
> 
> * initramfs-framework: Make cleaning udev database the last step [Alex Gonzalez]
> 
> ## meta-balena-2.89.2
> ### (2022-01-20)
> 
> * recipes-core/jq: Use 64bit time symbols [Alexandru Costache]
> 
> ## meta-balena-2.89.1
> ### (2022-01-19)
> 
> * tests: Enable UART serial console where supported [Kyle Harding]
> 
> ## meta-balena-2.89.0
> ### (2022-01-19)
> 
> * docker-disk: Pull images from Balena's registry [Alex Gonzalez]
> * balena-supervisor: Use image location path instead of repository:tag [Alex Gonzalez]
> * distro: balena-os: Add default cloud environment distro setting [Alex Gonzalez]
> 
> ## meta-balena-2.88.22
> ### (2022-01-18)
> 
> * intel-quark: Fix to honister syntax [Alex Gonzalez]
> * recipes-core/bash: Use 64bit time symbols [Alexandru Costache]
> * recipes-core/busybox: Use 64bit time symbols [Alexandru Costache]
> 
> ## meta-balena-2.88.21
> ### (2022-01-17)
> 
> * tests: os: config-json: cleanup persistentLogging test [Joseph Kogut]
> * tests: os: config-json: return promise from sshKeys test [Joseph Kogut]
> * tests: os: config-json: cleanup dnsServers config test [Joseph Kogut]
> * tests: os: config-json: cleanup ntpServer config test [Joseph Kogut]
> * tests: os: config-json: cleanup hostname config test [Joseph Kogut]
> * tests: os: create waitForServiceState helper [Joseph Kogut]
> * tests: os: config-json: remove reboot from randomMacAddressScan test [Joseph Kogut]
> * tests: os: config-json: remove reboot from connectivity test [Joseph Kogut]
> * tests: os: config-json: remove reboot from udevRules test [Joseph Kogut]
> 
> ## meta-balena-2.88.20
> ### (2022-01-17)
> 
> * chrony: fix mount service dependency for driftfile [Mark Corbin]
> 
> ## meta-balena-2.88.19
> ### (2022-01-12)
> 
> * os: tests: optimize fsck tests [Joseph Kogut]
> 
> ## meta-balena-2.88.18
> ### (2022-01-11)
> 
> * conf/distro: Prefer rust v1.36 for releases older than Honister [Alexandru Costache]
> 
</details>


<details>
<summary> Update balena-yocto-scripts to v1.17.3 [Florin Sarbu] </summary>

> ## balena-yocto-scripts-1.17.3
> ### (2022-03-02)
> 
> * jenkins_build: Use recurse-submodules when checking out meta-balena [Kyle Harding]
> 
</details>

# v2.88.17+rev6
## (2022-02-25)


<details>
<summary> Update balena-yocto-scripts to v1.17.2 [Alex Gonzalez] </summary>

> ## balena-yocto-scripts-1.17.2
> ### (2022-02-25)
> 
> * prepare-and-start: Remove balena login [Alex Gonzalez]
> 
> ## balena-yocto-scripts-1.17.1
> ### (2022-01-27)
> 
> * balena-deploy.inc: Do no deploy device logo to deprecated endpoint [Florin Sarbu]
> 
</details>

# v2.88.17+rev5
## (2022-01-20)


<details>
<summary> Update balena-yocto-scripts to v1.17.0 [Alex Gonzalez] </summary>

> ## balena-yocto-scripts-1.17.0
> ### (2022-01-20)
> 
> * balena-lib: Fix fetching meta-balena base version [Alex Gonzalez]
> * jenkins_build-block: Use true/false for ESR variable [Alex Gonzalez]
> * balena-deploy-block: Label ESR hostapps [Alex Gonzalez]
> * balena-api: add balena_api_fetch_fleet_tag [Alex Gonzalez]
> * balena-api: Set policy on ESR hostapps [Alex Gonzalez]
> * balena-deploy: Pass ESR variable when creating apps [Alex Gonzalez]
> 
> ## balena-yocto-scripts-1.16.4
> ### (2022-01-18)
> 
> * balena-deploy: Deploy passing the latest meta-balena version and not tag [Alex Gonzalez]
> * balena-lib: Add balena_lib_get_meta_balena_base_version [Alex Gonzalez]
> 
</details>

# v2.88.17+rev4
## (2022-01-18)


<details>
<summary> Update balena-yocto-scripts to v1.16.3 [Alex Gonzalez] </summary>

> ## balena-yocto-scripts-1.16.3
> ### (2022-01-17)
> 
> * balena-deploy-block: Check for existing tag only in specific hostapp [Alex Gonzalez]
> 
</details>

# v2.88.17+rev3
## (2022-01-16)


<details>
<summary> Update balena-yocto-scripts to v1.16.2 [Alex Gonzalez] </summary>

> ## balena-yocto-scripts-1.16.2
> ### (2022-01-15)
> 
> * balena-api: Propagate balena API environment, token and OS organization [Alex Gonzalez]
> * balena-build.sh: Propagate balena API environment and token [Alex Gonzalez]
> * prepare-and-start: Propagate balena API environment and token [Alex Gonzalez]
> 
</details>

# v2.88.17+rev2
## (2022-01-14)

* recipes-core/systemd: Move audit socket removal to meta-balena [Alexandru Costache]

# v2.88.17+rev1
## (2022-01-12)


<details>
<summary> Update balena-yocto-scripts to v1.16.1 [Alex Gonzalez] </summary>

> ## balena-yocto-scripts-1.16.1
> ### (2022-01-11)
> 
> * revert_overrides: Add intel-quark to architecture overrides [Alex Gonzalez]
> 
</details>

# v2.88.17
## (2022-01-11)


<details>
<summary> Update meta-balena from v2.85.16 to v2.88.17 [Florin Sarbu] </summary>

> ## meta-balena-2.88.17
> ### (2022-01-10)
> 
> * recipes-core/coreutils: Use 64bit time symbols [Alexandru Costache]
> * classes/image_types_balena: Preserve file modification times with mcopy [Alexandru Costache]
> 
> ## meta-balena-2.88.16
> ### (2022-01-05)
> 
> * balena-os.inc: Switch balena backend storage to overlay2 [Florin Sarbu]
> 
> ## meta-balena-2.88.15
> ### (2022-01-04)
> 
> * initrdscripts: fsuuidinit: Generate resin-rootA last [Alex Gonzalez]
> * lvm2: Add rule to persist dm devices in udev database [Alex Gonzalez]
> * initrdscript: Cleanup udev database before transitioning to rootfs [Alex Gonzalez]
> * initrdscripts: Use /run as bootparam_root storage [Alex Gonzalez]
> * lvm: Add lvm rules when secure boot is configured [Alex Gonzalez]
> * balena-keys: Fetch DER keys and decode from base64 [Alex Gonzalez]
> 
> ## meta-balena-2.88.14
> ### (2022-01-04)
> 
> * Sync cached writes to disk when updating supervisor.conf [Miguel Casqueira]
> 
> ## meta-balena-2.88.13
> ### (2022-01-04)
> 
> * hostapp-update-hooks: Handle developmentMode updates [Alex Gonzalez]
> 
> ## meta-balena-2.88.12
> ### (2022-01-03)
> 
> * systemd/timeinit: handle missing date field in HTTPS header [Mark Corbin]
> 
> ## meta-balena-2.88.11
> ### (2021-12-22)
> 
> * balena-supervisor: Update balena-supervisor to v12.11.16 Update balena-supervisor from 12.11.0 to 12.11.16 [Miguel Casqueira]
> 
> ## meta-balena-2.88.10
> ### (2021-12-16)
> 
> * Update NetworkManager to 1.32.12 [Zahari Petkov]
> 
> ## meta-balena-2.88.9
> ### (2021-12-15)
> 
> * u-boot: Move u-boot configs inclusion into resin-u-boot.bbclass [Florin Sarbu]
> 
> ## meta-balena-2.88.8
> ### (2021-12-09)
> 
> * patch: Add archiveLogs Teardown for HUP suite [Vipul Gupta]
> 
> ## meta-balena-2.88.7
> ### (2021-12-06)
> 
> * tests: Ensure BDADDR is initialized [Alexandru Costache]
> 
> ## meta-balena-2.88.6
> ### (2021-12-04)
> 
> * docs: Fix links in Rollback documentation [Kyle Harding]
> 
> ## meta-balena-2.88.5
> ### (2021-12-04)
> 
> * tests: os: fix unhandled exception when unwrapping non-flasher image [Joseph Kogut]
> 
> ## meta-balena-2.88.4
> ### (2021-12-03)
> 
> * tests: Add basic checks for data loss during HUP [Kyle Harding]
> * hostapp-update-hooks: Ensure data breadcrumb is present before HUP [Kyle Harding]
> 
> ## meta-balena-2.88.3
> ### (2021-12-02)
> 
> * grub-conf: Delay grub boot in os development mode [Alex Gonzalez]
> * grub-efi: Allow input/output in OS development mode [Alex Gonzalez]
> 
> ## meta-balena-2.88.2
> ### (2021-12-02)
> 
> * sign-efi.bbclass: Do not deploy the unused .signed symlink [Michal Toman]
> * sign-gpg.bbclass: Only deploy the detached signature [Michal Toman]
> * kernel-image-initramfs.bb: Ship kernel and matching signature [Michal Toman]
> * Make kexec work under kernel lockdown [Michal Toman]
> 
> ## meta-balena-2.88.1
> ### (2021-12-02)
> 
> * bluez5: Update to bluez 5.61 from poky honister [Kyle Harding]
> 
> ## meta-balena-2.88.0
> ### (2021-12-01)
> 
> * systemd/timeinit: add HTTPS time synchronisation service [Mark Corbin]
> 
> ## meta-balena-2.87.32
> ### (2021-12-01)
> 
> * tests: Add BeagleBone Black u-boot overlay test [Florin Sarbu]
> 
> ## meta-balena-2.87.31
> ### (2021-11-30)
> 
> * resin-update-state.rules: do not run for unnamed partitions [Michal Toman]
> * resin_update_state_probe: do not skip device mapper devices [Michal Toman]
> 
> ## meta-balena-2.87.30
> ### (2021-11-30)
> 
> * tests: Add device specific RevPi Core 3 DIO module test [Alexandru Costache]
> 
> ## meta-balena-2.87.29
> ### (2021-11-29)
> 
> * common: image-balena: enable developmentMode when OS_DEVELOPMENT=1 [Joseph Kogut]
> 
> ## meta-balena-2.87.28
> ### (2021-11-26)
> 
> * Add secure boot keys to the flasher boot partition [Alex Gonzalez]
> 
> ## meta-balena-2.87.27
> ### (2021-11-25)
> 
> * balena-os: make sure PAM support is not configured [Alex Gonzalez]
> 
> ## meta-balena-2.87.26
> ### (2021-11-25)
> 
> * tests: add test for filesystem checks [Joseph Kogut]
> * common: initrdscript: fsck resin-data on boot [Joseph Kogut]
> 
> ## meta-balena-2.87.25
> ### (2021-11-25)
> 
> * connectivity: reduce ping interval to minimum [Joseph Kogut]
> 
> ## meta-balena-2.87.24
> ### (2021-11-24)
> 
> * tests: Fix dnsmasq tests in cases where 8.8.8.8 is assigned via DHCP [Kyle Harding]
> 
> ## meta-balena-2.87.23
> ### (2021-11-24)
> 
> * 0-signed-update HUP hook: mount efivarfs if necessary [Michal Toman]
> 
> ## meta-balena-2.87.22
> ### (2021-11-24)
> 
> * grub-efi: Accept no input and output nothing when in secure boot mode [Michal Toman]
> 
> ## meta-balena-2.87.21
> ### (2021-11-24)
> 
> * linux-firmware: Include MT7601U firmware [Zahari Petkov]
> 
> ## meta-balena-2.87.20
> ### (2021-11-23)
> 
> * balena-image: Add balena keys to boot partition if required [Alex Gonzalez]
> * grub-conf: Enforce module signing and integrity lockdown on luks config [Alex Gonzalez]
> * distro: balena-os: Add empty SIGN_API [Alex Gonzalez]
> * classes: image-balena: Copy signed files if present [Alex Gonzalez]
> * classes/sign-gpg: Rename class to sign_gpg [Alex Gonzalez]
> * classes: Rename sign to sign-gpg [Alex Gonzalez]
> * classes: sign: Drop suffix from deployed files [Alex Gonzalez]
> * resin-init-flasher: Set fde grub.cfg if secure boot is enabled [Alex Gonzalez]
> * balena-image-initramfs: Add secure boot dependencies [Alex Gonzalez]
> * kernel-image-initramfs: Install signed kernel images if available [Alex Gonzalez]
> * kernel-balena: Configure for secure boot [Alex Gonzalez]
> 
> ## meta-balena-2.87.19
> ### (2021-11-22)
> 
> * common: enable multi-label mDNS resolution and IPv6 [Joseph Kogut]
> 
> ## meta-balena-2.87.18
> ### (2021-11-22)
> 
> * unwrap flasher images in os suite if needed [rcooke-warwick]
> * bluetooth and hup test with qemu [rcooke-warwick]
> 
> ## meta-balena-2.87.17
> ### (2021-11-21)
> 
> * efitools: Add recipe [Alex Gonzalez]
> * sbsigntool: Add recipe [Alex Gonzalez]
> 
> ## meta-balena-2.87.16
> ### (2021-11-21)
> 
> * peak: Modify kernel driver to use signing class [Alex Gonzalez]
> 
> ## meta-balena-2.87.15
> ### (2021-11-21)
> 
> * kernel-balena.class: Add support for FDE and sign for secure boot [Michal Toman]
> 
> ## meta-balena-2.87.14
> ### (2021-11-21)
> 
> * sign-efi.bbclass: do not mix old and new bitbake syntax [Michal Toman]
> * Revert "sign-efi.class, sign-kmod.class: Replace original files with signed ones" [Michal Toman]
> 
> ## meta-balena-2.87.13
> ### (2021-11-20)
> 
> * meta-resin-sumo/pyro: Fix initramfs-framework kexec dependencies [Alex Gonzalez]
> * initrdscripts: Use a 2nd stage bootloader to unlock LUKS partitions [Michal Toman]
> * grub-efi: add support for signature verification in secure boot mode [Michal Toman]
> 
> ## meta-balena-2.87.12
> ### (2021-11-20)
> 
> * initramfs-module-cryptsetup: add TPM dependencies [Michal Toman]
> 
> ## meta-balena-2.87.11
> ### (2021-11-20)
> 
> * balena-keys: Add recipe [Alex Gonzalez]
> 
> ## meta-balena-2.87.10
> ### (2021-11-20)
> 
> * sign-efi.class, sign-kmod.class: Replace original files with signed ones [Michal Toman]
> * Add signing classes [Alex Gonzalez]
> 
> ## meta-balena-2.87.9
> ### (2021-11-17)
> 
> * hostapp-update-hooks: Add a hook that aborts HUP to unsigned OS under secure boot [Michal Toman]
> 
> ## meta-balena-2.87.8
> ### (2021-11-17)
> 
> * resin-mounts: mount EFI partition if it is split from boot [Michal Toman]
> 
> ## meta-balena-2.87.7
> ### (2021-11-16)
> 
> * initrdscripts: add a script for unlocking LUKS volumes [Michal Toman]
> 
> ## meta-balena-2.87.6
> ### (2021-11-15)
> 
> * connectivity: proxy: move nadoo/glider to container [Joseph Kogut]
> 
> ## meta-balena-2.87.5
> ### (2021-11-11)
> 
> * tests: os: Add exposed engine socket test [Alex Gonzalez]
> 
> ## meta-balena-2.87.4
> ### (2021-11-11)
> 
> * resindataexpander: also resize LUKS volume if necessary [Michal Toman]
> 
> ## meta-balena-2.87.3
> ### (2021-11-11)
> 
> * Add out-of-tree peak CAN driver [Michal Toman]
> 
> ## meta-balena-2.87.2
> ### (2021-11-11)
> 
> * Add recipes for TPM2 tools [Michal Toman]
> 
> ## meta-balena-2.87.1
> ### (2021-11-10)
> 
> * recipes-devtools/dosfstools: Fix build with Poky Honister [Alexandru Costache]
> 
> ## meta-balena-2.87.0
> ### (2021-11-09)
> 
> * meta-balena-common/conf: Switch layer to Honister compatibility [Alexandru Costache]
> 
> ## meta-balena-2.86.3
> ### (2021-11-09)
> 
> * patch: Fix URL to yocto project dependencies [Kyle Harding]
> 
> ## meta-balena-2.86.2
> ### (2021-11-08)
> 
> * dosfstools: selectively apply upstreamed patch [Joseph Kogut]
> * tests: wait for the chronyd service become active [Mark Corbin]
> 
> ## meta-balena-2.86.1
> ### (2021-11-02)
> 
> * tests/issue: Add test to check issues files [Alex Gonzalez]
> * base files: Use HOSTOS_VERSION in issue and issue.net [Alex Gonzalez]
> 
> ## meta-balena-2.86.0
> ### (2021-10-29)
> 
> * Create new data partition reset service [Kyle Harding]
> 
> ## meta-balena-2.85.17
> ### (2021-10-28)
> 
> * restrict dtoverlay test to rpi devices [rcooke-warwick]
> 
</details>

# v2.85.16+rev3
## (2022-01-03)


<details>
<summary> Update balena-yocto-scripts to v1.16.0 [Alex Gonzalez] </summary>

> ## balena-yocto-scripts-1.16.0
> ### (2021-12-30)
> 
> * balena-deploy: Check for file existence before deploying [Alex Gonzalez]
> * balena-deploy-block: Check existence of tag before re-deploying [Alex Gonzalez]
> * balena-api: Add function to check the existence of a release tag [Alex Gonzalez]
> * balena-deploy-block: Finalize releases when deployed [Alex Gonzalez]
> * Accept deployments without balena.yml [Alex Gonzalez]
> * jenkins_generate_ami: Remove variant from image name [Alex Gonzalez]
> * balena-build.sh: Stop building OS variants [Alex Gonzalez]
> * jenkins_build.sh: Remove buildFlavor [Alex Gonzalez]
> * jenkins_build-blocks: Remove variant build option [Alex Gonzalez]
> * balena-deploy: Stop using .dev/.prod variant suffixes [Alex Gonzalez]
> * balena-deploy-block: Stop tagging hostapp releases with variant [Alex Gonzalez]
> * balena-lib: Use externalVersion to match contracts [Alex Gonzalez]
> * jenkins_build: Deploy hostapp like any other block [Alex Gonzalez]
> * jenkins_build-blocks: Separate block build release deployment [Alex Gonzalez]
> * balena-deploy-block: Use release versioning [Alex Gonzalez]
> * jenkins_build: Remove discontinued check [Alex Gonzalez]
> * balena-deploy: Do not deploy discontinued device types [Alex Gonzalez]
> * balena-deploy: Discontinued device types use meta-balena version [Alex Gonzalez]
> * balena-deploy: Adapt balena_deploy_block to release versioning and use it [Alex Gonzalez]
> * balena-build-block: Remove image release [Alex Gonzalez]
> * balena-api: Use release revision for fetchers [Alex Gonzalez]
> * jenkins_build-block: Remove release version API setter [Alex Gonzalez]
> * balena-api: Remove release version API setter [Alex Gonzalez]
> * balena-lib: Use release versioning [Alex Gonzalez]
> 
> ## balena-yocto-scripts-1.15.10
> ### (2021-12-02)
> 
> * balena-deploy: Set leviathan networkWireless mode based on device slug [Kyle Harding]
> 
> ## balena-yocto-scripts-1.15.9
> ### (2021-11-26)
> 
> * Substitute the worker types for generic device slugs [Kyle Harding]
> 
</details>

# v2.85.16+rev2
## (2021-11-04)


<details>
<summary> Update balena-yocto-scripts from v1.15.5 to v1.15.8 [Alexandru Costache] </summary>

> ## balena-yocto-scripts-1.15.8
> ### (2021-11-03)
> 
> * Dockerfile_yocto-build-env: Install Honister host deps [Alexandru Costache]
> 
> ## balena-yocto-scripts-1.15.7
> ### (2021-10-25)
> 
> * jenkins_build.sh: Fix deployment for discontinued device types [Alex Gonzalez]
> * jenkins_build.sh: Remove PRIVATE_DT as it is unused [Alex Gonzalez]
> * jenkins_build.sh: Fix lint warnings [Alex Gonzalez]
> 
> ## balena-yocto-scripts-1.15.6
> ### (2021-10-21)
> 
> * balena-generate-ami.sh: wait for boot partition when preloading AMI [Michal Toman]
> 
</details>

# v2.85.16+rev1
## (2021-10-27)


<details>
<summary> Update meta-balena from v2.85.6 to v2.85.16 [Robert Günzler] </summary>

> ## meta-balena-2.85.16
> ### (2021-10-27)
> 
> 
> <details>
> <summary> Update balena-engine to v19.03.30 [Robert Günzler] </summary>
> 
>> ### balena-engine-19.03.30
>> #### (2021-10-26)
>> 
>> * storagemigration: keep going if migration fails [Robert Günzler]
>> * graphdriver/copy: fix handling of sockets [Robert Günzler]
>> 
> </details>
> 
> 
> ## meta-balena-2.85.15
> ### (2021-10-26)
> 
> * linux-firmware: Include RTL8723BU firmware files [Zahari Petkov]
> 
> ## meta-balena-2.85.14
> ### (2021-10-25)
> 
> * balena-supervisor: Update balena-supervisor to v12.11.0 [Felipe Lalanne]
> 
> ## meta-balena-2.85.13
> ### (2021-10-21)
> 
> * balena-engine: Remove deprecated development drop-in service file [Kyle Harding]
> 
> ## meta-balena-2.85.12
> ### (2021-10-21)
> 
> * make led test work with beaglebone [rcooke-warwick]
> 
> ## meta-balena-2.85.11
> ### (2021-10-06)
> 
> * patch: Add dtoverlay practical test [Vipul Gupta (@vipulgupta2048)]
> 
> ## meta-balena-2.85.10
> ### (2021-10-04)
> 
> * image-balena: Decouple boot directory generation from rootfs task [Alex Gonzalez]
> 
> ## meta-balena-2.85.9
> ### (2021-10-01)
> 
> * classes/resin-u-boot: Increase OS_BOOTCOUNT_LIMIT to 3 [Alexandru Costache]
> 
> ## meta-balena-2.85.8
> ### (2021-09-29)
> 
> * hostapp-update-hooks: Blacklist Rock Pi configuration file [Alexandru Costache]
> 
> ## meta-balena-2.85.7
> ### (2021-09-28)
> 
> * balena-healthcheck: Remove redundant steps and rely on hello-world [Kyle Harding]
> 
</details>

# v2.85.6+rev4
## (2021-10-26)


<details>
<summary> Update balena-yocto-scripts from v1.14.9 to v1.15.5 [Alexandru Costache] </summary>

> ## balena-yocto-scripts-1.15.5
> ### (2021-10-21)
> 
> * jenkins_generate_ami.sh: Use a shared directory for preloaded image [Michal Toman]
> 
> ## balena-yocto-scripts-1.15.4
> ### (2021-10-20)
> 
> * barys: update development image variables [Mark Corbin]
> 
> ## balena-yocto-scripts-1.15.3
> ### (2021-10-20)
> 
> * jenkins_generate_ami.sh: Preload outside of yocto cache [Michal Toman]
> 
> ## balena-yocto-scripts-1.15.2
> ### (2021-10-01)
> 
> * balena-generate-ami.sh: correctly mount boot partition when injecting SSH key [Michal Toman]
> 
> ## balena-yocto-scripts-1.15.1
> ### (2021-10-01)
> 
> * Update balena-cli to 12.50.1 [Michal Toman]
> 
> ## balena-yocto-scripts-1.15.0
> ### (2021-10-01)
> 
> * jenkins_generate_ami.sh: Use lib function to get arch from config.json [Michal Toman]
> * balena-generate-ami.sh: Look for boot partition by label rather than hardcoding p1 [Michal Toman]
> * balena-generate-ami.sh: Fail if AMI already exists [Michal Toman]
> * balena-generate-ami.sh: sync after writing config.json [Michal Toman]
> * balena-generate-ami.sh: Stick to POSIX-compliant [ instead of [[ [Michal Toman]
> * balena-generate-ami.sh: Remove useless statements [Michal Toman]
> * jenkins_generate_ami.sh: Use architecture as suffix instead of machine name [Michal Toman]
> * jenkins_build.sh: pass MACHINE to jenkins_generate_ami.sh [Michal Toman]
> * AMI automation: Adjust AMI names to be compatible with AWS API [ab77]
> * AMI automation: Correct S3 bucket name and key [ab77]
> * AMI automation: Add a separate container for generaing AMI [Michal Toman]
> * AMI automation: shellcheck and resolve violations [ab77]
> * AMI automation: Use staging env by default [Tomás Tormo]
> * AMI automation: Simplify public ssh addition. Do not use sudo [Tomás Tormo]
> * automation: Generate and publish AMI from the raw balenaOS image [Tomás Tormo]
> 
</details>

# v2.85.6+rev3
## (2021-10-18)

* meta-balena-beaglebone: update local.conf.sample [Mark Corbin]

# v2.85.6+rev2
## (2021-10-15)

* Add am335x-bonegreen-wireless-uboot-univ to rootfs for people using gpios on BeagleBone Green Wireless [Claude Sammut]

# v2.85.6+rev1
## (2021-09-29)


<details>
<summary> Update meta-balena from v2.84.3 to v2.85.6 [Robert Günzler] </summary>

> ## meta-balena-2.85.6
> ### (2021-09-27)
> 
> * kernel-balena: Fix kernel config warning for UPROBE_EVENTS [Alex Gonzalez]
> * kernel-balena: Configure DEBUG_FS [Alex Gonzalez]
> 
> ## meta-balena-2.85.5
> ### (2021-09-23)
> 
> * Run iwlwifi firmware cleanup in fakeroot [Kyle Harding]
> 
> ## meta-balena-2.85.4
> ### (2021-09-21)
> 
> * common: conf: create disable-user-ns distro feature [Joseph Kogut]
> 
> ## meta-balena-2.85.3
> ### (2021-09-21)
> 
> * balena-os-sysctl: Reduce the console default loglevel [Alex Gonzalez]
> * balena-config-vars: Re-run os-sshkeys if config.json is modified [Alex Gonzalez]
> * systemd: Use drop-in to modify unit files instead of sed [Alex Gonzalez]
> 
> ## meta-balena-2.85.2
> ### (2021-09-17)
> 
> 
> <details>
> <summary> Update balena-engine to v19.03.29 [Robert Günzler] </summary>
> 
>> ### balena-engine-19.03.29
>> #### (2021-09-14)
>> 
>> * pkg/storagemigration: use graphdriver/copy.DirCopy [Robert Günzler]
>> 
>> ### balena-engine-19.03.28
>> #### (2021-09-14)
>> 
>> * Prune Jenkinsfile [Robert Günzler]
>> 
>> ### balena-engine-19.03.27
>> #### (2021-09-01)
>> 
>> * Backport platform-detection fixes from containerd [Robert Günzler]
>> 
> </details>
> 
> 
> ## meta-balena-2.85.1
> ### (2021-09-17)
> 
> * Fix typo in OS_DEVELOPMENT distro feature [Kyle Harding]
> * tests: Remove OS variants [Alex Gonzalez]
> 
> ## meta-balena-2.85.0
> ### (2021-09-15)
> 
> * Replace image variants with development mode [Alex Gonzalez]
> 
> <details>
> <summary> balena-supervisor: Update balena-supervisor to v12.10.10 [Alex Gonzalez] </summary>
> 
>> ### balena-supervisor-12.10.10
>> #### (2021-09-07)
>> 
>> * api-keys: Remove os variant parameter for authentication check [Alex Gonzalez]
>> * os-release: Use developmentMode to ascertain OS variant in new releases [Alex Gonzalez]
>> * config: Add developmentMode to schema [Alex Gonzalez]
>> 
>> ### balena-supervisor-12.10.9
>> #### (2021-09-02)
>> 
>> * Update URL to balena-proxy-config source code [Kyle Harding]
>> 
>> ### balena-supervisor-12.10.8
>> #### (2021-09-01)
>> 
>> * Bump path-parse from 1.0.6 to 1.0.7 [dependabot[bot]]
>> 
>> ### balena-supervisor-12.10.7
>> #### (2021-09-01)
>> 
>> * Bump tar from 4.4.13 to 4.4.19 [dependabot[bot]]
>> 
>> ### balena-supervisor-12.10.6
>> #### (2021-09-01)
>> 
>> * Remove "variable list" heading in configuration doc [Miguel Casqueira]
>> 
>> ### balena-supervisor-12.10.5
>> #### (2021-08-31)
>> 
>> * Clean up configurations.md [Miguel Casqueira]
>> 
>> ### balena-supervisor-12.10.4
>> #### (2021-08-31)
>> 
>> * Include issues with downgrading versions in README [Miguel Casqueira]
>> 
> </details>
> 
> * u-boot: Introduce a compile time osdev-image feature [Alex Gonzalez]
> * os-release: Remove image variants information [Alex Gonzalez]
> * Replace DEVELOPMENT_IMAGE and image variants with OS_DEVELOPMENT [Alex Gonzalez]
> * images: Remove debug-tweaks settings. [Alex Gonzalez]
> * openssh: Enable runtime development configuration [Alex Gonzalez]
> * balena-info: Rename from resin-info [Alex Gonzalez]
> * balena: Expose engine socket on development mode [Alex Gonzalez]
> * image-balena: Allow passwordless root logins [Alex Gonzalez]
> * image_balena: Remove "balena" hostname from development images [Alex Gonzalez]
> * systemd: Runtime enablement of serial console [Alex Gonzalez]
> * development-features: Add service for development features runtime management [Alex Gonzalez]
> 
> ## meta-balena-2.84.7
> ### (2021-09-13)
> 
> * hostapp-update-hooks: Fix blacklisted extlinux.conf file path [Alexandru Costache]
> 
> ## meta-balena-2.84.6
> ### (2021-09-11)
> 
> * balena-persistent-logs: add comment and update logging [Mark Corbin]
> * meta-balena: rename resin-persistent-logs [Mark Corbin]
> 
> ## meta-balena-2.84.5
> ### (2021-09-10)
> 
> * tests: led: require led property from device type [Joseph Kogut]
> 
> ## meta-balena-2.84.4
> ### (2021-09-09)
> 
> * tests: Remove reboots from redsocks test cases [Kyle Harding]
> 
</details>

# v2.84.3+rev1
## (2021-09-10)


<details>
<summary> Update meta-balena from v2.81.1 to v2.84.3 [Robert Günzler] </summary>

> ## meta-balena-2.84.3
> ### (2021-09-09)
> 
> * tests: Prevent failure when journalctl has no logs for some boots [Kyle Harding]
> 
> ## meta-balena-2.84.2
> ### (2021-09-08)
> 
> * contributing-device-support.md: Updates to board support instructions [Florin Sarbu]
> 
> ## meta-balena-2.84.1
> ### (2021-09-05)
> 
> * tests: s/BALENA_MACHINE_NAME/BALENA_ARCH [Joseph Kogut]
> 
> ## meta-balena-2.84.0
> ### (2021-09-03)
> 
> * balena-engine: Enable storage migration [Robert Günzler]
> 
> <details>
> <summary> Update balena-engine to v19.03.26 [Robert Günzler] </summary>
> 
>> ### balena-engine-19.03.26
>> #### (2021-08-31)
>> 
>> * storagemigration: capture failcleanup logs in logfile [Robert Günzler]
>> 
>> ### balena-engine-19.03.25
>> #### (2021-08-20)
>> 
>> * storagemigration: move logic to package [Robert Günzler]
>> 
> </details>
> 
> 
> ## meta-balena-2.83.22
> ### (2021-09-02)
> 
> * tests: remove healthcheck test race condition [rcooke-warwick]
> 
> ## meta-balena-2.83.21
> ### (2021-09-01)
> 
> * tests: Register teardown only when DUT is reachable [rcooke-warwick]
> 
> ## meta-balena-2.83.20
> ### (2021-09-01)
> 
> * tests: Use new Archiver implementation & helpers [Vipul Gupta (@vipulgupta2048)]
> 
> ## meta-balena-2.83.19
> ### (2021-09-01)
> 
> * tests: List boots when collecting journal logs in hup suite [Kyle Harding]
> 
> ## meta-balena-2.83.18
> ### (2021-08-31)
> 
> 
> <details>
> <summary> balena-supervisor: Update balena-supervisor to v12.10.3 [Kyle Harding] </summary>
> 
>> ### balena-supervisor-12.10.3
>> #### (2021-08-24)
>> 
>> * Skip restarting services if they are part of conf targets [Kyle Harding]
>> 
>> ### balena-supervisor-12.10.2
>> #### (2021-08-02)
>> 
>> * Removed fire emoji prefix for firewall logs. [peakyDicers]
>> 
>> ### balena-supervisor-12.10.1
>> #### (2021-08-02)
>> 
>> * Fix regression with local mode push [Felipe Lalanne]
>> 
>> ### balena-supervisor-12.10.0
>> #### (2021-07-28)
>> 
>> * Remove comparison based on image, release, and service ids [Felipe Lalanne]
>> 
>> ### balena-supervisor-12.9.6
>> #### (2021-07-26)
>> 
>> * Use tags to track supervised images in docker [Felipe Lalanne]
>> 
>> ### balena-supervisor-12.9.5
>> #### (2021-07-22)
>> 
>> * Log the delta URL that will be downloaded on update [Felipe Lalanne]
>> 
>> ### balena-supervisor-12.9.4
>> #### (2021-07-08)
>> 
>> * Fix db-helper module for tests [Felipe Lalanne]
>> 
> </details>
> 
> 
> ## meta-balena-2.83.17
> ### (2021-08-31)
> 
> * Assign a fixed name to the balena-healthcheck container [Kyle Harding]
> 
> ## meta-balena-2.83.16
> ### (2021-08-31)
> 
> * kernel-modules-headers: Copy module.lds [Alex Gonzalez]
> 
> ## meta-balena-2.83.15
> ### (2021-08-30)
> 
> * kernel-balena: remove global blacklist of btrfs [Joseph Kogut]
> 
> ## meta-balena-2.83.14
> ### (2021-08-26)
> 
> * tests: remove reboot requirement from NTP server test [Mark Corbin]
> * recipes-connectivity: fix auto-update when config.json changes [Mark Corbin]
> 
> ## meta-balena-2.83.13
> ### (2021-08-26)
> 
> * networkmanager: fix hostname race condition [Mark Corbin]
> 
> ## meta-balena-2.83.12
> ### (2021-08-25)
> 
> * tests: remove reboot requirement from hostname test [Mark Corbin]
> * hostname: update system hostname when config.json changes [Mark Corbin]
> 
> ## meta-balena-2.83.11
> ### (2021-08-24)
> 
> * linux-firmware: Use wildcards when selecting files to package [Alex Gonzalez]
> * linux-firmware: Add firmware compression support [Alex Gonzalez]
> * kernel-balena: Support firmware compression from kernel version 5.3 [Alex Gonzalez]
> 
> ## meta-balena-2.83.10
> ### (2021-08-18)
> 
> * kernel-balena: Add function to conditionally configure based on version [Alex Gonzalez]
> * kernel-balena: Split function to get kernel version from source [Alex Gonzalez]
> * kernel-resin: Add as symlink to kernel-balena [Alex Gonzalez]
> * kernel-balena: Replace and deprecate kernel-resin [Alex Gonzalez]
> 
> ## meta-balena-2.83.9
> ### (2021-08-17)
> 
> * recipes-connectivity: improve NTP dispatcher script [Mark Corbin]
> 
> ## meta-balena-2.83.8
> ### (2021-08-17)
> 
> 
> <details>
> <summary> Update balena-engine to v19.03.24 [Alex Gonzalez] </summary>
> 
>> ### balena-engine-19.03.24
>> #### (2021-08-12)
>> 
>> * prevent slice oob access in concatReadSeekCloser [Martin Rauscher]
>> 
> </details>
> 
> 
> ## meta-balena-2.83.7
> ### (2021-08-14)
> 
> * grub: don't package or install bindir utils [Joseph Kogut]
> 
> ## meta-balena-2.83.6
> ### (2021-08-13)
> 
> * balena-os-sysctl: disable user namespacing by default [Joseph Kogut]
> * common: kernel-resin: enable user namespacing [Joseph Kogut]
> 
> ## meta-balena-2.83.5
> ### (2021-08-13)
> 
> * resin-u-boot.bbclass: Make console silencing change more resilient [Florin Sarbu]
> 
> ## meta-balena-2.83.4
> ### (2021-08-11)
> 
> * balena-os: pin linux-firmware to 20210511 from hardknott [Joseph Kogut]
> * linux-firmware: upgrade 20190815 -> 20210511 [Joseph Kogut]
> 
> ## meta-balena-2.83.3
> ### (2021-08-05)
> 
> * supervisor: Consolidate supervisor container removal [Kyle Harding]
> 
> ## meta-balena-2.83.2
> ### (2021-08-05)
> 
> * tests: Fix insecure registry error [Robert Günzler]
> 
> ## meta-balena-2.83.1
> ### (2021-07-31)
> 
> * linux-firmware: package i915 generations separately [Joseph Kogut]
> 
> ## meta-balena-2.83.0
> ### (2021-07-29)
> 
> * Add support for rootfs on MD RAID1 [Michal Toman]
> 
> ## meta-balena-2.82.13
> ### (2021-07-29)
> 
> * tests: Symlink /dev/null instead of copying bash to break services [Michal Toman]
> 
> ## meta-balena-2.82.12
> ### (2021-07-24)
> 
> * common: grub: don't install sbin utils [Joseph Kogut]
> 
> ## meta-balena-2.82.11
> ### (2021-07-21)
> 
> * tests: Remove journalctl line limit from hup suite [Kyle Harding]
> * tests: Enable rollback tests in hup suite [Kyle Harding]
> * tests: Update smoke test conditions [Kyle Harding]
> * tests: Add rollback tests to HUP suite [Kyle Harding]
> * rollback-altboot: Fix minor typo in log message [Kyle Harding]
> 
> ## meta-balena-2.82.10
> ### (2021-07-20)
> 
> * tests: Remove reboot requirement from dnsmasq tests [Kyle Harding]
> 
> ## meta-balena-2.82.9
> ### (2021-07-16)
> 
> * patch: Make OS test suite compatible with current helpers [Vipul Gupta (@vipulgupta2048)]
> 
> ## meta-balena-2.82.8
> ### (2021-07-16)
> 
> * kernel-devsrc: Add upstream recipe from hardknott-3.3.1 for dunfell [Florin Sarbu]
> 
> ## meta-balena-2.82.7
> ### (2021-07-15)
> 
> 
> <details>
> <summary> Update balena-engine to v19.03.23 [Leandro Motta Barros] </summary>
> 
>> ### balena-engine-19.03.23
>> #### (2021-07-12)
>> 
>> * Make layer download resuming more resilient [Leandro Motta Barros]
>> 
>> ### balena-engine-19.03.22
>> #### (2021-06-30)
>> 
>> * Drop CODEOWNERS [Robert Günzler]
>> 
>> ### balena-engine-19.03.21
>> #### (2021-06-25)
>> 
>> * Lock destination layers while delta is being processed [Robert Günzler]
>> 
>> ### balena-engine-19.03.20
>> #### (2021-06-17)
>> 
>> * pkg/storagemigration: poperly handle errors during state creation [Robert Günzler]
>> 
>> ### balena-engine-19.03.19
>> #### (2021-06-10)
>> 
>> * pkg/storagemigration: allow writing logs to separate file [Robert Günzler]
>> * storagemigration: defer commit to next start [Robert Günzler]
>> 
> </details>
> 
> 
> ## meta-balena-2.82.6
> ### (2021-07-15)
> 
> * dnsmasq: Restart when config.json changes [Kyle Harding]
> * balena-config-vars: Restart target when config.json changes [Kyle Harding]
> * balena-config-vars: Add config-json.target service [Kyle Harding]
> * balena-config-vars: Restore null as valid for dnsServers [Kyle Harding]
> 
> ## meta-balena-2.82.5
> ### (2021-07-15)
> 
> * kernel-headers-test: Update base image to buster [Florin Sarbu]
> 
> ## meta-balena-2.82.4
> ### (2021-07-14)
> 
> * tests: Add hup test suite [Robert Günzler]
> 
> ## meta-balena-2.82.3
> ### (2021-07-13)
> 
> * Check that the hostapp image fits the inactive partion on HUP [Alex Gonzalez]
> * image-balena: Add check for docker image size [Alex Gonzalez]
> * balena-image: Break down the rootfs image size calculation [Alex Gonzalez]
> * image_types_balena: Add rootfs size calculation function [Alex Gonzalez]
> 
> ## meta-balena-2.82.2
> ### (2021-07-13)
> 
> * Update balena-supervisor from v12.8.8 to v12.9.3 [Miguel Casqueira]
> 
> ## meta-balena-2.82.1
> ### (2021-07-12)
> 
> * balena-hostname: add comments and improve logging [Mark Corbin]
> * meta-balena: rename resin-hostname to balena-hostname [Mark Corbin]
> 
> ## meta-balena-2.82.0
> ### (2021-07-10)
> 
> * networkmanager: Rename references to resin [Kyle Harding]
> * resin-proxy-config: Rename to balena-proxy-config [Kyle Harding]
> * resin-ntp-config: Rename to balena-ntp-config [Kyle Harding]
> * resin-net-config: Rename to balena-net-config [Kyle Harding]
> 
</details>

# v2.81.1+rev3
## (2021-08-26)

* Add balena-yocto-scripts upstream source [Alex Gonzalez]

# v2.81.1+rev2
## (2021-08-24)

* Update balena-yocto-scripts from v1.14.7 to v1.14.9 [Alex Gonzalez]

# v2.81.1+rev1
## (2021-07-19)

* Update balena-yocto-scripts from v1.11.0 to v1.14.7 [Alex Gonzalez]

<details>
<summary> Update meta-balena from v2.79.7 to v2.81.1 [Alex Gonzalez] </summary>

> ## meta-balena-2.81.1
> ### (2021-07-09)
> 
> * balena-engine: Restore previous systemd service settings [Kyle Harding]
> 
> ## meta-balena-2.81.0
> ### (2021-07-06)
> 
> * recipes-core: add a 'network connectivity wait' service [Mark Corbin]
> 
> ## meta-balena-2.80.12
> ### (2021-07-05)
> 
> * Remove CODEOWNERS [Michal Toman]
> 
> ## meta-balena-2.80.11
> ### (2021-07-01)
> 
> * get journal logs at the end of the suite [rcooke-warwick]
> 
> ## meta-balena-2.80.10
> ### (2021-06-24)
> 
> * hostapp-update-hooks: Migrate supervisor database [Kyle Harding]
> * hostapp-update-hooks: Revert sv database path used by previous hooks [Kyle Harding]
> 
> ## meta-balena-2.80.9
> ### (2021-06-21)
> 
> * balena-engine: refactor systemd service [Robert Günzler]
> 
> ## meta-balena-2.80.8
> ### (2021-06-21)
> 
> * Update balena-supervisor from v12.8.7 to v12.8.8 [Florin Sarbu]
> 
> ## meta-balena-2.80.7
> ### (2021-06-18)
> 
> * prevent failed teardown from making test hang [rcooke-warwick]
> 
> ## meta-balena-2.80.6
> ### (2021-06-17)
> 
> * catch error if image path is corrupted [rcooke-warwick]
> 
> ## meta-balena-2.80.5
> ### (2021-06-17)
> 
> * update-balena-supervisor: Improve obtaining the supervisor directory name [Alexandru Costache]
> * Update balena-supervisor from v12.7.0 to v12.8.7 [Miguel Casqueira]
> 
> ## meta-balena-2.80.4
> ### (2021-06-14)
> 
> * kernel-headers-test: simplify example module Makefile [Joseph Kogut]
> 
> ## meta-balena-2.80.3
> ### (2021-06-10)
> 
> * Add oneshot service to migrate supervisor state config [Kyle Harding]
> 
> ## meta-balena-2.80.2
> ### (2021-06-09)
> 
> * update-balena-supervisor: Refactor script to ensure target version is ran [Alexandru Costache]
> 
> ## meta-balena-2.80.1
> ### (2021-06-07)
> 
> * bluez5: Disable PnP Device Information service [Zahari Petkov]
> 
> ## meta-balena-2.80.0
> ### (2021-06-07)
> 
> * Revert Go 1.16 recipes [Joseph Kogut]
> 
> ## meta-balena-2.79.10
> ### (2021-06-03)
> 
> * supervisor: Remove symlink to legacy resin sysconfig [Kyle Harding]
> * hostapp-update-hooks: Migrate resin-supervisor to balena-supervisor [Kyle Harding]
> * supervisor: Remove legacy resin supervisor container [Kyle Harding]
> 
> ## meta-balena-2.79.9
> ### (2021-06-03)
> 
> * hostapp-update-hooks: Sync to disk when hook is done [Alex Gonzalez]
> * extract-balena-ca: Sync changes to disk in case of power loss [Alex Gonzalez]
> * resin-net-config: Make sure to sync changes to disk in case of power loss [Alex Gonzalez]
> 
> ## meta-balena-2.79.8
> ### (2021-06-02)
> 
> * bluez: Set policy configuration to AutoEnable [Alex Gonzalez]
> * bluez5: Replace executable path directory in unit file [Alex Gonzalez]
> 
</details>

# v2.79.7+rev1
## (2021-06-02)


<details>
<summary> Update meta-balena from v2.78.0 to v2.79.7 [Mark Corbin] </summary>

> ## meta-balena-2.79.7
> ### (2021-05-26)
> 
> * meta-balena: rename connectivity packagegroup [Mark Corbin]
> 
> ## meta-balena-2.79.6
> ### (2021-05-26)
> 
> * bluez5: Use bluez5 recipe from poky master [Zahari Petkov]
> 
> ## meta-balena-2.79.5
> ### (2021-05-21)
> 
> * README: Update supported Yocto versions [Alex Gonzalez]
> 
> ## meta-balena-2.79.4
> ### (2021-05-21)
> 
> * Skip some services when running under docker [Robert Günzler]
> 
> ## meta-balena-2.79.3
> ### (2021-05-20)
> 
> * kernel-resin: disable panic on hung task [Joseph Kogut]
> 
> ## meta-balena-2.79.2
> ### (2021-05-19)
> 
> * Add boot-splash test to unmanaged suite [rcooke-warwick]
> 
> ## meta-balena-2.79.1
> ### (2021-05-18)
> 
> * balena-os: Add preferred provider for Go native [Alex Gonzalez]
> 
> ## meta-balena-2.79.0
> ### (2021-05-13)
> 
> * balena-engine: build in GOPATH mode [Joseph Kogut]
> * recipes-devtools: go: backport get_linuxloader [Joseph Kogut]
> * meta-resin-pyro: go-native: include fix-goarch.inc [Joseph Kogut]
> * meta-balena-common: upgrade from go 1.12.17 to 1.16.2 [Joseph Kogut]
> 
> ## meta-balena-2.78.2
> ### (2021-05-13)
> 
> * balena-config-vars: improve handling of NM config parameters [Mark Corbin]
> 
> ## meta-balena-2.78.1
> ### (2021-05-12)
> 
> * Add Device Tree tests [Vipul Gupta (@vipulgupta2048)]
> 
</details>

* balena-beaglebone: rename connectivity packagegroup [Mark Corbin]

# v2.78.0+rev1
## (2021-05-11)

* Rename resin-supervisor to balena-supervisor [Kyle Harding]

<details>
<summary> Update meta-balena from v2.73.15 to v2.78.0 [Kyle Harding] </summary>

> ## meta-balena-2.78.0
> ### (2021-05-10)
> 
> * Add symlinks and aliases for legacy resin namespaces [Kyle Harding]
> * Rename resin-supervisor to balena-supervisor [Kyle Harding]
> 
> ## meta-balena-2.77.2
> ### (2021-05-10)
> 
> 
> <details>
> <summary> Update balena-supservisor from v12.5.10 to v12.7.0 [Kyle Harding] </summary>
> 
>> ### balena-supervisor-12.7.0
>> #### (2021-05-07)
>> 
>> * Backwards compatility changes for old resin namespaces [Kyle Harding]
>> * Change container name to balena_supervisor [Kyle Harding]
>> * Rename resin-supervisor to balena-supervisor [Kyle Harding]
>> 
>> ### balena-supervisor-12.6.8
>> #### (2021-05-06)
>> 
>> * Show warning instead of exception for invalid network config [Felipe Lalanne]
>> 
>> ### balena-supervisor-12.6.7
>> #### (2021-05-06)
>> 
>> * Patch awaiting response when checking if supervisor0 network exists [Miguel Casqueira]
>> 
>> ### balena-supervisor-12.6.6
>> #### (2021-05-06)
>> 
>> * Fix parsing driver_opts from compose to docker network creation [quentinGllmt]
>> 
>> ### balena-supervisor-12.6.5
>> #### (2021-05-06)
>> 
>> 
>> <details>
>> <summary> Update balena-register-device and send extra info at provision time [Pagan Gazzard] </summary>
>> 
>>> #### balena-register-device-7.2.0
>>> ##### (2021-04-29)
>>> 
>>> * Support `supervisorVersion`/`osVersion`/`osVariant`/`macAddress` fields [Pagan Gazzard]
>>> 
>>> #### balena-register-device-7.1.1
>>> ##### (2021-04-29)
>>> 
>>> * Update dependencies [Pagan Gazzard]
>>> 
>>> #### balena-register-device-7.1.0
>>> ##### (2020-07-13)
>>> 
>>> * Switch from randomstring to uuid for generating device uuids [Pagan Gazzard]
>>> 
>>> #### balena-register-device-7.0.1
>>> ##### (2020-07-13)
>>> 
>>> * Add .versionbot/CHANGELOG.yml for nested changelogs [Pagan Gazzard]
>>> 
>>> #### balena-register-device-7.0.0
>>> ##### (2020-07-06)
>>> 
>>> * Convert to type checked javascript [Pagan Gazzard]
>>> * Drop callback interface in favor of promise interface [Pagan Gazzard]
>>> * Switch to a named export [Pagan Gazzard]
>>> * Convert to typescript [Pagan Gazzard]
>>> * Update to typed-error 3.x [Pagan Gazzard]
>>> * Switch to returning native promises [Pagan Gazzard]
>>> * Update to balena-request 11.x [Pagan Gazzard]
>>> * Use typescript import helpers [Pagan Gazzard]
>>> 
>> </details>
>> 
>> 
>> ### balena-supervisor-12.6.4
>> #### (2021-05-05)
>> 
>> * Log error responses from API when reporting state [Felipe Lalanne]
>> 
>> ### balena-supervisor-12.6.3
>> #### (2021-05-04)
>> 
>> * Added configurations.md to document all configurable vars [Miguel Casqueira]
>> 
>> ### balena-supervisor-12.6.2
>> #### (2021-04-30)
>> 
>> * Remove version tag from livepush generated image [Felipe Lalanne]
>> 
>> ### balena-supervisor-12.6.1
>> #### (2021-04-27)
>> 
>> * Remove mz, mkdirp, body-parser dependencies [Christina Wang]
>> 
>> ### balena-supervisor-12.6.0
>> #### (2021-04-27)
>> 
>> * Bump dockerode types to 2.5.34 [Felipe Lalanne]
>> 
>> ### balena-supervisor-12.5.16
>> #### (2021-04-27)
>> 
>> * Enable docker layer caching on CircleCI [Miguel Casqueira]
>> 
>> ### balena-supervisor-12.5.15
>> #### (2021-04-26)
>> 
>> * Added clean step to remove previous builds before running tests [Miguel Casqueira]
>> 
>> ### balena-supervisor-12.5.14
>> #### (2021-04-26)
>> 
>> * balena-supervisor: replace references to resin-vars [Mark Corbin]
>> 
>> ### balena-supervisor-12.5.13
>> #### (2021-04-25)
>> 
>> * Update supervisor to typescript 4 [Felipe Lalanne]
>> 
>> ### balena-supervisor-12.5.12
>> #### (2021-04-20)
>> 
>> * Bump ssri from 6.0.1 to 6.0.2 [dependabot[bot]]
>> 
>> ### balena-supervisor-12.5.11
>> #### (2021-04-14)
>> 
>> * Refactor extra_uEnv to not match with intel nuc [Miguel Casqueira]
>> 
> </details>
> 
> 
> ## meta-balena-2.77.1
> ### (2021-05-10)
> 
> * Update os-config from v1.2.0 to v1.2.1 [Kyle Harding]
> 
> ## meta-balena-2.77.0
> ### (2021-05-05)
> 
> * grub update hook: move variables from grub.cfg to grubenv [Michal Toman]
> 
> ## meta-balena-2.76.0
> ### (2021-04-30)
> 
> * kernel: Always include overlayfs support [Robert Günzler]
> 
> ## meta-balena-2.75.1
> ### (2021-04-29)
> 
> * grub: grub-efi: buildin gzio for gz compressed kernels [Joseph Kogut]
> 
> ## meta-balena-2.75.0
> ### (2021-04-22)
> 
> * Update mobynit to the new multi-container hostOS specification [Alex Gonzalez]
> 
> ## meta-balena-2.74.0
> ### (2021-04-20)
> 
> * balena-engine: Update to 19.03.18 [Robert Günzler]
> 
</details>

# v2.73.15+rev1
## (2021-04-26)


<details>
<summary> Update meta-balena from v2.73.1 to v2.73.15 [Alex Gonzalez] </summary>

> ## meta-balena-2.73.15
> ### (2021-04-20)
> 
> * modemmanager:u-blox-switch: Rework the u-blox modem switch to ECM mode [Florin Sarbu]
> 
> ## meta-balena-2.73.14
> ### (2021-04-19)
> 
> * device-progress: do not force an exit code [Matthew McGinn]
> 
> ## meta-balena-2.73.13
> ### (2021-04-19)
> 
> * add retries to status check [rcooke-warwick]
> 
> ## meta-balena-2.73.12
> ### (2021-04-16)
> 
> * meta-balena: rename resin-vars to balena-config-vars [Mark Corbin]
> 
> ## meta-balena-2.73.11
> ### (2021-04-16)
> 
> * patch: Add strict bootcount count condition [Vipul Gupta (@vipulgupta2048)]
> * patch: Reactivate Persistent Logging test [Vipul Gupta (@vipulgupta2048)]
> 
> ## meta-balena-2.73.10
> ### (2021-04-14)
> 
> * repo.yml: Move balena-supervisor reference to balena-os [Alex Gonzalez]
> 
> ## meta-balena-2.73.9
> ### (2021-04-14)
> 
> * Update balena-supervisor from v12.5.6 to v12.5.10 [Christina Wang]
> 
> ## meta-balena-2.73.8
> ### (2021-04-13)
> 
> * resin-mounts/etc-fake-hwclock: add dependency on resin-state services [Mark Corbin]
> 
> ## meta-balena-2.73.7
> ### (2021-04-13)
> 
> * fix udev test indentation [rcooke-warwick]
> * Added comments for easier debugging [rcooke-warwick]
> * Fix old tests + add new tests based on testlodge [rcooke-warwick]
> 
> ## meta-balena-2.73.6
> ### (2021-04-12)
> 
> * Add automated test checking for udev/resin_update_state_probe warnings [Michal Toman]
> * udev: Silence warnings from resin_update_state_probe [Michal Toman]
> 
> ## meta-balena-2.73.5
> ### (2021-04-06)
> 
> * Update balena-supervisor from v12.4.6 to v12.5.6 [Christina Wang]
> 
> ## meta-balena-2.73.4
> ### (2021-03-20)
> 
> * Add to persistent logging defn [Andrew Nhem]
> 
> ## meta-balena-2.73.3
> ### (2021-03-19)
> 
> * wifi: remove listed example as it's discontinued [Tomás Migone]
> 
> ## meta-balena-2.73.2
> ### (2021-03-17)
> 
> * hostapp-update: convert absolute symlinks to relative [Joseph Kogut]
> 
</details>

# v2.73.1+rev2
## (2021-03-19)

* resin-image: Install new BT package for kernel 5.4.70 [Alexandru Costache]

# v2.73.1+rev1
## (2021-03-17)


<details>
<summary> Update meta-balena from v2.72.0 to v2.73.1 [Alexandru Costache] </summary>

> ## meta-balena-2.73.1
> ### (2021-03-16)
> 
> * Update balena-supervisor from v12.3.5 to v12.4.6 [Felipe Lalanne]
> 
> ## meta-balena-2.73.0
> ### (2021-03-15)
> 
> * image_types_balena: make rootfs labeling generic [Joseph Kogut]
> * image_types_balena: make agnostic to root fstype [Joseph Kogut]
> * mkfs-hostapp-native: make agnostic to fstype [Joseph Kogut]
> 
> ## meta-balena-2.72.2
> ### (2021-03-15)
> 
> * balena: dissolve healthcheck-image-load into healthcheck script [Robert Günzler]
> 
> ## meta-balena-2.72.1
> ### (2021-03-11)
> 
> * Fix disablement of userspace firmware loading requests [Pelle van Gils]
> 
</details>

# v2.72.0+rev1
## (2021-03-11)

* Rename resin image types to balena [Kyle Harding]

<details>
<summary> Update meta-balena from v2.69.1 to v2.72.0 [Kyle Harding] </summary>

> ## meta-balena-2.72.0
> ### (2021-03-10)
> 
> 
> <details>
> <summary> os-config: Update os-config from v1.1.4 to v1.2.0 [Kyle Harding] </summary>
> 
>> ### os-config-1.2.0
>> #### (2021-02-23)
>> 
>> * os-config: rename flasher flag path [Kyle Harding]
>> 
> </details>
> 
> * Rename resin image types to balena [Kyle Harding]
> 
> ## meta-balena-2.71.7
> ### (2021-03-08)
> 
> * Apply aufs patches if aufs is present in kernel config [Kyle Harding]
> 
> ## meta-balena-2.71.6
> ### (2021-03-05)
> 
> * grub-efi: build required modules into grub image [Joseph Kogut]
> 
> ## meta-balena-2.71.5
> ### (2021-03-03)
> 
> * initrdscripts: always use by-uuid symlink looking for flasher rootfs [Michal Toman]
> 
> ## meta-balena-2.71.4
> ### (2021-03-01)
> 
> * Update OS test suite [Vipul Gupta (@vipulgupta2048)]
> 
> ## meta-balena-2.71.3
> ### (2021-02-26)
> 
> * balena: Make the healthcheck loading service part of balena.service [Robert Günzler]
> 
> ## meta-balena-2.71.2
> ### (2021-02-23)
> 
> * dnsmasq: enable dbus support [Kyle Harding]
> * dnsmasq: update to 2.84 with dnspooq fix [Kyle Harding]
> 
> ## meta-balena-2.71.1
> ### (2021-02-23)
> 
> * recipes-bsp: grub: install only release modules [Joseph Kogut]
> 
> ## meta-balena-2.71.0
> ### (2021-02-15)
> 
> * meta-balena-common: add grub-efi support [Joseph Kogut]
> 
> ## meta-balena-2.70.2
> ### (2021-02-12)
> 
> * Update PR template to specify test coverage in more detail [Alex Gonzalez]
> * Update codeowners [Alex Gonzalez]
> 
> ## meta-balena-2.70.1
> ### (2021-02-11)
> 
> * Add leviathan automated OS test suite [Vipul Gupta (@vipulgupta2048)]
> 
> ## meta-balena-2.70.0
> ### (2021-02-11)
> 
> * systemd/timeinit: use systemd mount unit for /etc/fake-hwclock [Mark Corbin]
> 
</details>

* Update balena-yocto-scripts from v1.9.0 to v1.11.0 [Kyle Harding]

# v2.69.1+rev1
## (2021-02-12)


<details>
<summary> Update meta-balena from v2.68.1 to v2.69.1 [Alexandru Costache] </summary>

> ## meta-balena-2.69.1
> ### (2021-02-03)
> 
> * Update balena-supervisor from v12.3.0 to v12.3.5 [Miguel Casqueira]
> 
> ## meta-balena-2.69.0
> ### (2021-02-01)
> 
> * openvpn: remove resin-ntp-config call from upscript.sh [Mark Corbin]
> * resin-vars: trigger NTP config script on config.json changes [Mark Corbin]
> * resin-ntp-config: update script and add systemd service [Mark Corbin]
> * networkmanager: add improved dispatcher scripts for NTP handling [Mark Corbin]
> * chrony: add sourcedir support and helper script [Mark Corbin]
> 
</details>

# v2.68.1+rev1
## (2021-02-08)


<details>
<summary> Update meta-balena from v2.67.3 to v2.68.1 [Alex Gonzalez] </summary>

> ## meta-balena-2.68.1
> ### (2021-01-29)
> 
> * Fix task ordering for the iwlwifi_firmware_clean task [Florin Sarbu]
> 
> ## meta-balena-2.68.0
> ### (2021-01-29)
> 
> * Update NetworkManager to 1.28.0 [Zahari Petkov]
> 
> ## meta-balena-2.67.6
> ### (2021-01-28)
> 
> * docs: mention balenaRootCA as a config.json parameter [Matthew McGinn]
> 
> ## meta-balena-2.67.5
> ### (2021-01-27)
> 
> * replace busybox ps with procps [klutchell] [Kyle Harding]
> 
> ## meta-balena-2.67.4
> ### (2021-01-27)
> 
> * Update aufs4 and aufs5 kernel patches [Florin Sarbu]
> 
</details>

# v2.67.3+rev1
## (2021-01-25)


<details>
<summary> Update meta-balena from v2.65.1 to v2.67.3 [Alexandru Costache] </summary>

> ## meta-balena-2.67.3
> ### (2021-01-15)
> 
> * kernel-headers-test: Install python dependency [Alexandru Costache]
> 
> ## meta-balena-2.67.2
> ### (2021-01-14)
> 
> * Fix pppd timeout when launched by NetworkManager [Zahari Petkov]
> 
> ## meta-balena-2.67.1
> ### (2021-01-13)
> 
> * resin-device-register: Fix post provisioning state not reported [Alexandru Costache]
> 
> ## meta-balena-2.67.0
> ### (2021-01-12)
> 
> * Update balena-supervisor from v12.2.11 to v12.3.0 [Felipe Lalanne]
> 
> ## meta-balena-2.66.3
> ### (2021-01-12)
> 
> * Respect custom CA in supervisor [Michal Toman]
> 
> ## meta-balena-2.66.2
> ### (2021-01-11)
> 
> * README: Rename resin-logo to balena-logo. [Alex Gonzalez]
> 
> ## meta-balena-2.66.1
> ### (2021-01-04)
> 
> * kernel-devsrc: use upstream recipe starting with dunfell [Kyle Harding]
> * gen_mod_headers: add missing arch headers to tools [Kyle Harding]
> 
> ## meta-balena-2.66.0
> ### (2020-12-18)
> 
> * chrony: bump to version 4.0 [Mark Corbin]
> 
</details>

# v2.65.1+rev2
## (2021-01-11)

* linux-beagleboard: Update to 5.4.70-ti-r21, add HM3301 [Alexandru Costache]

# v2.65.1+rev1
## (2020-12-23)


<details>
<summary> Update meta-balena from 2.65.0 to 2.65.1 [Alexandru Costache] </summary>

> ## meta-balena-2.65.1
> ### (2020-12-17)
> 
> * u-boot: Add required configuration for BalenaOS environment [Alex Gonzalez]
> 
</details>

* linux-beagleboard: Revert "cpsw: fix min eth packet size" [Zahari Petkov]

# v2.65.0+rev2
## (2020-12-17)

* linux-beagleboard: Include beaglebone green gateway device tree [Alexandru Costache]

# v2.65.0+rev1
## (2020-12-16)

* Update balena-yocto-scripts to v1.9.0 [Alexandru Costache]

<details>
<summary> Update meta-balena from v2.58.3 to 2.65.0 [Alexandru Costache] </summary>

> ## meta-balena-2.65.0
> ### (2020-12-14)
> 
> * Update balena-supervisor from v12.1.1 to v12.2.11 [Miguel Casqueira]
> 
> ## meta-balena-2.64.4
> ### (2020-12-14)
> 
> * Add IPV6 multicast routing capability [Alex Gonzalez]
> 
> ## meta-balena-2.64.3
> ### (2020-12-11)
> 
> * Revert "resin-data.mount: Remove default dependencies" [Alex Gonzalez]
> * hostapp-update-hooks: Add supervisor database fix [Alex Gonzalez]
> * resin-supervisor: Make sure the database directory exists [Alex Gonzalez]
> * Correct the data partition mountpoint [Alex Gonzalez]
> 
> ## meta-balena-2.64.2
> ### (2020-12-10)
> 
> * meta-balena-common: kernel-resin: enable task-accounting by default [Joseph Kogut]
> * meta-balena-common: kernel-resin: create task-accounting config [Joseph Kogut]
> 
> ## meta-balena-2.64.1
> ### (2020-12-09)
> 
> * Update codeowners [Alex Gonzalez]
> 
> ## meta-balena-2.64.0
> ### (2020-12-07)
> 
> * rust: remove merged fix for TUNE_FEATURES parsing [Kyle Harding]
> * systemd: update patches to avoid fuzzy matching [Kyle Harding]
> * systemd: add missing udev rules [Kyle Harding]
> * systemd: avoid conflicts with timeinit package [Kyle Harding]
> * dropbear: prevent conflicts with openssh [Kyle Harding]
> * networkmanager: add bash requirement [Kyle Harding]
> * networkmanager: remove deprecated bluetooth inherit [Kyle Harding]
> * meta-balena-common: replace distro_features_check with features_check [Kyle Harding]
> * avahi: remove example services [Kyle Harding]
> * u-boot: disable u-boot-initial-env [Kyle Harding]
> * dnsmasq: fix build after y2038 changes in glib [Kyle Harding]
> * bluez5: replace experimental flag patch with service conf [Kyle Harding]
> * mtools: remove initialize-direntry patch [Kyle Harding]
> * meta-balena-dunfell: dunfell compatibility layer support [Kyle Harding]
> 
> ## meta-balena-2.63.1
> ### (2020-12-04)
> 
> * start-resin-supervisor: fix directory creation for 'balena start' [Mark Corbin]
> 
> ## meta-balena-2.63.0
> ### (2020-11-30)
> 
> * zram-swap-init: adjust default to lesser of 50%/4GB [Joseph Kogut]
> 
> ## meta-balena-2.62.2
> ### (2020-11-25)
> 
> * chrony: use a non-privileged UDP source port [Mark Corbin]
> 
> ## meta-balena-2.62.1
> ### (2020-11-19)
> 
> * supervisor: remove old/unnecessary balenaRootCA references [Matthew McGinn]
> 
> ## meta-balena-2.62.0
> ### (2020-11-13)
> 
> * systemd/timeinit: improve RTC handling at boot [Mark Corbin]
> * os-helpers: add support functions for system date/time [Mark Corbin]
> 
> ## meta-balena-2.61.3
> ### (2020-11-05)
> 
> * modemmanager: add u-blox-modeswitch scripts [Mark Corbin]
> 
> ## meta-balena-2.61.2
> ### (2020-11-05)
> 
> * Check the API for configuration changes once a day [Michal Toman]
> 
> ## meta-balena-2.61.1
> ### (2020-11-04)
> 
> * Enable kernel user space probes support [Alex Gonzalez]
> 
> ## meta-balena-2.61.0
> ### (2020-11-04)
> 
> 
> <details>
> <summary> Update balena-supervisor from v11.14.0 to v12.1.1 [Cameron Diver] </summary>
> 
>> ### balena-supervisor-12.1.1
>> #### (2020-10-28)
>> 
>> * Use root mount point to find device-type.json [Cameron Diver]
>> 
>> ### balena-supervisor-12.1.0
>> #### (2020-10-28)
>> 
>> * Change log source from docker to journalctl [Thomas Manning]
>> 
>> ### balena-supervisor-12.0.9
>> #### (2020-10-27)
>> 
>> * Change source of deviceType to device-type.json [Felipe Lalanne]
>> 
>> ### balena-supervisor-12.0.8
>> #### (2020-10-26)
>> 
>> * Fixed evaluating if updates are needed to reach target state [Miguel Casqueira]
>> 
>> ### balena-supervisor-12.0.7
>> #### (2020-10-19)
>> 
>> * Improved log message when networks do not match [Miguel Casqueira]
>> 
>> ### balena-supervisor-12.0.6
>> #### (2020-10-16)
>> 
>> * Fixes check allowing preloading in local (unmanaged) mode [ab77]
>> * Handle delete of multiple images with same dockerImageId [Felipe Lalanne]
>> 
>> ### balena-supervisor-12.0.5
>> #### (2020-10-14)
>> 
>> * Improve calculation for used system memory [Felipe Lalanne]
>> 
>> ### balena-supervisor-12.0.4
>> #### (2020-10-13)
>> 
>> * Don't require an existing supervisor container to sync [Cameron Diver]
>> 
>> ### balena-supervisor-12.0.3
>> #### (2020-10-12)
>> 
>> * Refactor system information filtering [Cameron Diver]
>> * tests: Clean up and consistify naming scheme [Cameron Diver]
>> 
>> ### balena-supervisor-12.0.2
>> #### (2020-10-12)
>> 
>> * Attempt a state report once every maxReportFrequency [Cameron Diver]
>> * Remove superfluous current state reporting code from api-binder [Cameron Diver]
>> 
>> ### balena-supervisor-12.0.1
>> #### (2020-10-12)
>> 
>> * Add features label `io.balena.features.journal-logs` [Thomas Manning]
>> 
>> ### balena-supervisor-12.0.0
>> #### (2020-09-29)
>> 
>> * version: drop SUPERVISOR_VERSION env var [Matthew McGinn]
>> 
>> ### balena-supervisor-11.14.8
>> #### (2020-09-29)
>> 
>> * Fix supervisor deadlock during migration [Felipe Lalanne]
>> 
>> ### balena-supervisor-11.14.7
>> #### (2020-09-25)
>> 
>> * Correctly evaluate if scheduledApply.delay is not set [Miguel Casqueira]
>> 
>> ### balena-supervisor-11.14.6
>> #### (2020-09-24)
>> 
>> * Fix config checks for ConfigFS backend [Felipe Lalanne]
>> 
>> ### balena-supervisor-11.14.5
>> #### (2020-09-24)
>> 
>> * mixpanel: superisor_version -> supervisor_version [Matthew McGinn]
>> 
>> ### balena-supervisor-11.14.4
>> #### (2020-09-18)
>> 
>> * api: Implement scoped Supervisor API keys [Rich Bayliss]
>> 
>> ### balena-supervisor-11.14.3
>> #### (2020-09-17)
>> 
>> * Clarify docs for toggling update lock override from dashboard [M. Casqueira]
>> 
>> ### balena-supervisor-11.14.2
>> #### (2020-09-15)
>> 
>> * Refactor extra_uEnv backend to match with more devices [Miguel Casqueira]
>> 
>> ### balena-supervisor-11.14.1
>> #### (2020-09-14)
>> 
>> * application-manager: Convert to a singleton [Rich Bayliss]
>> * device-state: Convert to a singleton [Rich Bayliss]
>> * api-binder: Convert to a singleton [Rich Bayliss]
>> 
> </details>
> 
> 
> ## meta-balena-2.60.1
> ### (2020-10-30)
> 
> * chrony: set the source UDP port for NTP requests to 123 [Mark Corbin]
> 
> ## meta-balena-2.60.0
> ### (2020-10-29)
> 
> * chrony: don't restore time from drift file or RTC [Mark Corbin]
> * systemd/timeinit: add fake.hwclock to maintain system time over reboots [Mark Corbin]
> * resin-mounts: add bind mount service for /etc/fake-hwclock [Mark Corbin]
> 
> ## meta-balena-2.59.0
> ### (2020-10-27)
> 
> * Add host extensions support [Alex Gonzalez]
> * packagegroup-resin: Add hostapp extensions update script [Alex Gonzalez]
> * hostapp-extensions-update: Add host extensions update script [Alex Gonzalez]
> * resin-vars: Parse the HOSTEXT_IMAGES variable from config.json [Alex Gonzalez]
> * docker-disk: Add the host extension images to the data partition [Alex Gonzalez]
> * docker-disk: Generalize hostapp platform variable [Alex Gonzalez]
> * initrdscripts: Busybox switch_root does not support -c argument [Alex Gonzalez]
> * resin-filesystem-expand: Omit fs check and resize if partition is mounted [Alex Gonzalez]
> * initrdscripts: Expand the resin-data filesystem [Alex Gonzalez]
> * initrdscripts: Add resin-data to fs UUID generation [Alex Gonzalez]
> * resin-data.mount: Remove default dependencies [Alex Gonzalez]
> * packagegroup-resin: Add independent mobynit package to image [Alex Gonzalez]
> * balena-engine: Do not build mobynit [Alex Gonzalez]
> * mobynit: Fix source directory [Alex Gonzalez]
> * mobynit: Separate recipe from balena-engine [Alex Gonzalez]
> 
> ## meta-balena-2.58.6
> ### (2020-10-15)
> 
> * readme: DCHP -> DHCP [Matthew McGinn]
> 
> ## meta-balena-2.58.5
> ### (2020-10-13)
> 
> * bootfiles: blacklist proper grub configuration backend [Matthew McGinn]
> 
> ## meta-balena-2.58.4
> ### (2020-10-05)
> 
> * docker-disk: Allow expanding data filesystem on 2TB disks [Alexandru Costache]
> 
</details>

# v2.58.3+rev4
## (2020-11-10)

* Update kernel for the beaglebones to version 5.4.70-ti-r19 [Florin Sarbu]

# v2.58.3+rev3
## (2020-10-14)

* Update kernel for the beaglebones to version 5.4.66-ti-r18 [Florin Sarbu]

# v2.58.3+rev2
## (2020-09-23)

* beaglebone: Remove duplicate instruction for power removal [Alexandru Costache]

# v2.58.3+rev1
## (2020-09-23)


<details>
<summary> Update meta-balena from v2.56.0 to v2.5.3 [Alexandru Costache] </summary>

> ## meta-balena-2.58.3
> ### (2020-09-18)
> 
> * Blacklist supervisor configuration backend files during HUP [Alex Gonzalez]
> 
> ## meta-balena-2.58.2
> ### (2020-09-17)
> 
> * hooks: fix up improperly named variable [Matthew McGinn]
> 
> ## meta-balena-2.58.1
> ### (2020-09-15)
> 
> * Wait for the root device to come up when necessary [Michal Toman]
> 
> ## meta-balena-2.58.0
> ### (2020-09-05)
> 
> * Respect balenaRootCA system-wide [Michal Toman]
> 
> ## meta-balena-2.57.1
> ### (2020-09-04)
> 
> * os-helpers-logging: Log to stderr rather than stdout [Michal Toman]
> 
> ## meta-balena-2.57.0
> ### (2020-09-04)
> 
> * Update libmbim to 1.24.2, libqmi to 1.26.0, modemmanager to 1.14.2 [Vicentiu Galanopulo]
> 
</details>

# v2.56.0+rev1
## (2020-09-21)


<details>
<summary> Update meta-balena from v2.54.2 to v2.56.0 [Alexandru Costache] </summary>

> ## meta-balena-2.56.0
> ### (2020-09-03)
> 
> 
> <details>
> <summary> Update balena-supervisor from v11.13.0 to v11.14.0 [Cameron Diver] </summary>
> 
>> ### balena-supervisor-11.14.0
>> #### (2020-09-03)
>> 
>> * Add device system information to state endpoint patch [Cameron Diver]
>> 
> </details>
> 
> 
> ## meta-balena-2.55.0
> ### (2020-09-03)
> 
> 
> <details>
> <summary> Update balena-supervisor from v11.12.4 to v11.13.0 [Cameron Diver] </summary>
> 
>> ### balena-supervisor-11.13.0
>> #### (2020-08-29)
>> 
>> * added support for configuring ODMDATA [Miguel Casqueira]
>> 
>> ### balena-supervisor-11.12.11
>> #### (2020-08-27)
>> 
>> * bug: Resolve mDNS API URLs [Rich Bayliss]
>> 
>> ### balena-supervisor-11.12.10
>> #### (2020-08-24)
>> 
>> * Preventing removing all configurations if device has no backends [Miguel Casqueira]
>> 
>> ### balena-supervisor-11.12.9
>> #### (2020-08-20)
>> 
>> * Don't enforce the vc4-fkms-v3d dtoverlay on rpi4 [Cameron Diver]
>> 
>> ### balena-supervisor-11.12.8
>> #### (2020-08-19)
>> 
>> 
>> <details>
>> <summary> Update dependencies [Pagan Gazzard] </summary>
>> 
>>> #### node-docker-delta-2.2.11
>>> ##### (2020-08-19)
>>> 
>>> * Add .versionbot/CHANGELOG.yml for nested changelogs [Pagan Gazzard]
>>> 
>>> #### node-docker-delta-2.2.10
>>> ##### (2020-08-05)
>>> 
>>> * Removed unused dependencies [Pagan Gazzard]
>>> * circleci: update docker [Pagan Gazzard]
>>> 
>>> #### docker-progress-4.0.3
>>> ##### (2020-08-17)
>>> 
>>> * Update to balena-lint 5.x [Pagan Gazzard]
>>> 
>>> #### docker-progress-4.0.2
>>> ##### (2020-08-17)
>>> 
>>> * Add .versionbot/CHANGELOG.yml for nested changelogs [Pagan Gazzard]
>>> 
>>> #### docker-progress-4.0.1
>>> ##### (2020-03-04)
>>> 
>>> * Update dependencies [Pagan Gazzard]
>>> 
>>> #### docker-progress-4.0.0
>>> ##### (2019-03-26)
>>> 
>>> * Detect error events in push/pull progress streams [Paulo Castro]
>>> 
>>> #### docker-toolbelt-3.3.10
>>> ##### (2020-08-19)
>>> 
>>> * Add .versionbot/CHANGELOG.yml for nested changelogs [Pagan Gazzard]
>>> 
>>> #### docker-toolbelt-3.3.9
>>> ##### (2020-08-17)
>>> 
>>> * Update to balena-lint 5.x [Pagan Gazzard]
>>> 
>>> #### livepush-3.5.1
>>> ##### (2020-08-19)
>>> 
>>> * Add .versionbot/CHANGELOG.yml for nested changelogs [Pagan Gazzard]
>>> 
>>> #### livepush-3.5.0
>>> ##### (2020-07-13)
>>> 
>>> * Allow setting ENV variables in the live image [Roman Mazur]
>>> * Bump dockerode types dependency [Roman Mazur]
>>> 
>>> #### livepush-3.4.1
>>> ##### (2020-05-05)
>>> 
>>> * Update README with information about live directives [Cameron Diver]
>>> 
>>> #### livepush-3.4.0
>>> ##### (2020-04-15)
>>> 
>>> * 🔭 Add a file watcher which can be used by library users [Cameron Diver]
>>> 
>>> #### resin-docker-build-1.1.6
>>> ##### (2020-08-19)
>>> 
>>> * Add .versionbot/CHANGELOG.yml for nested changelogs [Pagan Gazzard]
>>> 
>>> #### resin-docker-build-1.1.5
>>> ##### (2020-04-02)
>>> 
>>> * Update README with correct instantiation method [CameronDiver]
>>> 
>> </details>
>> 
>> 
>> ### balena-supervisor-11.12.7
>> #### (2020-08-19)
>> 
>> 
>> <details>
>> <summary> Update typed-error to 3.x [Pagan Gazzard] </summary>
>> 
>>> #### typed-error-3.2.1
>>> ##### (2020-08-05)
>>> 
>>> * Update dependencies [Pagan Gazzard]
>>> 
>>> #### typed-error-3.2.0
>>> ##### (2019-11-20)
>>> 
>>> * update deps and specify minimum engine requirements [Will Boyce]
>>> 
>>> #### typed-error-3.1.0
>>> ##### (2019-04-01)
>>> 
>>> * dev: Enforce prettier coding standards [Will Boyce]
>>> * npm: Update dependencies and remove `package-lock.json` [Will Boyce]
>>> * codeowners: Add top contributors @wrboyce, @Page-, and @dfunckt [Will Boyce]
>>> * versionbot: Add CHANGELOG.yml (for nested changelogs) [Will Boyce]
>>> 
>>> #### typed-error-3.0.2
>>> ##### (2018-11-01)
>>> 
>>> * Update README with new import style [CameronDiver]
>>> 
>>> #### typed-error-3.0.1
>>> ##### (2018-10-29)
>>> 
>>> * Update to typescript 3 [Pagan Gazzard]
>>> * Update dev dependencies [Pagan Gazzard]
>>> * Add node-10 to the circle test suite [Pagan Gazzard]
>>> 
>>> #### typed-error-3.0.0
>>> ##### (2018-04-17)
>>> 
>>> * Distribute generated typescript declaration [Will Boyce]
>>> * use circle for build/publish and add package-lock [Will Boyce]
>>> * add lint scripts/requirements [Will Boyce]
>>> * Remove `BaseError` class and  directly subclass `Error` [Will Boyce]
>>> * Update dependencies, clean up package/tsconfig [Will Boyce]
>>> 
>>> #### typed-error-2.0.1
>>> ##### (2017-12-15)
>>> 
>>> * Add LICENSE [Akis Kesoglou]
>>> 
>> </details>
>> 
>> 
>> ### balena-supervisor-11.12.6
>> #### (2020-08-18)
>> 
>> 
>> <details>
>> <summary> Update pinejs-client-request to 7.2.1 [Pagan Gazzard] </summary>
>> 
>>> #### pinejs-client-request-7.2.1
>>> ##### (2020-08-18)
>>> 
>>> 
>>> <details>
>>> <summary> Update dependencies [Pagan Gazzard] </summary>
>>> 
>>>> ##### pinejs-client-js-6.7.1
>>>> ###### (2020-08-12)
>>>> 
>>>> * Fix prepare $count typings [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-6.7.0
>>>> ###### (2020-08-12)
>>>> 
>>>> * Improve typings for request/post/put/patch/delete [Pagan Gazzard]
>>>> 
>>> </details>
>>> 
>>> 
>>> #### pinejs-client-request-7.2.0
>>> ##### (2020-08-12)
>>> 
>>> 
>>> <details>
>>> <summary> Update pinejs-client-core to 6.6.1 [Pagan Gazzard] </summary>
>>> 
>>>> ##### typed-error-3.2.1
>>>> ###### (2020-08-05)
>>>> 
>>>> * Update dependencies [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-6.6.1
>>>> ###### (2020-08-11)
>>>> 
>>>> * Fix typing when id is specified to be `AnyObject | undefined` [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-6.6.0
>>>> ###### (2020-08-11)
>>>> 
>>>> * Deprecate `$expand: { 'a/$count': {...} }` [Pagan Gazzard]
>>>> * Deprecate `resource: 'a/$count'` and update typings to reflect it [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-6.5.0
>>>> ###### (2020-08-11)
>>>> 
>>>> * Add `options: { $count: { ... } }` sugar for top level $count [Pagan Gazzard]
>>>> * Add `$expand: { a: { $count: { ... } } }` sugar for $count in expands [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-6.4.0
>>>> ###### (2020-08-11)
>>>> 
>>>> * Improve return typing of `subscribe` method [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-6.3.0
>>>> ###### (2020-08-11)
>>>> 
>>>> * Fix Poll.on typings [Pagan Gazzard]
>>>> * Improve return typing when id is passed to GET methods [Pagan Gazzard]
>>>> * Remove `PromiseResult` type, use `Promise<PromiseResultTypes>` instead [Pagan Gazzard]
>>>> * Remove `PromiseObj` type, use `Promise<{}>` instead [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-6.2.0
>>>> ###### (2020-08-10)
>>>> 
>>>> * Add `$filter: { a: { $count: 1 } }` sugar for $count in filters [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-6.1.2
>>>> ###### (2020-08-10)
>>>> 
>>>> * Remove redundant ParamsObj/SubscribeParamsObj types [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-6.1.1
>>>> ###### (2020-08-10)
>>>> 
>>>> * Make use of `mapObj` helper in more places [Pagan Gazzard]
>>>> * Use `Object.keys` in preference to `hasOwnProperty` where applicable [Pagan Gazzard]
>>>> 
>>> </details>
>>> 
>>> 
>> </details>
>> 
>> 
>> ### balena-supervisor-11.12.5
>> #### (2020-08-12)
>> 
>> * Refactor configurable backend class names [Miguel Casqueira]
>> 
> </details>
> 
> 
> ## meta-balena-2.54.3
> ### (2020-08-25)
> 
> * Pack /lib/vdso/Makefile in kernel-modules-headers [Vicentiu Galanopulo]
> 
</details>

# v2.54.2+rev1
## (2020-08-24)


<details>
<summary> Update meta-balena from v2.53.9 to v2.54.2 [Alexandru Costache] </summary>

> ## meta-balena-2.54.2
> ### (2020-08-12)
> 
> 
> <details>
> <summary> balena-supervisor: Update to v11.12.4 [Alex Gonzalez] </summary>
> 
>> ### balena-supervisor-11.12.4
>> #### (2020-08-12)
>> 
>> * bug: Firewall not blocking supervisor access from outside the device [Rich Bayliss]
>> 
>> ### balena-supervisor-11.12.3
>> #### (2020-08-11)
>> 
>> * bug: Allow DNS through firewall for local containers [Rich Bayliss]
>> 
> </details>
> 
> 
> ## meta-balena-2.54.1
> ### (2020-08-07)
> 
> * Package iwlwifi-cc-a0-48 firmware separately [Florin Sarbu]
> 
> ## meta-balena-2.54.0
> ### (2020-08-06)
> 
> 
> <details>
> <summary> Update balena-supervisor from v11.9.9 to v11.12.2 [Cameron Diver] </summary>
> 
>> ### balena-supervisor-11.12.2
>> #### (2020-08-05)
>> 
>> * Fix device-tag fetching function [Cameron Diver]
>> 
>> ### balena-supervisor-11.12.1
>> #### (2020-08-05)
>> 
>> 
>> <details>
>> <summary> Update resumable-request [Pagan Gazzard] </summary>
>> 
>>> #### resumable-request-2.0.1
>>> ##### (2020-08-05)
>>> 
>>> * Add .versionbot/CHANGELOG.yml for nested changelogs [Pagan Gazzard]
>>> * Optimize lodash dependency [Pagan Gazzard]
>>> 
>> </details>
>> 
>> 
>> ### balena-supervisor-11.12.0
>> #### (2020-08-05)
>> 
>> 
>> <details>
>> <summary> Update contrato to 0.5 [Pagan Gazzard] </summary>
>> 
>>> #### contrato-0.5.0
>>> ##### (2020-08-05)
>>> 
>>> * Remove handlebars-helpers to shrink bundle size [Pagan Gazzard]
>>> 
>>> #### contrato-0.4.0
>>> ##### (2020-08-04)
>>> 
>>> 
>>> <details>
>>> <summary> Update skhema to 5.x [Pagan Gazzard] </summary>
>>> 
>>>> ##### skhema-5.3.2
>>>> ###### (2020-08-04)
>>>> 
>>>> * Switch to typed-error [Pagan Gazzard]
>>>> 
>>>> ##### skhema-5.3.1
>>>> ###### (2020-08-04)
>>>> 
>>>> * Add .versionbot/CHANGELOG.yml for nested changelogs [Pagan Gazzard]
>>>> 
>>>> ##### skhema-5.3.0
>>>> ###### (2020-05-05)
>>>> 
>>>> * filter: Throw a custom error if the schema is invalid [Juan Cruz Viotti]
>>>> 
>>>> ##### skhema-5.2.9
>>>> ###### (2019-12-12)
>>>> 
>>>> * Add test to show .filter() not working correctly [StefKors]
>>>> * When combining with baseSchema merge enum with AND operator [StefKors]
>>>> 
>>>> ##### skhema-5.2.8
>>>> ###### (2019-11-27)
>>>> 
>>>> * Ensure values in "enum" are unique [Juan Cruz Viotti]
>>>> 
>>>> ##### skhema-5.2.7
>>>> ###### (2019-11-27)
>>>> 
>>>> * filter: Correctly handle "enum" inside "anyOf" [Juan Cruz Viotti]
>>>> 
>>>> ##### skhema-5.2.6
>>>> ###### (2019-11-19)
>>>> 
>>>> * merge: Be explicit about additionalProperties [Juan Cruz Viotti]
>>>> 
>>>> ##### skhema-5.2.5
>>>> ###### (2019-05-09)
>>>> 
>>>> * Add a resolver for the const keyword [Lucian]
>>>> 
>>>> ##### skhema-5.2.4
>>>> ###### (2019-04-15)
>>>> 
>>>> * Configure AJV instances with an LRU cache [Juan Cruz Viotti]
>>>> 
>>>> ##### skhema-5.2.3
>>>> ###### (2019-04-15)
>>>> 
>>>> * Set addUsedSchema to false in all AJV instances [Juan Cruz Viotti]
>>>> 
>>>> ##### skhema-5.2.2
>>>> ###### (2019-03-20)
>>>> 
>>>> * Fix bug in scoreMatch when handling arrays [Lucian]
>>>> 
>>>> ##### skhema-5.2.1
>>>> ###### (2019-03-19)
>>>> 
>>>> * Fix bad require name and .only in tests [Lucian]
>>>> 
>>>> ##### skhema-5.2.10
>>>> ###### (Invalid date)
>>>> 
>>>> * .filter(): Only match if the base schema matches [Lucian Buzzo]
>>>> 
>>>> ##### skhema-5.2.0
>>>> ###### (2019-03-19)
>>>> 
>>>> * Add ability to provide custom resolvers to merge() [Lucian]
>>>> 
>>>> ##### skhema-5.1.1
>>>> ###### (2019-02-08)
>>>> 
>>>> * Split up and optimize lodash dependencies [Lucian]
>>>> 
>>>> ##### skhema-5.1.0
>>>> ###### (2019-01-08)
>>>> 
>>>> * feature: Implement method for restricting a schema by another schema [Lucian Buzzo]
>>>> 
>>>> ##### skhema-5.0.0
>>>> ###### (Invalid date)
>>>> 
>>>> * Remove ability to add custom keywords or formats [Lucian]
>>>> 
>>>> ##### skhema-4.0.4
>>>> ###### (Invalid date)
>>>> 
>>>> * Improve performance of clone operations [Lucian]
>>>> 
>>>> ##### skhema-4.0.3
>>>> ###### (2018-12-10)
>>>> 
>>>> * Don't bust AJV cache [Lucian]
>>>> 
>>>> ##### skhema-4.0.2
>>>> ###### (2018-12-10)
>>>> 
>>>> * Add benchmark tests [Giovanni Garufi]
>>>> 
>>>> ##### skhema-4.0.1
>>>> ###### (2018-12-04)
>>>> 
>>>> * Recurse through nested `anyOf` statements when filtering [Lucian]
>>>> 
>>>> ##### skhema-4.0.0
>>>> ###### (2018-12-03)
>>>> 
>>>> * Treat undefined additionalProperties as true instead of false [Lucian]
>>>> 
>>>> ##### skhema-3.0.1
>>>> ###### (Invalid date)
>>>> 
>>>> * stryker: Increase test timeout [Juan Cruz Viotti]
>>>> * test: Configure Stryker for mutative testing [Juan Cruz Viotti]
>>>> 
>>>> ##### skhema-3.0.0
>>>> ###### (2018-11-29)
>>>> 
>>>> * Define additionalProperty inheritance in anyOf [Giovanni Garufi]
>>>> * Formalising filtering logic [Lucian]
>>>> * Added failing test case with mutation [Lucian]
>>>> 
>>>> ##### skhema-2.5.2
>>>> ###### (2018-11-07)
>>>> 
>>>> * hotfix: Make sure things that should be filtered are filtered [Juan Cruz Viotti]
>>>> 
>>>> ##### skhema-2.5.1
>>>> ###### (2018-11-06)
>>>> 
>>>> * filter: Force additionalProperties: true on match schemas [Juan Cruz Viotti]
>>>> 
>>>> ##### skhema-2.5.0
>>>> ###### (2018-10-16)
>>>> 
>>>> * Validate against just the schema if `options.schemaOnly` is true [Lucian Buzzo]
>>>> 
>>>> ##### skhema-2.4.1
>>>> ###### (2018-10-09)
>>>> 
>>>> * merge: When merging an empty array, return a wildcard schema [Lucian Buzzo]
>>>> 
>>>> ##### skhema-2.4.0
>>>> ###### (2018-10-09)
>>>> 
>>>> * validate: Make object optional [Lucian Buzzo]
>>>> 
>>> </details>
>>> 
>>> 
>>> #### contrato-0.3.1
>>> ##### (2020-08-04)
>>> 
>>> * Add .versionbot/CHANGELOG.yml for nested changelogs [Pagan Gazzard]
>>> 
>>> #### contrato-0.3.0
>>> ##### (2020-07-17)
>>> 
>>> * Add logical operator support in templates [Stevche Radevski]
>>> 
>> </details>
>> 
>> 
>> ### balena-supervisor-11.11.7
>> #### (2020-08-04)
>> 
>> * Bump elliptic from 6.5.2 to 6.5.3 [dependabot[bot]]
>> 
>> <details>
>> <summary> Update pinejs-client-request and make use of a named key [Pagan Gazzard] </summary>
>> 
>>> #### pinejs-client-request-7.1.0
>>> ##### (2020-07-28)
>>> 
>>> 
>>> <details>
>>> <summary> Update dependencies [Pagan Gazzard] </summary>
>>> 
>>>> ##### pinejs-client-js-6.1.0
>>>> ###### (2020-07-21)
>>>> 
>>>> * Add support for using named ids [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-6.0.1
>>>> ###### (2020-06-19)
>>>> 
>>>> * Drop unnecessary async from request() [Thodoris Greasidis]
>>>> 
>>> </details>
>>> 
>>> 
>>> #### pinejs-client-request-7.0.1
>>> ##### (2020-07-28)
>>> 
>>> * Increase default timeout to 59s [Pagan Gazzard]
>>> 
>> </details>
>> 
>> 
>> ### balena-supervisor-11.11.6
>> #### (2020-07-31)
>> 
>> * Fixes documentation - ping doesn't need apiKey and minor documentation formatting changes. [Nitish Agarwal]
>> 
>> ### balena-supervisor-11.11.5
>> #### (2020-07-31)
>> 
>> * Fixes #1299 v1 start/stop endpoint issue with service access. [Nitish Agarwal]
>> 
>> ### balena-supervisor-11.11.4
>> #### (2020-07-31)
>> 
>> * bug: Fix undefined containerId object [Rich Bayliss]
>> 
>> ### balena-supervisor-11.11.3
>> #### (2020-07-30)
>> 
>> * fix matching extra_uEnv backend with unsupported devices [Miguel Casqueira]
>> 
>> ### balena-supervisor-11.11.2
>> #### (2020-07-30)
>> 
>> * Fix an issue with reporting initial config using a stale target state [Pagan Gazzard]
>> 
>> ### balena-supervisor-11.11.1
>> #### (2020-07-29)
>> 
>> * fix up "atleast" -> "at least" [Matthew McGinn]
>> 
>> ### balena-supervisor-11.11.0
>> #### (2020-07-28)
>> 
>> * Support setting device/fleet configuration in extra_uEnv.txt [Miguel Casqueira]
>> 
>> ### balena-supervisor-11.10.0
>> #### (2020-07-24)
>> 
>> * Extract current state reporting to its own module [Pagan Gazzard]
>> 
>> ### balena-supervisor-11.9.10
>> #### (2020-07-23)
>> 
>> * log detection of changes to VPN status [dt-rush]
>> 
> </details>
> 
> 
> ## meta-balena-2.53.14
> ### (2020-08-06)
> 
> * balena-unique-key: Ensure config.json is synced after replacing [Alexandru Costache]
> 
> ## meta-balena-2.53.13
> ### (2020-08-05)
> 
> * flasher-register: if no supervisor information found, report null [Matthew McGinn]
> 
> ## meta-balena-2.53.12
> ### (2020-08-04)
> 
> * systemd: Set net.ipv4.conf.all.rp_filter in balena-os-sysctl [Alexandru Costache]
> 
> ## meta-balena-2.53.11
> ### (2020-07-30)
> 
> * Use a named key when querying for device by uuid [Pagan Gazzard]
> 
> ## meta-balena-2.53.10
> ### (2020-07-29)
> 
> * supervisor: allow supervisor updates without controlling the supervisor state [Matthew McGinn]
> 
</details>

# v2.53.9+rev1
## (2020-07-24)


<details>
<summary> Update meta-balena from v2.53.8 to v2.53.9 [Alexandru Costache] </summary>

> ## meta-balena-2.53.9
> ### (2020-07-23)
> 
> 
> <details>
> <summary> balena-supervisor: Update to v11.9.9 [Rich Bayliss] </summary>
> 
>> ### balena-supervisor-11.9.9
>> #### (2020-07-23)
>> 
>> * common: Fix bug where aliases might be undefined [Rich Bayliss]
>> 
> </details>
> 
> 
</details>

# v2.53.8+rev1
## (2020-07-23)


<details>
<summary> Update meta-balena from v2.53.6 to v2.53.8 [Florin Sarbu] </summary>

> ## meta-balena-2.53.8
> ### (2020-07-23)
> 
> * resin-supervisor: Create required directories before launch [Alex Gonzalez]
> 
> ## meta-balena-2.53.7
> ### (2020-07-23)
> 
> 
> <details>
> <summary> balena-supervisor: Update to v11.9.8 [Florin Sarbu] </summary>
> 
>> ### balena-supervisor-11.9.8
>> #### (2020-07-22)
>> 
>> * Bump lodash from 4.17.15 to 4.17.19 [dependabot[bot]]
>> 
>> ### balena-supervisor-11.9.7
>> #### (2020-07-22)
>> 
>> * docker-utils: Test network gateway determination logic [Rich Bayliss]
>> * Fix docker-util using incorrect reference for function [Miguel Casqueira]
>> 
> </details>
> 
> 
</details>

# v2.53.6+rev2
## (2020-07-23)

* Enable hciuart drivers to make bluetooth working again [Florin Sarbu]

# v2.53.6+rev1
## (2020-07-22)


<details>
<summary> Update meta-balena from v2.51.1 to v2.53.6 [Alexandru Costache] </summary>

> ## meta-balena-2.53.6
> ### (2020-07-21)
> 
> * recipes-containers/balena: Use separate service for loading healthcheck image [Alexandru Costache]
> 
> ## meta-balena-2.53.5
> ### (2020-07-21)
> 
> 
> <details>
> <summary> balena-supervisor: Update to v11.9.6 [Rich Bayliss] </summary>
> 
>> ### balena-supervisor-11.9.6
>> #### (2020-07-20)
>> 
>> * Fix purge and restart invocations by providing instanced apps [Cameron Diver]
>> * Fix purge invocations of new singletons [Cameron Diver]
>> 
>> ### balena-supervisor-11.9.5
>> #### (2020-07-14)
>> 
>> * Update ESR version information [Cameron Diver]
>> 
> </details>
> 
> 
> ## meta-balena-2.53.4
> ### (2020-07-21)
> 
> * Add support for aufs5 on kernel 5.x variants [Florin Sarbu]
> * Force choosing busybox-hwclock over util-linux-hwclock [Alex Gonzalez]
> 
> ## meta-balena-2.53.3
> ### (2020-07-16)
> 
> * provisioning: provide base supervisor_version during provision [Matthew McGinn]
> 
> ## meta-balena-2.53.2
> ### (2020-07-16)
> 
> * Add LZ4 support config for older kernels [Alexandru Costache]
> 
> ## meta-balena-2.53.1
> ### (2020-07-14)
> 
> * Remove unnecessary config.json keys [Pagan Gazzard]
> 
> ## meta-balena-2.53.0
> ### (2020-07-14)
> 
> * resin-supervisor: Create required directories before launch [Alex Gonzalez]
> * Rebrand custom resin logos [Alex Gonzalez]
> * plymouth: Remove patch that sets plymouth resin theme [Alex Gonzalez]
> * docker-disk: Update dind container to v19.03.10 [Michal Toman]
> * docker-disk: Update to still supported dind container [Gergely Imreh]
> * Use udev for setting up wlan power management [Michal Toman]
> * Use --mount instead of --volume for bind mounts to the supervisor container. [Robert Günzler]
> 
> ## meta-balena-2.52.7
> ### (2020-07-13)
> 
> 
> <details>
> <summary> Update balena-supervisor from v11.9.3 to v11.9.4 [Rich Bayliss] </summary>
> 
>> ### balena-supervisor-11.9.4
>> #### (2020-07-13)
>> 
>> * bug: Fix unhandled promise rejection [Rich Bayliss]
>> 
> </details>
> 
> 
> ## meta-balena-2.52.6
> ### (2020-07-13)
> 
> * Update to use api v6 and fix a quoting bug [Pagan Gazzard]
> 
> ## meta-balena-2.52.5
> ### (2020-07-10)
> 
> * Allow comments in iptables ruleset [Alex Gonzalez]
> 
> ## meta-balena-2.52.4
> ### (2020-07-09)
> 
> 
> <details>
> <summary> Update balena-supervisor from v11.4.10 to v11.9.3 [Cameron Diver] </summary>
> 
>> ### balena-supervisor-11.9.3
>> #### (2020-07-08)
>> 
>> * Fix bug where a promise was not resolved in db-format [Cameron Diver]
>> * Convert deviceConfig module to a singleton [Cameron Diver]
>> 
>> ### balena-supervisor-11.9.2
>> #### (2020-07-06)
>> 
>> * avahi: Control with HOST_DISCOVERABILITY [Cameron Diver]
>> 
>> ### balena-supervisor-11.9.1
>> #### (2020-07-01)
>> 
>> * firewall: Add Host Firewall functionality [Rich Bayliss]
>> 
>> ### balena-supervisor-11.9.0
>> #### (2020-06-23)
>> 
>> * Added support for configuring FDT directive in extlinux.conf [Miguel Casqueira]
>> 
>> ### balena-supervisor-11.8.4
>> #### (2020-06-22)
>> 
>> * state: Report device MAC address to the API [Rich Bayliss]
>> 
>> ### balena-supervisor-11.8.3
>> #### (2020-06-18)
>> 
>> 
>> <details>
>> <summary> Update pinejs-client-request to 7.x [Pagan Gazzard] </summary>
>> 
>>> #### pinejs-client-request-7.0.0
>>> ##### (2020-06-16)
>>> 
>>> * Empty commit to attempt republish [Pagan Gazzard]
>>> * Switch from bluebird-lru-cache to lru-cache for caching [Pagan Gazzard]
>>> * Update target to es2018 [Pagan Gazzard]
>>> * Remove bluebird dependency [Pagan Gazzard]
>>> * Convert to async/await [Pagan Gazzard]
>>> 
>>> <details>
>>> <summary> Update to pinejs-client-core 6.x [Pagan Gazzard] </summary>
>>> 
>>>> ##### pinejs-client-js-6.0.0
>>>> ###### (2020-06-04)
>>>> 
>>>> * Increase minimum es version to es2015 [Pagan Gazzard]
>>>> * Convert to async/await [Pagan Gazzard]
>>>> * Remove now unnecessary PinejsClientCoreFactory [Pagan Gazzard]
>>>> * Switch to using native promises [Pagan Gazzard]
>>>> * Drop support for deprecated request overrides [Pagan Gazzard]
>>>> * Drop support for deprecated `query` method [Pagan Gazzard]
>>>> * Drop support for deprecated string based requests [Pagan Gazzard]
>>>> * Use `;` for expand options instead of `&` [Pagan Gazzard]
>>>> 
>>> </details>
>>> 
>>> 
>>> #### pinejs-client-request-6.2.0
>>> ##### (2020-06-08)
>>> 
>>> * Lazy load bluebird-lru-cache and lodash [Pagan Gazzard]
>>> 
>>> #### pinejs-client-request-6.1.4
>>> ##### (2020-06-08)
>>> 
>>> * Convert some lodash usage to native versions [Pagan Gazzard]
>>> 
>>> #### pinejs-client-request-6.1.3
>>> ##### (2020-06-04)
>>> 
>>> * Remove unused dependencies [Pagan Gazzard]
>>> 
>>> #### pinejs-client-request-6.1.2
>>> ##### (2020-06-02)
>>> 
>>> 
>>> <details>
>>> <summary> Update dependencies [Pagan Gazzard] </summary>
>>> 
>>>> ##### pinejs-client-js-5.8.0
>>>> ###### (2020-05-29)
>>>> 
>>>> * Generate optional builds for es2015/es2018 as well as the default es5 [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-5.7.1
>>>> ###### (2020-05-25)
>>>> 
>>>> * Update dependencies [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-5.7.0
>>>> ###### (2020-04-15)
>>>> 
>>>> * Make transformGetResult a method , to ease overriding the get method [Thodoris Greasidis]
>>>> 
>>> </details>
>>> 
>>> 
>>> #### pinejs-client-request-6.1.1
>>> ##### (2020-03-19)
>>> 
>>> * Add linting [Pagan Gazzard]
>>> 
>>> #### pinejs-client-request-6.1.0
>>> ##### (2020-03-19)
>>> 
>>> * Move require-npm4-to-publish to dev dependencies [Pagan Gazzard]
>>> 
>>> <details>
>>> <summary> Update dependencies [Pagan Gazzard] </summary>
>>> 
>>>> ##### typed-error-3.2.0
>>>> ###### (2019-11-20)
>>>> 
>>>> * update deps and specify minimum engine requirements [Will Boyce]
>>>> 
>>>> ##### pinejs-client-js-5.6.11
>>>> ###### (2020-02-21)
>>>> 
>>>> * 🐛: Fix missing `deprecated.getStringParams` function [Andreas Fitzek]
>>>> 
>>>> ##### pinejs-client-js-5.6.10
>>>> ###### (2020-02-14)
>>>> 
>>>> * Update to resin-lint 3.x [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-5.6.9
>>>> ###### (2020-02-14)
>>>> 
>>>> * CircleCI: Remove deploy job as it's handled by balenaCI [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-5.6.8
>>>> ###### (2020-02-14)
>>>> 
>>>> * Add the missing `method` on the post method [Thodoris Greasidis]
>>>> 
>>>> ##### pinejs-client-js-5.6.7
>>>> ###### (2020-02-14)
>>>> 
>>>> * Deprecate request overrides [Pagan Gazzard]
>>>> * Deprecate queries using a string url [Pagan Gazzard]
>>>> * Deprecate `query` in favor of `get` [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-5.6.6
>>>> ###### (2020-02-14)
>>>> 
>>>> * Allow resource/$count in $filter [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-5.6.5
>>>> ###### (2020-01-30)
>>>> 
>>>> * Remove `defaults` helper in favour of `??` [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-5.6.4
>>>> ###### (2020-01-30)
>>>> 
>>>> * Avoid allocations when destroying a poll [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-5.6.3
>>>> ###### (2020-01-30)
>>>> 
>>>> * Improve `RawFilter` typing [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-5.6.2
>>>> ###### (2020-01-29)
>>>> 
>>>> * Update dependencies [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-5.6.1
>>>> ###### (2020-01-22)
>>>> 
>>>> * Switch most CODEOWNERS entries to a team [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-5.6.0
>>>> ###### (2019-07-12)
>>>> 
>>>> * Add 'upsert' method supporting natural keys, requires Pinejs ^10.19.1 [Thodoris Greasidis]
>>>> 
>>>> ##### pinejs-client-js-5.5.4
>>>> ###### (2019-06-18)
>>>> 
>>>> * Remove unnecessary `string` type that is handled by the `Params` type [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-5.5.3
>>>> ###### (2019-06-18)
>>>> 
>>>> * Use an .npmrc to prevent creating a package-lock on each install [Thodoris Greasidis]
>>>> 
>>>> ##### pinejs-client-js-5.5.2
>>>> ###### (2019-06-10)
>>>> 
>>>> * Add some type casting so that it compiles on TypeScript 3.5 [Thodoris Greasidis]
>>>> 
>>>> ##### pinejs-client-js-5.5.1
>>>> ###### (2019-05-15)
>>>> 
>>>> * Fix downstream declaration creation errors due to `Dictionary` [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-5.5.0
>>>> ###### (2019-05-15)
>>>> 
>>>> * Add a prepare method that prepares a query into a function [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-5.4.1
>>>> ###### (2019-05-10)
>>>> 
>>>> * Add CODEOWNERS [Gergely Imreh]
>>>> 
>>>> ##### pinejs-client-js-5.4.0
>>>> ###### (2019-05-10)
>>>> 
>>>> * Add support for parameter aliases in resource ids [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-5.3.10
>>>> ###### (2019-05-10)
>>>> 
>>>> * Deduplicate transformation of GET results [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-5.3.9
>>>> ###### (2019-05-10)
>>>> 
>>>> * Simplify how we expose types, which means `subscribe` is now exposed [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-5.3.8
>>>> ###### (2019-05-09)
>>>> 
>>>> * Add automatic formatting via prettier [Pagan Gazzard]
>>>> 
>>>> ##### pinejs-client-js-5.3.7
>>>> ###### (2019-05-08)
>>>> 
>>>> * Remove node 4 build, add node 12 [Pagan Gazzard]
>>>> * Add .versionbot/CHANGELOG.yml for downstream changelogs [Pagan Gazzard]
>>>> 
>>> </details>
>>> 
>>> 
>>> #### pinejs-client-request-6.0.3
>>> ##### (2020-01-22)
>>> 
>>> * Add CODEOWNERS [Pagan Gazzard]
>>> 
>>> #### pinejs-client-request-6.0.2
>>> ##### (2019-05-08)
>>> 
>>> * Add node 12 tests [Pagan Gazzard]
>>> * Add upstream for pinejs-client-core [Pagan Gazzard]
>>> 
>>> #### pinejs-client-request-6.0.1
>>> ##### (2019-04-23)
>>> 
>>> * Update target to es2016, part of/fixing the typed-error bump [Pagan Gazzard]
>>> 
>>> #### pinejs-client-request-6.0.0
>>> ##### (2019-04-17)
>>> 
>>> * typed-error: Update to v3.1.0 [Will Boyce]
>>> 
>> </details>
>> 
>> 
>> ### balena-supervisor-11.8.2
>> #### (2020-06-17)
>> 
>> * Make service-manager module a singleton [Cameron Diver]
>> * Make volume-manager module a singleton [Cameron Diver]
>> * Make network-manager module a singleton [Cameron Diver]
>> * Add supervisor upgrade document [Hugh Brown]
>> 
>> ### balena-supervisor-11.8.1
>> #### (2020-06-16)
>> 
>> * Update webpack dependencies [Pagan Gazzard]
>> 
>> ### balena-supervisor-11.8.0
>> #### (2020-06-16)
>> 
>> * Use API v6 [Akis Kesoglou]
>> 
>> ### balena-supervisor-11.7.3
>> #### (2020-06-15)
>> 
>> * Db-format module code fixups [Cameron Diver]
>> 
>> ### balena-supervisor-11.7.2
>> #### (2020-06-11)
>> 
>> * Add label to expose gpu to container [Robert Günzler]
>> 
>> ### balena-supervisor-11.7.1
>> #### (2020-06-11)
>> 
>> * Move database app processing out to its own module [Cameron Diver]
>> * Make target-state-cache a singleton [Cameron Diver]
>> 
>> ### balena-supervisor-11.7.0
>> #### (2020-06-10)
>> 
>> * Respect an initialDeviceName field in the config.json [Cameron Diver]
>> 
>> ### balena-supervisor-11.6.6
>> #### (2020-06-10)
>> 
>> * Make images module a singleton [Cameron Diver]
>> 
>> ### balena-supervisor-11.6.5
>> #### (2020-06-09)
>> 
>> * fix: API auth missing on state GET/PATCH [Rich Bayliss]
>> 
>> ### balena-supervisor-11.6.4
>> #### (2020-06-08)
>> 
>> * Refactored @ts-ignore to @ts-expect-error in test file [Miguel Casqueira]
>> 
>> ### balena-supervisor-11.6.3
>> #### (2020-06-08)
>> 
>> * Make logger module a singleton [Cameron Diver]
>> * Fix exponential backoff for state polling [Pagan Gazzard]
>> 
>> ### balena-supervisor-11.6.2
>> #### (2020-06-08)
>> 
>> * Make the event-tracker module a singleton [Cameron Diver]
>> 
>> ### balena-supervisor-11.6.1
>> #### (2020-06-05)
>> 
>> * Convert all test files to TS and add .spec to all filenames [Miguel Casqueira]
>> * fix: Pin alpine python version [Rich Bayliss]
>> 
>> ### balena-supervisor-11.6.0
>> #### (2020-06-03)
>> 
>> * Isolate target state fetching to its own module which emits on update [Pagan Gazzard]
>> 
>> ### balena-supervisor-11.5.3
>> #### (2020-06-02)
>> 
>> * Make docker module a singleton [Cameron Diver]
>> 
>> ### balena-supervisor-11.5.2
>> #### (2020-06-02)
>> 
>> * Make the config module a singleton [Cameron Diver]
>> 
>> ### balena-supervisor-11.5.1
>> #### (2020-06-01)
>> 
>> * Remove unused dependencies and dedupe [Cameron Diver]
>> 
>> ### balena-supervisor-11.5.0
>> #### (2020-05-29)
>> 
>> * Refactor device-state healthchecks to log reason for failure [Miguel Casqueira]
>> 
>> ### balena-supervisor-11.4.17
>> #### (2020-05-29)
>> 
>> * Update dependencies [Pagan Gazzard]
>> 
>> ### balena-supervisor-11.4.16
>> #### (2020-05-29)
>> 
>> * Make the db module a singleton [Cameron Diver]
>> 
>> ### balena-supervisor-11.4.15
>> #### (2020-05-26)
>> 
>> * Check for ApiError before using it as such [Cameron Diver]
>> 
>> ### balena-supervisor-11.4.14
>> #### (2020-05-21)
>> 
>> * check for 409 status code, rather than string matching uuid conflicts [Cameron Diver]
>> 
>> ### balena-supervisor-11.4.13
>> #### (2020-05-21)
>> 
>> * Use safeStateClone to avoid call-stack exceeding errors [Cameron Diver]
>> 
>> ### balena-supervisor-11.4.12
>> #### (2020-05-19)
>> 
>> * Improved handling of invalid appId in V2 state endpoint [Miguel Casqueira]
>> 
>> ### balena-supervisor-11.4.11
>> #### (2020-05-18)
>> 
>> * Switch to balenaApi for the state patch as patching cannot be cached [Pagan Gazzard]
>> 
> </details>
> 
> 
> ## meta-balena-2.52.3
> ### (2020-07-09)
> 
> * systemd: Simplify zram swap unit dependencies to avoid ordering cycle [Alex Gonzalez]
> 
> ## meta-balena-2.52.2
> ### (2020-07-06)
> 
> * kernel-resin: Make USB_SERIAL and USB_SERIAL_GENERIC built-ins [Alex Gonzalez]
> * kernel-resin: Fix configuration warnings from newer kernels [Alex Gonzalez]
> * kernel-resin: Update balena kernel configuration for updated engine [Alex Gonzalez]
> 
> ## meta-balena-2.52.1
> ### (2020-07-02)
> 
> * Fix up UUID variable when communicating with API [Matthew McGinn]
> 
> ## meta-balena-2.52.0
> ### (2020-06-30)
> 
> * Add compressed memory swap support [Alex Gonzalez]
> * systemd-zram-swap: Add compressed memory swap support [Alex Gonzalez]
> * kernel-resin: Built-in zram configuration [Alex Gonzalez]
> 
> ## meta-balena-2.51.8
> ### (2020-06-30)
> 
> * resin-ntp-config: merge 'burst' command with 'add server' line [Mark Corbin]
> 
> ## meta-balena-2.51.7
> ### (2020-06-25)
> 
> * resin-image: Install extra_uEnv.txt in boot partition [Alexandru Costache]
> 
> ## meta-balena-2.51.6
> ### (2020-06-25)
> 
> * initrdscripts: rootfs: Fix comparison to account for empty variable [Alex Gonzalez]
> * Use UUID rather than ID when communicating with API [Matthew McGinn]
> 
> ## meta-balena-2.51.5
> ### (2020-06-18)
> 
> * Set chrony default servers as pools [Matthew McGinn]
> 
> ## meta-balena-2.51.4
> ### (2020-06-15)
> 
> * Generate nested changelogs for balena-engine [Robert Günzler]
> 
> ## meta-balena-2.51.3
> ### (2020-06-10)
> 
> * Revert allowing local resin-supervisor image updates [Alex Gonzalez]
> 
> ## meta-balena-2.51.2
> ### (2020-06-08)
> 
> * Disable u-boot console, silence u-boot in production builds [Florin Sarbu]
> 
</details>

* Update kernel for the beaglebones to version 5.4.47-ti-r13 [Florin Sarbu]

# v2.51.1+rev2
## (2020-06-29)

* u-boot: Use meta-balena fs uuids for beaglebones [Alexandru Costache]

# v2.51.1+rev1
## (2020-06-26)

* Update balena-yocto-scripts to v1.8.0 [Alexandru Costache]

<details>
<summary> Update meta-balena from v2.48.0 to v2.51.1 [Alexandru Costache] </summary>

> ## meta-balena-2.51.1
> ### (2020-06-04)
> 
> * openvpn: Add runtime dependency on bash [Willem Remie]

> ## meta-balena-2.51.0
> ### (2020-06-03)
> 
> * balena-engine: Update to 19.03.13 [Robert Günzler]

> ## meta-balena-2.50.4
> ### (2020-06-02)
> 
> * Use correct SRC_URI for bindmount [Florin Sarbu]

> ## meta-balena-2.50.3
> ### (2020-06-01)
> 
> * os-helpers-fs: Fix shellcheck warnings [Alex Gonzalez]
> * Fallback to label root device matching to support devices with closed source bootloaders [Alex Gonzalez]
> * Fallback to labels and partlabels for devices with custom HUPs [Alex Gonzalez]

> ## meta-balena-2.50.2
> ### (2020-05-27)
> 
> * Enable the Analog Devices AD5446 kernel driver [Florin Sarbu]

> ## meta-balena-2.50.1
> ### (2020-05-21)
> 
> * networkmanager: Remove build warning [Alex Gonzalez]
> * Remove busybox-syslog to use only systemd's journald [Alex Gonzalez]
> * Update CODEOWNERS [Alex Gonzalez]
> * Backport NM patch for setting modem MTU correctly [Florin Sarbu]
> * update-resin-supervisor: short circuit if remote image cannot be fetched [Matthew McGinn]
> 
<details>
<summary> Update balena-supervisor from v11.4.1 to v11.4.10 [Cameron Diver] </summary>

>> ### balena-supervisor-11.4.10
>> #### (2020-05-18)
>> 
>> * Fix leftover spurious return from typescript conversion [Cameron Diver]

>> ### balena-supervisor-11.4.9
>> #### (2020-05-18)
>> 
>> * Catch errors in the target state poll so polling will always continue [Pagan Gazzard]

>> ### balena-supervisor-11.4.8
>> #### (2020-05-18)
>> 
>> * Avoid querying `instantUpdates` on every state poll [Pagan Gazzard]

>> ### balena-supervisor-11.4.7
>> #### (2020-05-16)
>> 
>> * Fix default request options [Pagan Gazzard]

>> ### balena-supervisor-11.4.6
>> #### (2020-05-15)
>> 
>> * Remove CoffeeScript tests and all CoffeeScript tools [Miguel Casqueira]

>> ### balena-supervisor-11.4.5
>> #### (2020-05-15)
>> 
>> * Update to @balena/lint 5.x [Pagan Gazzard]

>> ### balena-supervisor-11.4.4
>> #### (2020-05-15)
>> 
>> * Add a random offset to the poll interval with each poll [Cameron Diver]

>> ### balena-supervisor-11.4.3
>> #### (2020-05-14)
>> 
>> * Cache service names in local log backend [Cameron Diver]

>> ### balena-supervisor-11.4.2
>> #### (2020-05-13)
>> 
>> * Update engine information in package.json [Cameron Diver]
</details>

> 

> ## meta-balena-2.50.0
> ### (2020-05-13)
> 
> * Use /tmp as bootparam_root storage [Alex Gonzalez]
> * Update to libqmi v1.24.10 [Michal Toman]
> * Set rust 1.36 as the preferred rust version from meta-balena-common [Zubair Lutfullah Kakakhel]
> * Turn off wlan0 power save [Michal Toman]
> 
<details>
<summary> Update os-config from 1.1.3 to 1.1.4 [Alex Gonzalez] </summary>

>> ### os-config-1.1.4
>> #### (2020-05-13)
>> 
>> * versionbot: Add changelog yml file [Alex Gonzalez]
</details>

> 
> 
<details>
<summary> Update balena-supervisor from v11.3.0 to v11.4.1 [Cameron Diver] </summary>

>> ### balena-supervisor-11.4.1
>> #### (2020-05-12)
>> 
>> * Correctly check if value is a valid Integer [Miguel Casqueira]

>> ### balena-supervisor-11.4.0
>> #### (2020-05-12)
>> 
>> * Added endpoint to check if VPN is connected [Miguel Casqueira]

>> ### balena-supervisor-11.3.11
>> #### (2020-05-11)
>> 
>> * Fixed stubs for test suite [Miguel Casqueira]

>> ### balena-supervisor-11.3.10
>> #### (2020-05-11)
>> 
>> * Added more documentation to help new contributors start developing [Miguel Casqueira]

>> ### balena-supervisor-11.3.9
>> #### (2020-05-11)
>> 
>> * Fix dindctl script and update balenaos-in-container [Cameron Diver]

>> ### balena-supervisor-11.3.8
>> #### (2020-05-08)
>> 
>> * Remove unnecessary config.json keys [Pagan Gazzard]

>> ### balena-supervisor-11.3.7
>> #### (2020-05-08)
>> 
>> * CI: Use node 12 for tests to match runtime version [Pagan Gazzard]
>> * CI: Use docker 18 client to match remote [Pagan Gazzard]

>> ### balena-supervisor-11.3.6
>> #### (2020-05-07)
>> 
>> * Move SupervisorAPI state change logs to appropriate functions [Miguel Casqueira]

>> ### balena-supervisor-11.3.5
>> #### (2020-05-07)
>> 
>> * Add 20k-ultra to codeowners [Miguel Casqueira]

>> ### balena-supervisor-11.3.4
>> #### (2020-05-06)
>> 
>> * Don't use the openvpn alias to check VPN status [Cameron Diver]

>> ### balena-supervisor-11.3.3
>> #### (2020-05-06)
>> 
>> * Use lstat rather than stat to avoid error with symlinks in sync [Cameron Diver]

>> ### balena-supervisor-11.3.2
>> #### (2020-05-05)
>> 
>> * Move build files into build-conf and rename to build-utils [Cameron Diver]
>> * Fix knex migration require translation [Cameron Diver]

>> ### balena-supervisor-11.3.1
>> #### (2020-05-05)
>> 
>> * Remove legacy fallback to DROP rule in iptables [Cameron Diver]
>> * Add an ESTABLISHED flag to API iptables rules [Cameron Diver]
>> * Add ESR information to repo.yml [Cameron Diver]
</details>

> 
> 
<details>
<summary> Update balena-supervisor from v10.11.0 to v11.3.0 [Cameron Diver] </summary>

>> ### balena-supervisor-11.3.0
>> #### (2020-05-04)
>> 
>> * Added Bearer Authorization spec [Miguel Casqueira]

>> ### balena-supervisor-11.2.0
>> #### (2020-04-30)
>> 
>> * Added explanation README for running specific tests [Miguel Casqueira]

>> ### balena-supervisor-11.1.11
>> #### (2020-04-28)
>> 
>> * Remove coverage running and modules [Cameron Diver]

>> ### balena-supervisor-11.1.10
>> #### (2020-04-27)
>> 
>> * Update balena-register-device to fix provisioning [Cameron Diver]

>> ### balena-supervisor-11.1.9
>> #### (2020-04-22)
>> 
>> * Added protocol to semver.org link [Miguel Casqueira]

>> ### balena-supervisor-11.1.8
>> #### (2020-04-21)
>> 
>> * Actually remove dbus-native dependency [Cameron Diver]

>> ### balena-supervisor-11.1.7
>> #### (2020-04-21)
>> 
>> * Fix livepush predicate for POSIX sh in entry.sh [Cameron Diver]

>> ### balena-supervisor-11.1.6
>> #### (2020-04-21)
>> 
>> * Remove double printing of API status error [Cameron Diver]

>> ### balena-supervisor-11.1.5
>> #### (2020-04-15)
>> 
>> * ⤴️ Upgrade migrations to work with knex [Cameron Diver]
>> * 📄 Upgrade knex to avoid CVE-2019-10757 [Cameron Diver]

>> ### balena-supervisor-11.1.4
>> #### (2020-04-14)
>> 
>> * 🔎 Also watch js files during livepush [Cameron Diver]
>> * Clear changed files after successful livepush invocation [Cameron Diver]
>> * Use livepush commands for copying and running dev specific steps [Cameron Diver]

>> ### balena-supervisor-11.1.3
>> #### (2020-04-13)
>> 
>> * 🚀 Update supervisor to node12 [Cameron Diver]

>> ### balena-supervisor-11.1.2
>> #### (2020-04-13)
>> 
>> * Move from dbus-native to dbus [Cameron Diver]

>> ### balena-supervisor-11.1.1
>> #### (2020-04-10)
>> 
>> * Update copy-webpack-plugin [Pagan Gazzard]
>> * Update ts-loader to 6.x [Pagan Gazzard]
>> * Update fork-ts-checker-webpack-plugin to 4.x [Pagan Gazzard]

>> ### balena-supervisor-11.1.0
>> #### (2020-04-09)
>> 
>> * Support matching on device type within contracts [Cameron Diver]

>> ### balena-supervisor-11.0.9
>> #### (2020-04-08)
>> 
>> * Workaround a circular dependency [Pagan Gazzard]

>> ### balena-supervisor-11.0.8
>> #### (2020-04-08)
>> 
>> * Link sqlite with a system sqlite for quicker builds [Cameron Diver]

>> ### balena-supervisor-11.0.7
>> #### (2020-04-08)
>> 
>> * Convert application-manager.coffee to javascript [Pagan Gazzard]

>> ### balena-supervisor-11.0.6
>> #### (2020-04-08)
>> 
>> * Don't sync test files with livepush [Cameron Diver]

>> ### balena-supervisor-11.0.5
>> #### (2020-04-07)
>> 
>> * Add newTargetState event and use it for backup loading [Cameron Diver]

>> ### balena-supervisor-11.0.4
>> #### (2020-04-07)
>> 
>> * Don't wrap UpdatesLockedErrors with a detailed error [Cameron Diver]

>> ### balena-supervisor-11.0.3
>> #### (2020-04-07)
>> 
>> * Allow spaces in volume definitions [Cameron Diver]

>> ### balena-supervisor-11.0.2
>> #### (2020-04-06)
>> 
>> * Update to balena-register-device 6.0.1 [Pagan Gazzard]

>> ### balena-supervisor-11.0.1
>> #### (2020-04-06)
>> 
>> * Don't mangle names when minimising with webpack [Cameron Diver]

>> ### balena-supervisor-11.0.0
>> #### (2020-04-06)
>> 
>> * ⚡ Update synchronisation scripts for supervisor development [Cameron Diver]
>> * 🔧 Move to an alpine base image and drop i386-nlp support [Cameron Diver]

>> ### balena-supervisor-10.11.3
>> #### (2020-04-02)
>> 
>> * Convert test/18-startup.coffee to typescript [Pagan Gazzard]
>> * Convert test/19-compose-utils.coffee to javascript [Pagan Gazzard]
>> * Convert test/18-compose-network.coffee to javascript [Pagan Gazzard]
>> * Convert test/17-config-utils.spec.coffee to javascript [Pagan Gazzard]
>> * Convert test/16-ports.spec.coffee to typescript [Pagan Gazzard]
>> * Convert test/15-conversions.spec.coffee to javascript [Pagan Gazzard]
>> * Convert test/12-logger.spec.coffee to javascript [Pagan Gazzard]

>> ### balena-supervisor-10.11.2
>> #### (2020-03-31)
>> 
>> * Pass in deviceId when fetching device tags [Cameron Diver]

>> ### balena-supervisor-10.11.1
>> #### (2020-03-30)
>> 
>> * 🔧 Update resin-lint -> balena-lint in lintstaged [Cameron Diver]
</details>

> 
> 
<details>
<summary> Update os-config from 1.1.1 to 1.1.3 [Zubair Lutfullah Kakakhel] </summary>

>> ### os-config-1.1.3
>> #### (2020-03-24)
>> 
>> * Reorder module dependencies [Zahari Petkov]
>> * Pin serde version to v1.0.94 [Zahari Petkov]

>> ### os-config-1.1.2
>> #### (2020-02-04)
>> 
>> * Block on random until success [Zahari Petkov]
>> * Use parse_filters instead of parse [Zubair Lutfullah Kakakhel]
</details>

> 

> ## meta-balena-2.49.0
> ### (2020-05-01)
> 
> * balena-host: Ignore environment file if it does not exist [Alex Gonzalez]
> * Bump balena-engine to 18.09.17 [Robert Günzler]
> * networkmanager: Use absolute path in drop-in [Sven Schwermer]
> * Update ModemManager to v1.12.8 [Michal Toman]
> * Update balena-engine to 18.09.16 [Robert Günzler]
> * Add support for using udev by-state links in balenaOS [Alex Gonzalez]
> * Add initramfs module to regenerate default filesystem UUIDs [Alex Gonzalez]
> * Create udev state symlinks for all partitions [Alex Gonzalez]
> * initramfs-framework: Add os-helpers to module prepare [Alex Gonzalez]
> * Fix initramfs fsck warnings for the boot partition [Andrei Gherzan]
> * Switch to built-in FAT kernel configs [Andrei Gherzan]
> 
<details>
<summary> Update balena-supervisor from v10.8.0 to v10.11.0 [Cameron Diver] </summary>

>> ### balena-supervisor-10.11.0
>> #### (2020-03-30)
>> 
>> * Add BALENA_DEVICE_ARCH environment variable for containers [Cameron Diver]

>> ### balena-supervisor-10.10.15
>> #### (2020-03-30)
>> 
>> * Don't throw an error when getting an unhealthy state [Cameron Diver]

>> ### balena-supervisor-10.10.14
>> #### (2020-03-28)
>> 
>> * Convert src/device-api/common.coffee to javascript [Pagan Gazzard]

>> ### balena-supervisor-10.10.13
>> #### (2020-03-27)
>> 
>> * Switch to mz for the proxyvisor [Pagan Gazzard]
>> * Convert proxyvisor to javascript [Pagan Gazzard]

>> ### balena-supervisor-10.10.12
>> #### (2020-03-26)
>> 
>> * Remove unnecessary code from application-manager [Pagan Gazzard]
>> * Switch to a named export for application-manager [Pagan Gazzard]

>> ### balena-supervisor-10.10.11
>> #### (2020-03-25)
>> 
>> * Convert device-api/v1 to javascript [Pagan Gazzard]

>> ### balena-supervisor-10.10.10
>> #### (2020-03-24)
>> 
>> * Update livepush [Cameron Diver]

>> ### balena-supervisor-10.10.9
>> #### (2020-03-24)
>> 
>> * Add type checking for javascript files [Pagan Gazzard]

>> ### balena-supervisor-10.10.8
>> #### (2020-03-24)
>> 
>> * Pin resin-cli-visuals to avoid build error of lzma-native [Cameron Diver]
>> * Update dependencies [Cameron Diver]

>> ### balena-supervisor-10.10.7
>> #### (2020-03-24)
>> 
>> * Avoid any transpilation of node_modules [Pagan Gazzard]

>> ### balena-supervisor-10.10.6
>> #### (2020-03-24)
>> 
>> * Add transpilation for javascript files to ease node 6 compatibility [Pagan Gazzard]
>> * Add a precheck that linting/tests work on node 10 [Pagan Gazzard]
>> * Update to balena-lint and enable javascript linting [Pagan Gazzard]

>> ### balena-supervisor-10.10.5
>> #### (2020-03-23)
>> 
>> * Tests: Add missing await [Pagan Gazzard]

>> ### balena-supervisor-10.10.4
>> #### (2020-03-16)
>> 
>> * docs: Clarify update locks for multicontainer applications [Gareth Davies]

>> ### balena-supervisor-10.10.3
>> #### (2020-03-16)
>> 
>> * logging: fix up some typos [Matthew McGinn]

>> ### balena-supervisor-10.10.2
>> #### (2020-03-16)
>> 
>> * Bump acorn from 5.7.3 to 5.7.4 [dependabot[bot]]

>> ### balena-supervisor-10.10.1
>> #### (2020-03-13)
>> 
>> * Update dependencies [Pagan Gazzard]

>> ### balena-supervisor-10.10.0
>> #### (2020-03-06)
>> 
>> * Allow semver comparison on l4t versions in contracts [Cameron Diver]
>> * Allow l4t versions with three numbers as well as two [Cameron Diver]

>> ### balena-supervisor-10.9.2
>> #### (2020-03-05)
>> 
>> * config: Support loading SSDT via ConfigFS [Rich Bayliss]

>> ### balena-supervisor-10.9.1
>> #### (2020-02-25)
>> 
>> * Convert device-state module to typescript [Cameron Diver]
>> * Improve application-manager typings [Cameron Diver]
>> * Improve and extend internal typings [Cameron Diver]

>> ### balena-supervisor-10.9.0
>> #### (2020-02-24)
>> 
>> * Add a containerId request parameter for journal-logs api endpoint, and pass it along to journalctl process options. [Ivan]
</details>

> 
</details>

# v2.48.0+rev2
## (2020-05-12)

* Set private to false in .coffee files for the public device types [Florin Sarbu]

# v2.48.0+rev1
## (2020-03-25)

* Update balena-yocto-scripts to v1.5.6 [Florin Sarbu]

<details>
<summary> Update meta-balena from v2.47.1 to v2.48.0 [Florin Sarbu] </summary>

> ## meta-balena-2.48.0
> ### (2020-03-20)
> 
> * Add the linux-firmware recipe from the Poky zeus-22.0.1 release and package various iwlwifi firmware separately [Florin Sarbu]
> * Add regulatory.db (Wireless Central Regulatory Domain Database) to rootfs so kernel versions >= v4.15 can load it (for Poky Thud and Warrior based board) [Florin Sarbu]
> * Do not send SIGKILL directly to user containers (set KillMode=process in balena.service) [Florin Sarbu]
> * Update balena-supervisor from  to v10.8.0 [Cameron Diver]
> * Update config.json documentation for disabling NM connectivity checks [Gareth Davies]
> * Fix a typo in a NetworkManager plugin path [Zubair Lutfullah Kakakhel]
> * Remove unnecessary openvpn v2.4.4 recipe in meta-resin-pyro. [Zubair Lutfullah Kakakhel]
> * Use a weak default assignment in a recipe for customer trying to override a variable in his layer [Zubair Lutfullah Kakakhel]
</details>

# v2.47.1+rev2
## (2020-03-06)

* linux-beagleboard: Prevent kernel panic if rtc failed [Alexandru Costache]

# v2.47.1+rev1
## (2020-02-13)


<details>
<summary> Update meta-balena from v2.47.0 to v2.47.1 [Florin Sarbu] </summary>

> ## meta-balena-2.47.1
> ### (2020-02-13)
> 
> * Affects 2.45+ on all devices. Fix dangling sshd services on failed connections that would grow and cause cpu load to keep rising. See issue 1837 in meta-balena for more detail. [Zubair Lutfullah Kakakhel]
</details>

# v2.47.0+rev1
## (2020-02-11)

* Update balena-yocto-scripts to v1.5.4 [Florin Sarbu]

<details>
<summary> Update meta-balena from v2.46.1 to v2.47.0 [Florin Sarbu] </summary>

> ## meta-balena-2.47.0
> ### (2020-01-29)
> 
> * Update usb-modeswitch-data to version 20191128 [Florin Sarbu]
> * Update usb-modeswitch to version 2.5.2 [Florin Sarbu]
> * Update to ModemManager v1.12.4 [Florin Sarbu]
> * Update libmbim to version 1.22.0 [Florin Sarbu]
> * Update libqmi to version 1.24.4 [Florin Sarbu]
> * Add periodic vacuuming of journald log files [Alex Gonzalez]
> * No user impact. Increase limit for maximum initramfs size from 12MB to 32MB. This helps reduce unnecessary overrides in integration layers. [Zubair Lutfullah Kakakhel]
> * Match licenses with license files. [Alex Gonzalez]
> * Enable sixaxis support in bluez5 [Alexis Svinartchouk]
> * Addressing review comments [Gareth Davies]
> * Update config.json documentation [Gareth Davies]
> * Increase DNS clients timeout to 15 seconds [Alex Gonzalez]
> * Fix supervisor nested changelogs [Zubair Lutfullah Kakakhel]
> * Enable memory overcommit [Alex Gonzalez]
> * Add uinput kernel module [Florin Sarbu]
> * Make sure to add in rootfs the wifi firmware for wl18xx [Florin Sarbu]
> * Add supported USB WiFi dongle [Vicentiu Galanopulo]

> ## meta-balena-2.46.2
> ### (2020-01-17)
> 
> * Americanize the README.md [Matthew McGinn]
</details>

# v2.46.1+rev4
## (2020-02-11)

* Update meta-rust to include 1.36 [Zubair Lutfullah Kakakhel]

# v2.46.1+rev3
## (2020-02-10)

* Remove unnecessary override of IMAGE_ROOTFS_MAXSIZE [Zubair Lutfullah Kakakhel]

# v2.46.1+rev2
## (2020-01-15)

* Change the state to 'released' in the coffee files [Vicentiu Galanopulo]

# v2.46.1+rev1
## (2020-01-04)


<details>
<summary> Update meta-balena from v2.45.0 to v2.46.1 [Florin Sarbu] </summary>

> ## meta-balena-2.46.1
> ### (2020-01-01)
> 
> * Disable by default the option to stop u-boot autoboot by pressing CTRL+C in all OS versions [Florin Sarbu]
> * Increase NTP polling time to around 4.5 hours. [Alex Gonzalez]
> * Disable the option to stop u-boot autoboot by pressing CTRL+C in production OS version [Florin Sarbu]

> ## meta-balena-2.46.0
> ### (2019-12-23)
> 
> * Update to ModemManager v1.12.2 [Zahari Petkov]
> * Update libmbim to version 1.20.2 [Zahari Petkov]
> * Update libqmi to version 1.24.2 [Zahari Petkov]
> * Update balena-supervisor to v10.6.27 [Cameron Diver]
> * Tweak how the flasher asserts that internal media is valid for being installed balena OS on [Florin Sarbu]
> * Remove networkmanager stale temporary files at startup [Alex Gonzalez]
> * networkmanager: Rework patches to remove fuzzing [Alex Gonzalez]
> * Update openvpn to v2.4.7 [Will Boyce]
> * Enable kernel configs for USB_SERIAL, USB_SERIAL_PL2303 and HFS for all devices [Zubair Lutfullah Kakakhel]
> * image-resin.bbclass: Mark do_populate_lic_deploy with nostamp [Zubair Lutfullah Kakakhel]
> * Namespace the hello-world healthcheck image [Zubair Lutfullah Kakakhel]
> * Update balena-supervisor to v10.6.17 [Cameron Diver]
> * Update balena-supervisor to v10.6.13 [Cameron Diver]
> * Update CODEOWNERS [Zubair Lutfullah Kakakhel]

> ## meta-balena-2.45.1
> ### (2019-11-21)
> 
> * Fix for a race condition where occasionally the supervisor might not be able to come up during boot. Also can be caused by using io.balena.features.balena-socket and app container restart always policy. Affects meta-balena 2.44.0 and 2.45.0. To be fixed in 2.44.1 and 2.46.0 [Zubair Lutfullah Kakakhel]
> * Rename resin to balena where possible [Pagan Gazzard]
> * Add leading new line for PACKAGE_INSTALL variable [Vicentiu Galanopulo]
> * Set `net.ipv4.ip_local_port_range` to recommended range (49152-65535) [Will Boyce]
> * No user impact, subtle fix in rollback version checks [Zubair Lutfullah Kakakhel]
</details>

# v2.45.0+rev2
## (2019-11-19)

* Update balena-yocto-scripts to v1.5.2 [Florin Sarbu]

# v2.45.0+rev1
## (2019-11-12)

* Update to thud [Vicentiu Galanopulo]

<details>
<summary> Update meta-balena from v2.43.0 to v2.45.0 [Vicentiu Galanopulo] </summary>

> ## meta-balena-2.45.0
> ### (2019-10-30)
> 
> * Increase persistent journal size to 32M [Will Boyce]
> * Move persistent logs from state to data partition [Will Boyce]
> * Add wpa-supplicant recipe and update to v2.9 [Will Boyce]
> * Improve robustness by making variou services restart if they stop for some reason [Zubair Lutfullah Kakakhel]
> * Build net/dummy as module [Alexandru Costache]

> ## meta-balena-2.44.0
> ### (2019-10-03)
> 
> * Make uboot dev images autoboot delay build time configurable. Default is no delay [Zubair Lutfullah Kakakhel]
> * Reduce systemd logging level from info to notice [Zubair Lutfullah Kakakhel]
> * resin-supervisor: Expose container ID via env variable [Roman Mazur]
> * kernel-devsrc: Copy vdso.lds.S file in source archive if available [Sebastian Panceac]
> * Disable PasswordAuthentication in sshd in production images as an extra precautionary measure. [Zubair Lutfullah Kakakhel]
> * Update balena-engine to 18.9.10 [Robert Günzler]
> * hostapp-update-hooks: Filter out automount for inactive sysroot [Alexandru Costache]
> * Add support for hooks 2.0 enabling finer granularity during HostOS updates. [Zubair Lutfullah Kakakhel]
> * Update balena-supervisor to v10.3.7 [Cameron Diver]
> * Add support for balena cloud SSH public keys [Andrei Gherzan]
> * Map any user to root using libnss-ato [Andrei Gherzan]
> * Add option to disable kernel headers from being built. [Zubair Lutfullah Kakakhel]
</details>

# v2.43.0+rev4
## (2019-10-10)

* Update balena-yocto-scripts to v1.4.0 [Florin Sarbu]

# v2.43.0+rev3
## (2019-09-30)

* Update balena-yocto-scripts to v1.3.8 [Zubair Lutfullah Kakakhel]

# v2.43.0+rev2
## (2019-09-24)

* Patches for TCP-based remote denial of service vulnerabilities [Vicentiu Galanopulo]

# v2.43.0+rev1
## (2019-09-23)


<details>
<summary> Update meta-balena from v2.41.1 to v2.43.0 [Florin Sarbu] </summary>

> ## meta-balena-2.43.0
> ### (2019-09-13)
> 
> * Update NetworkManager to 1.20.2 [Andrei Gherzan]
> * Update ModemManager to 1.10.6 [Andrei Gherzan]

> ## meta-balena-2.42.0
> ### (2019-09-13)
> 
> * A small fix in initramfs when /dev/console is invalid due to whatever reason [Zubair Lutfullah Kakakhel]
> * Add automated testing for external kernel module header tarballs [Zubair Lutfullah Kakakhel]
> * Make sure correct utsrelease.h is packaged [Zubair Lutfullah Kakakhel]
> * Fix a bug where application containers with new systemd versions were failing to start in cases. Switch to systemd cgroup driver in balenaEngine [Zubair Lutfullah Kakakhel]
</details>

# v2.41.1+rev2
## (2019-09-16)

* Replace 'resin' with 'balena' and update pull request rules. [Rafq77]

# v2.41.1+rev1
## (2019-09-11)

* Update the balena-yocto-scripts submodule to v1.3.7 [Florin Sarbu]

<details>
<summary> Update meta-balena from v2.40.0 to v2.41.1 [Florin Sarbu] </summary>

> ## meta-balena-2.41.1
> ### (2019-09-03)
> 
> * Update ModemManager to version 1.10.4 [Florin Sarbu]
> * Fix for some innocous systemd tmpfile warnings /var/run -> /run ones [Zubair Lutfullah Kakakhel]
> * Fix for rollbacks where the inactive partition mount was unavailable when altboot triggered [Zubair Lutfullah Kakakhel]
> * kernel-resin: Enable FTDI USB-serial convertors driver [Sebastian Panceac]

> ## meta-balena-2.41.0
> ### (2019-08-22)
> 
> * Fix a hang in initramfs for warrior production images [Zubair Lutfullah Kakakhel]
> * Update balena-engine to 18.09.8 [Robert Günzler]
> * Avoid overlayfs mounts in poky's volatile-binds [Andrei Gherzan]
</details>

# v2.40.0+rev1
## (2019-08-17)


<details>
<summary> Update meta-balena from v2.38.3 to v2.40.0 [Florin Sarbu] </summary>

> ## meta-balena-2.40.0
> ### (2019-08-14)
> 
> * Update balena-supervisor to v10.2.2 [Cameron Diver]
> * Workaround for a cornercase bug in PersistentLogging where journalctl filled the state partition. Vacuum the journal on boot. [Zubair Lutfullah Kakakhel]

> ## meta-balena-2.39.0
> ### (2019-07-31)
> 
> * usb-modeswitch-data: Switch Huawei E3372 12d1:1f01 to mbim mode [Alexandru Costache]
> * Fix rollback altboots to prevent good reboots by supervisor triggering rollback. [Zubair Lutfullah Kakakhel]
> * Devices using u-boot. Remove any BOOTDELAY for production images. Add a 2 seconds delay for development images [Zubair Lutfullah Kakakhel]
> * Devices using u-boot. Enable CONFIG_CMD_SETEXPR for all devices. Required for rollbacks to work [Zubair Lutfullah Kakakhel]
> * Devices using u-boot. Enable rollback-altboot by handling bootcount via meta-balena. [Zubair Lutfullah Kakakhel]
> * Production Devices using u-boot. Enable CONFIG_RESET_TO_RETRY to reset a device in case it drops into a u-boot shell [Zubair Lutfullah Kakakhel]
> * Remove confusing networkmanager https connectivity warning [Zubair Lutfullah Kakakhel]
> * Increase fs.inotify.max_user_instances to 512 [Zubair Lutfullah Kakakhel]
> * Update balena-supervisor to v10.0.3 [Cameron Diver]
> * Fix balena hello-world healthcheck [Zubair Lutfullah Kakakhel]
> * Add nf_table kernel modules [Zubair Lutfullah Kakakhel]
> * hostapp-update-hooks: Use correct source for inactive sysroot [Alexandru Costache]
> * Add extra healthcheck to balena service. It will spin up a hello-world container as well [Zubair Lutfullah Kakakhel]
> * Update balena-supervisor to v9.18.8 [Cameron Diver]
> * image-resin.bbclass: fixed a typo [Kyle Harding]
> * kernel-resin: Add support for CH340 family of usb-serial adapters [Sebastian Panceac]
> * resin-proxy-config: add missing reserved ip ranges to default noproxy [Will Boyce]
> * Reduce data partition size from 1G to 192M [Zubair Lutfullah Kakakhel]
</details>

# v2.38.3+rev2
## (2019-08-14)

* linux-beagleboard: Switch UART driver to CONFIG_SERIAL_OMAP [Sebastian Panceac]

# v2.38.3+rev1
## (2019-07-16)

* Update the balena-yocto-scripts submodule to v1.3.5 [Florin Sarbu]

<details>
<summary> Update meta-balena from v2.38.2 to v2.38.3 [Florin Sarbu] </summary>

> ## meta-balena-2.38.3
> ### (2019-07-10)
> 
> * resin-proxy-config: fix up incorrect bash subshell command [Matthew McGinn]
</details>

# v2.38.2+rev2
## (2019-07-10)

* Rename beaglebone-black.svg to beaglebone.svg [Florin Sarbu]

# v2.38.2+rev1
## (2019-07-10)

* Update the balena-yocto-scripts submodule to v1.2.3 [Florin Sarbu]

<details>
<summary> Update meta-balena from v2.38.0 to v2.38.2 [Florin Sarbu] </summary>

> ## meta-balena-2.38.2
> ### (2019-06-27)
> 
> * Update to kernel-modules-headers v0.0.20 to fix missing target modpost binary on kernel 5.0.3 [Florin Sarbu]
> * Update to kernel-modules-headers v0.0.19 to fix target objtool compile issue on kernel 5.0.3 [Florin Sarbu]

> ## meta-balena-2.38.1
> ### (2019-06-20)
> 
> * Add warrior to compatible layers for meta-balena-common [Florin Sarbu]
> * Fix image-resin.bbclass to be able to use deprecated layers [Andrei Gherzan]
> * Fix kernel-devsrc on thud when kernel version < 4.10 [Andrei Gherzan]
</details>

# v2.38.0+rev1
## (2019-06-19)

* Update meta-balena from v2.37.0 to v2.38.0 [Sebastian Panceac]

<details>
<summary> View details </summary>

## meta-balena-2.38.0
### (2019-06-14)

* Fix VERSION_ID os-release to be semver complient [Andrei Gherzan]
* Introduce META_BALENA_VERSION in os-release [Andrei Gherzan]
* Fix a case where changes to u-boot were not regenerating the config file at build time and using stale values. [Zubair Lutfullah Kakakhel]
* Use all.rp_filter=2 as the default value in balenaOS [Andrei Gherzan]
* Persist bluetooth storage data over reboots [Andrei Gherzan]
* Drop support for morty and krogoth Yocto versions [Andrei Gherzan]
* Add Yocto Warrior support [Zubair Lutfullah Kakakhel]
* Set both VERSION_ID and VERSION in os-release to host OS version [Andrei Gherzan]
* Bump balena-engine to 18.9.6 [Zubair Lutfullah Kakakhel]
* Downgrade balena-supervisor to v9.15.7 [Andrei Gherzan]
* Switch from dropbear to openSSH [Andrei Gherzan]
* Rename meta-resin-common to meta-balena-common [Andrei Gherzan]
* Add wifi firmware for rtl8192su [Zubair Lutfullah Kakakhel]
</details>

# v2.37.0+rev5
## (2019-06-19)

* linux-beagleboard: Power cycle SD card at boot on Beagleboard-XM [Sebastian Panceac]

# v2.37.0+rev4
## (2019-06-07)

* Use the os_cmdline uboot support provided by meta-balena [Andrei Gherzan]

# v2.37.0+rev3
## (2019-06-06)

* u-boot: Integrate Balena env for Beagleboard-XM [Sebastian Panceac]

# v2.37.0+rev2
## (2019-06-03)

* Add icon for Beagleboard-XM board [Sebastian Panceac]

# v2.37.0+rev1
## (2019-05-31)

* resin-image: Add support for Beagleboard-XM [Sebastian Panceac]
* Add support for Beagleboard-XM board [Sebastian Panceac]
* linux-beagleboard: Add support for Beagleboard-XM [Sebastian Panceac]
* Update meta-balena from v2.33.0 to v2.37.0 [Sebastian Panceac]

<details>
<summary> View details </summary>

## meta-balena-2.37.0
### (2019-05-29)

* Update balena-supervisor to v9.15.8 [Cameron Diver]
* kernel-modules-headers: Update to v0.0.18 [Andrei Gherzan]
* os-config: Update to v1.1.1 to fix mDNS [Andrei Gherzan]
* Fix busybox nslookup mdns lookups [Andrei Gherzan]
* Update balena-supervisor to v9.15.4 [Cameron Diver]
* Improve logging and version comparison in linux-firmware cleanup class [Andrei Gherzan]
* Sync ModemManager recipe with upstream [Andrei Gherzan]
* Update NetworkManager to 1.18.0 [Andrei Gherzan]

## meta-balena-2.36.0
### (2019-05-20)

* Cleanup old versions of iwlwifi firmware files in Yocto Thud [Florin Sarbu]

## meta-balena-2.35.0
### (2019-05-18)

* Update kernel-module-headers to version v0.0.16 [Florin Sarbu]
* Add uboot support for unified kernel cmdline arguments [Andrei Gherzan]
* Switch flasher detection in initramfs to flasher boot parameter [Andrei Gherzan]
* Update balena-supervisor to v9.15.0 [Cameron Diver]
* Improve boot speed by only mounting the inactive partition when needed [Zubair Lutfullah Kakakhel]
* Fix openssl dependency of balena-unique-key [Andrei Gherzan]
* Do not spawn getty in production images [Florin Sarbu]

## meta-balena-2.34.1
### (2019-05-14)

* Update balena-supervisor to v9.14.10 [Cameron Diver]

## meta-balena-2.34.0
### (2019-05-10)

* Add support to update a connectivity section in NetworkManager via config.json [Zubair Lutfullah Kakakhel]
* systemd: Fix journald configuration file [Andrei Gherzan]
* Add --max-download-attempts=10 to balenaEngine service to improve performance on shaky networks [Zubair Lutfullah Kakakhel]
* Update balena-engine to 18.09.5 [Zubair Lutfullah Kakakhel]
* Log initramfs messages to kernel dmesg to capture fsck, partition expand etc. command output [Zubair Lutfullah Kakakhel]
* kernel-resin: Add FAT fs specific configs to RESIN_CONFIGS [Sebastian Panceac]
* Update balena-supervisor to v9.14.9 [Cameron Diver]
* Introduce meta-balena yocto thud support [Andrei Gherzan]
* Update os-config to 1.1.0 [Andrei Gherzan]
</details>

# v2.33.0+rev2
## (2019-05-24)

* bb-org-overlays.bb: Added BB-UART4-RTSCTS-00A0.dts overlay [sharvin26]

# v2.33.0+rev1
## (2019-05-06)

* Update rust to 1.33 [Andrei Gherzan]
* Add support for OS_KERNEL_CMDLINE [Florin Sarbu]
* Update meta-balena from v2.32.0 to v2.33.0 [Andrei Gherzan]

<details>
<summary> View details </summary>

## meta-balena-2.33.0
### (2019-05-02)

* Fixes for sysroot symlinks creation [Andrei Gherzan]
* libmbim: Refresh patches after last update to avoid build warnings [Andrei Gherzan]
* modemmanager: Refresh patches after last update to avoid build warnings [Andrei Gherzan]
* Make security flags inclusion yocto version specific [Andrei Gherzan]
* systemd: Make directory warning patch yocto version specific [Andrei Gherzan]
* Replace wireless tools by iw [Andrei Gherzan]
* systemd: Use a conf.d file for journald configuration [Andrei Gherzan]
* Set go verison to 1.10.8 to match balena-engine requirements [Andrei Gherzan]
* Update balena-engine to 18.09.3 [Andrei Gherzan]
* Update balena-supervisor to v9.14.6 [Cameron Diver]
* resin-u-boot: make devtool-compatible [Sven Schwermer]
* docker-disk: Disable unnecessary docker pid check [Armin Schlegel]
* Update libmbim to version 1.18.0 [Zahari Petkov]
* Update libqmi to version 1.22.2 [Zahari Petkov]
* Update to ModemManager v1.10.0 [Zahari Petkov]
* Add a OS_KERNEL_CMDLINE parameter that allows BSPs to easily add extra kernel cmdline args to production images [Zubair Lutfullah Kakakhel]
</details>

# v2.32.0+rev3
## (2019-05-06)

* Fix reference in repo.yml to point to the correct URL [Giovanni Garufi]

# v2.32.0+rev2
## (2019-04-25)

* Change the poky submodule to our github mirror [Florin Sarbu]

# v2.32.0+rev1
## (2019-04-24)

* Update the meta-resin submodule from v2.31.5 to v2.32.0 [Alexandru Costache]

<details>
<summary> View details </summary>

## meta-resin-2.32.0
### (2019-04-08)

* balena-supervisor: Update to v9.14.0 [Cameron Diver]
* readme: Replace resin with balena where appropriate [Roman Mazur]
* Add systemd-analyze to production images as well [Zubair Lutfullah Kakakhel]
* Enable dbus interface for dnsmasq [Zubair Lutfullah Kakakhel]
* Disable docker bridge while pulling the supervisor container to remove runtime balena-engine warnings [Zubair Lutfullah Kakakhel]
* Fix typo in os-networkmanager that prevented it from working [Zubair Lutfullah Kakakhel]
* Fix bug where fsck was run on the data partition on every boot even if it wasn't needed due to old system time. [Zubair Lutfullah Kakakhel]
* Fix the balena version string reported by balena-engine info [Zubair Lutfullah Kakakhel]
* Only check mmc devices for flasher image presence by default. [Zubair Lutfullah Kakakhel]
* Remove an extra redundant copy of udev rules database [Zubair Lutfullah Kakakhel]
* Un-upx mobynit and os-config to speed them up a bit. Approx 1 second boost to boot time. [Zubair Lutfullah Kakakhel]
</details>

* Update repo.yml to be able to trigger VersionBot with `meta-balena` [Alexandru Costache]
* Update the balena-yocto-scripts submodule to v1.0.5 [Alexandru Costache]

# v2.31.5+rev1
## (2019-03-26)

* Update meta-resin from v2.30.0 to v2.31.5 [Florin Sarbu]

<details>
<summary> View details </summary>

## meta-resin-2.31.5
### (2019-03-21)

* Update resin-supervisor to v9.11.3 [Andrei Gherzan]

## meta-resin-2.31.4
### (2019-03-20)

* resin-supervisor: Recreate on start if config has changed [Rich Bayliss]

## meta-resin-2.31.3
### (2019-03-20)

* Update resin-supervisor to v9.11.2 [Pablo Carranza Velez]

## meta-resin-2.31.2
### (2019-03-19)

* Update resin-supervisor to v9.11.1 [Pablo Carranza Velez]

## meta-resin-2.31.1
### (2019-03-18)

* Update resin-supervisor to v9.11.0 [Pablo Carranza Velez]

## meta-resin-2.31.0
### (2019-03-08)

* README:md: Document dnsServers behaviour [Alexis Svinartchouk]
* Update resin-supervisor to v9.9.0 [Cameron Diver]
* Cleanup old versions of iwlwifi firmware files in Yocto sumo [Andrei Gherzan]
* Remove polkit dependency in balenaOS [Andrei Gherzan]
* Remove support for XFS file system [Andrei Gherzan]
* resin-init: update resin.io reference to balenaOS [Matthew McGinn]
</details>

* Update the balena-yocto-scripts submodule to v1.0.3 [Florin Sarbu]

# v2.30.0+rev1
## (2019-03-04)

* u-boot: Set pocketbeagle autoboot delay to 0 [Alexandru Costache]
* meta-resin: Update to v2.30.0 [Alexandru Costache]

# v2.29.2+rev4
## (2019-02-25)

* Disable reboot on kernel panic as workaround for https://github.com/balena-os/balena-beaglebone/issues/177 [Florin Sarbu]

# v2.29.2+rev3
## (2019-02-04)

* Fix BT timeout on Beaglebone Green Wireless [Alexandru Costache]

# v2.29.2+rev2
## (2019-02-01)

* Fix BT timeout on Beaglebone Black Wireless [Alexandru Costache]

# v2.29.2+rev1
## (2019-01-15)

* Update meta-resin from v2.29.0 to v2.29.2 [Alexandru Costache]
* Adapted pocketbeagle bootscripts to NetworkManager 1.14.4 [Alexandru Costache]

# v2.29.0+rev3
## (2019-01-14)

* u-boot: Load and apply device tree overlays [Sebastian Panceac]
* Install BeagleBone DT overlays in root partition [Sebastian Panceac]

# v2.29.0+rev2
## (2019-01-03)

* Switch to mainline u-boot v2018.11 [Florin Sarbu]

# v2.29.0+rev1
## (2018-12-20)

* Update meta-resin from v2.28.0 to v2.29.0 [Sebastian Panceac]

<details>
<summary> View details </summary>

## meta-resin-2.29.0
### (2018-12-19)

* OS will default apps.json to an empty json file [Andrei Gherzan]
* Update balena-engine to include low entropy fixes [Andrei Gherzan]
* Move an NM patch to the right place to reduce a warning [Zubair Lutfullah Kakakhel]
* Update balena-supervisor to v9.0.1 [Pablo Carranza Velez]
* Fix cases where RESIN_BOOT_PARTITION_FILES includes invalid entries [Andrei Gherzan]
* Enable some common linux kernel serial device drivers [Andrei Gherzan]
* Configure NetworkManager to only ignore our vpn interface but manage other tun devices [Andrei Gherzan]
* networkmanager: Add pppd to FILES [Zubair Lutfullah Kakakhel]
* networkmanager: Add balena-client-id.patch in bbappend [Zubair Lutfullah Kakakhel]
* Bump network manager from v1.12.2 to v1.14.4 [Zubair Lutfullah Kakakhel]
* Update balena-supervisor to v8.7.0 [Pablo Carranza Velez]
* Fix test cases for kernel module header compilation [Zubair Lutfullah Kakakhel]
* Add chrony v3.2 recipe in various layers to keep minimum chrony version on devices above v3.2 [Zubair Lutfullah Kakakhel]
* chrony/pyro: Add v3.2 recipe [Zubair Lutfullah Kakakhel]
* chrony/morty: Add v3.2 recipe [Zubair Lutfullah Kakakhel]
* chrony/krogoth: Bump recipe version to v3.2 [Zubair Lutfullah Kakakhel]
* Update resin-supervisor to v8.6.8 [Zubair Lutfullah Kakakhel]
</details>

* Update balena-yocto-scripts submodule to v1.0.1 [Sebastian Panceac]

# v2.28.0+rev2
## (2018-12-14)

* u-boot: Switch console to USB [Alexandru Costache]

# v2.28.0+rev1
## (2018-12-06)

* Update meta-resin from v2.27.0 to v2.28.0 [Alexandru Costache]

<details>
<summary> View details </summary>

## meta-resin-2.28.0
### (2018-12-05)

* Update os-config to 1.0.0 [Zahari Petkov]
* Update libqmi to version 1.20.2 [Florin Sarbu]
* Update libmbim to version 1.16.2 [Florin Sarbu]
* kernel-modules-headers: Add basic sanity test [Zubair Lutfullah Kakakhel]
* Fix kernel module header generation [Zubair Lutfullah Kakakhel]
* image-resin.bbclass: Fix config.json pretty format [Andrei Gherzan]
* Allow supervisor update on unmanaged devices [Andrei Gherzan]
* Update resin-supervisor to v8.6.3 [Cameron Diver]
</details>

* Switch from resin-yocto-scripts to balena-yocto-scripts [Alexandru Costache]
* Use overlayfs for PocketBeagle [Alexandru Costache]

# v2.27.0+rev2
## (2018-12-03)

* Add scripts for PocketBeagle networking [Alexandru Costache]

# v2.27.0+rev1
## (2018-11-29)

* Update meta-resin from v2.26.0 to v2.27.0 [Florin Sarbu]

<details>
<summary> View details </summary>

## meta-resin-2.27.0
### (2018-11-23)

* Expose randomMacAddressScan config.json knob [Andrei Gherzan]
* Move modemmanager udev rules in /lib/udev/rules.d [Andrei Gherzan]
* Fix modemmanager bbappend files [Andrei Gherzan]
* dnsmasq: Define 8.8.8.8 as a fallback nameserver [Andrei Gherzan]
* Increase timeout for filesystem label [Vicentiu Galanopulo]
* Add support for Huawei ME936 modem in MBIM mode [Florin Sarbu]
* Backport systemd sd-shutdown improvements for sumo versions [Florin Sarbu]
* Include avahi d-bus introspection files in rootfs [Andrei Gherzan]
* Fix custom udev rules when rule is removed from config.json [Zubair Lutfullah Kakakhel]
* resin-mounts: Add NetworkManager conf.d bind mounts [Zubair Lutfullah Kakakhel]
* Add support to pass custom configuration to NetworkManager [Zubair Lutfullah Kakakhel]
* README.md: Add info about SSH and Avahi services [Andrei Gherzan]
* Avoid xtables lock in resin-proxy-config [Andrei Gherzan]
* Migrate the supervisor to balena repositories [Florin Sarbu]
* Update balena-supervisor to v8.3.5 [Cameron Diver]
* Update supported modems list [Florin Sarbu]

## meta-resin-2.26.0
### (2018-11-05)

* Rename resin-unique-key to balena-unique-key [Andrei Gherzan]
* Don't let resin-unique-key rewrite config.json [Andrei Gherzan]
</details>

* Revert "random: fix crng_ready() test" to fix balena delay start issue [Florin Sarbu]

# v2.26.0+rev4
## (2018-11-28)

* Add icon for PocketBeagle [Alexandru Costache]

# v2.26.0+rev3
## (2018-11-27)

* Fix boot loop hang when switched to meta-ti rocko [Florin Sarbu]

# v2.26.0+rev2
## (2018-11-27)

* beaglebone-pocket: Added machine for PocketBeagle device [Alexandru Costache]

# v2.26.0+rev1
## (2018-11-23)

* Update meta-resin from v2.15.1 to v2.26.0 [Florin Sarbu]

<details>
<summary> View details </summary>

## meta-resin-2.26.0
### (2018-11-05)

* Rename resin-unique-key to balena-unique-key [Andrei Gherzan]
* Don't let resin-unique-key rewrite config.json [Andrei Gherzan]

## meta-resin-2.25.0
### (2018-11-02)

* Generate ssh host key at first boot (not at first connection) [Andrei Gherzan]
* Fix extraneous space in kernel-resin.bbclass config [Florin Sarbu]
* Drop obsolete eval from kernel-resin's do_kernel_resin_reconfigure [Florin Sarbu]
* Add SyslogIdentifier for balena and resin-supervisor healthdog services [Matthew McGinn]

## meta-resin-2.24.1
### (2018-11-01)

* Update resin-supervisor to v8.0.0 [Pablo Carranza Velez]

## meta-resin-2.24.0
### (2018-10-24)

* resin-info: Small tweak for balenaCloud product [Andrei Gherzan]
* Update resin-supervisor to v7.25.8 [Pablo Carranza Velez]
* Rename resinOS to balenaOS [Andrei Gherzan]

## meta-resin-2.23.0
### (2018-10-22)

* Update resin-supervisor to v7.25.5 [Cameron Diver]
* recipes-containers: Increase healthcheck timeout to 180s [Gergely Imreh]
* .gitignore: add node_modules and package-lock files [Giovanni Garufi]

## meta-resin-2.22.1
### (2018-10-20)

* Update resin-supervisor to v7.25.3 [Pablo Carranza Velez]

## meta-resin-2.22.0
### (2018-10-19)

* Update resin-supervisor to v7.25.2 [Andrei Gherzan]
* Include a CONTRIBUTING.md file [Andrei Gherzan]
* Update to ModemManager v1.8.2 [Andrei Gherzan]
* Updates on contributing-device-support.md [Vicentiu Galanopulo]

## meta-resin-2.21.0
### (2018-10-18)

* Improve systemd service ordering in rollbacks [Zubair Lutfullah Kakakhel]
* Update resin-supervisor to v7.24.1 [Andrei Gherzan]

## meta-resin-2.20.0
### (2018-10-18)

* Avoid expander on flasher based on root kernel argument [Andrei Gherzan]
* resin-vars: Implement custom ssh keys service [Andrei Gherzan]
* Fix redsocks interface creation when no proxy configured [Andrei Gherzan]
* Replace NM's DHCP request option "Client indentifier" with udhcpc style option [Sebastian Panceac]
* Fix for rollbacks in case of old balenaOS version [Zubair Lutfullah Kakakhel]
* Update resin-supervisor to v7.21.4 [Cameron Diver]
* Warn if rules are found in /etc/udev/rules.d [Zubair Lutfullah Kakakhel]
* Add support to load custom udev rules from config.json [Zubair Lutfullah Kakakhel]
* aufs-util: Package auplink separately [Florin Sarbu]
* Enable kernel config dependencies for MBIM and QMI [Florin Sarbu]
* Set UPX to use LZMA compression by default [Andrei Gherzan]
* Downgrade UPX to 3.94 for ARM [Andrei Gherzan]
* Balena update for rollbacks. mobynit can now mount rootfs from sysroot. [Zubair Lutfullah Kakakhel]
* Fix proxy when using containers over bridge network [Andrei Gherzan]
* Add support for aufs 4.9.9+, 4.9.94+, 4.18 [Florin Sarbu]
* Add rollback-altboot service before balena service [Zubair Lutfullah Kakakhel]
* Add Automated Rollback recipe [Zubair Lutfullah Kakakhel]
* Add Automated Rollback support in u-boot env_resin.h [Zubair Lutfullah Kakakhel]
* Add a hook to support Automated Rollbacks [Zubair Lutfullah Kakakhel]
* Update HUP grub hook to support Automated Rollbacks [Zubair Lutfullah Kakakhel]
* Update HUP u-boot hook to support Automated Rollbacks [Zubair Lutfullah Kakakhel]
* Move kernel-image-initramfs from resin-image recipe to packagegroup-resin.inc [Zubair Lutfullah Kakakhel]
* Have 99-resin-grub hostapp-update-hook decide which grub to use [Florin Sarbu]

## meta-resin-2.19.0
### (2018-09-23)

* Update Balena to fix tty console hanging in some cases [Petros Angelatos]
* Pin down cargo deps (using Cargo.lock) to versions known working with rust 1.24.1 (for sumo) [Florin Sarbu]
* Remove duplicate packaging of bcm43143 [Florin Sarbu]
* Set ModemManager to ignore Inca Roads Serial Device [Petros Angelatos]
* Add support for aufs 4.14.56+ [Florin Sarbu]
* Update resin-supervisor to v7.19.7 [Cameron Diver]

## meta-resin-2.18.1
### (2018-09-14)

* Add a parsable representation of the changelog [Giovanni Garufi]

## meta-resin-v2.18.0
### (2018-09-12)

* Update grub hooks to prepare to load kernel from root [Zubair Lutfullah Kakakhel]
* Update resin-supervisor to v7.19.4 [Cameron Diver]
* Kernel-resin.bbclass: Enable CONFIG_IP_NF_TARGET_LOG as a module [John (Jack) Brown]
* Balena: Update to current HEAD of 17.12-resin [Andrei Gherzan]
* Compress os-config with UPX on arm64 too [Andrei Gherzan]
* Update upx to 3.95 [Andrei Gherzan]
* Add support to skip flasher detection in env_resin.h [Zubair Lutfullah Kakakhel]
* Add the kernel to the rootfs [Zubair Lutfullah Kakakhel]
* Rework resin-supervisor systemd dependency on balena [Florin Sarbu]
* Enhanced security options for dropbear - sumo [Andrei Gherzan]
* Enhanced security options for dropbear - rocko [Andrei Gherzan]
* Enhanced security options for dropbear - pyro [Andrei Gherzan]
* Enhanced security options for dropbear - morty [Andrei Gherzan]
* Enhanced security options for dropbear - krogoth [Andrei Gherzan]

## meta-resin-2.17.0
### (2018-09-03)

* Resin-proxy-config: The no_proxy file fails to parse when missing EOL [Rich Bayliss]

## meta-resin-2.16.0
### (2018-08-31)

* Os-config: UPX is broken on aarch64 [Theodor Gherzan]
* Allow flasher types to pin preloaded devices [Theodor Gherzan]
* Disable PIE for go [Zubair Lutfullah Kakakhel]
* Disable PIE for balena [Zubair Lutfullah Kakakhel]
</details>

* Update to Poky version rocko-18.0.3 [Florin Sarbu]
* Update the resin-yocto-scripts submodule to master HEAD [Florin Sarbu]
* Add a parsable representation of the changelog [Giovanni Garufi]

# v2.15.1+rev1
## (2018-09-07)

* Update the meta-resin submodule to version v2.15.1 [Florin Sarbu]

# v2.14.1+rev2
## (2018-08-28)

* Add versionist support [Giovanni Garufi]

# v2.14.1+rev1
## (2018-08-07)

* Update the meta-resin submodule to version v2.14.1 [Florin]
* Update the resin-yocto-scripts submodule to 8312741e13604a9d166370349061876afb22c0fa [Florin]

# v2.14.0+rev1
## (2018-07-18)

* Update the meta-resin submodule to version v2.14.0 [Florin]

# v2.13.6+rev1
## (2018-07-13)

* Update the meta-resin submodule to version v2.13.6 [Florin]

# v2.13.5+rev1
## (2018-07-09)

* Update the meta-resin submodule to version v2.13.5 [Florin]

# v2.13.3+rev1
## (2018-07-08)

* Update the meta-resin submodule to version v2.13.3 [Florin]
* Update the resin-yocto-scripts submodule to 59ccd8558435ff6424827fb36ccb43b14650f4d4 (on master branch) [Florin]
* Update the beaglebone kernel to version 4.14.53-ti-r62 [Florin]
* Update the pyro branch for meta-rust submodule [Andrei]

# v2.12.7+rev1
## (2018-05-07)

* Update the meta-resin submodule to version v2.12.7 [Florin]

# v2.12.5+rev1
## (2018-04-26)

* Update the meta-resin submodule to version v2.12.5 [Florin]
* Add support for BeagleBone Black Wireless [Florin]
* Update the resin-yocto-scripts submodule to f7718efbbf53369aaacb7eb54e707ee8a5d4fc4b (on master branch) [Florin]

# v2.12.3+rev1
## (2018-03-15)

* Update the meta-resin submodule to version v2.12.3 [Florin]
* Update the resin-yocto-scripts submodule to dc9dfe466e48d934e55fb20a05156886873b1ab1 (on master branch) [Florin]

# v2.12.1+rev1
## (2018-03-12)

* Update the meta-resin submodule to version v2.12.1 [Andrei]

# v2.9.6+rev1
## (2018-01-14)

* Update the meta-resin submodule to version v2.9.6 [Florin]
* Update the resin-yocto-scripts submodule to 6f7a9ab326bb822196e3e48b08ef1d73d08caec6 (on master branch) [Florin]
* Add wlconf to rootfs [Minh]

# v2.7.8+rev1
## (2017-11-17)

* Update the meta-resin submodule to version v2.7.8 [Florin]
* Increase initramfs maximum size to 12 MB (12288 KB) [Florin]

# v2.7.5+rev2
## (2017-11-03)

* Update the resin-yocto-scripts submodule to c4db082fd2d5a3b4857035264c1e726962d7b826 (on master branch) [Florin]
* Add overlays for being able to use the CAN interface on P9 pins 19 and 20 (CAN0) [Florin]

# v2.7.5+rev1
## (2017-11-01)

* Update the meta-resin submodule to version v2.7.5 [Florin]
* Add to rootfs the device tree overlays needed for the PWM pins [Florin]

# v2.7.4+rev1
## (2017-10-27)

* Update the meta-resin submodule to version v2.7.4 [Florin]
* Update the resin-yocto-scripts submodule to e3a06d48a2f8b7e32d3047c33066a5b896e6ae93 (on master branch) [Florin]
* Update meta-openembedded to latest pyro branch [Will]
* Update poky to latest pyro branch [Will]

# v2.7.2+rev2
## (2017-10-12)

* Install in the rootfs the 99-resin-uboot hostapp hook needed for u-boot to switch the root partition when doing host OS updates [Florin]

# v2.7.2+rev1
## (2017-10-08)

* Update the meta-resin submodule to version v2.7.2 [Florin]
* Update the resin-yocto-scripts submodule to HEAD of master [Florin]
* Update to Yocto Pyro [Will]
* Include meta-rust layer [Will]
* Add meta-rust layer [Will]

# v2.4.2+rev1
## (2017-09-04)

* Update the meta-resin submodule to version v2.4.2 [Florin]
* Update the resin-yocto-scripts submodule to HEAD of master [Florin]
* Add bb-wl18xx-bluetooth recipe for enabling bluetooth [Florin]

# v2.3.0+rev1
## (2017-08-17)

* Update the meta-resin submodule to version v2.3.0 [Florin]

# v2.2.0+rev1
## (2017-07-30)

* Update the meta-resin submodule to version v2.2.0 [Florin]
* Update the resin-yocto-scripts submodule to HEAD of master [Florin]
* Revert Define a new attribute to denote the yocto flasher image [Florin]
* Add device tree overlay for Nimbelinks Skywire Beaglebone Black Cape [Florin]

# v2.1.0+rev1
## (2017-07-21)

* Update the meta-resin submodule to version v2.1.0 [Michal]
* Update the resin-yocto-scripts submodule to HEAD of master [Michal]
* Define a new attribute to denote the yocto flasher image [Michal]

# v2.0.7+rev2
## (2017-06-29)

* Revert beaglebone-green and beaglebone-green-wifi .coffee files to point to their respective yocto machines [Florin]

# v2.0.7+rev1
## (2017-06-29)

* Update the meta-resin submodule to version v2.0.7 [Florin]
* Update the resin-yocto-scripts submodule to HEAD of master [Florin]
* Change bbg and bbgw .coffee files to point to the bbb yocto machine and also change the getting started links [Florin]
* Update kernel to version 4.9.34-ti-r43 [Florin]
* Adapt the u-boot patch for integration with resin-uboot [Florin]
* Update kernel for the beagleboard family from 4.4 to 4.9 [Theodor]
* Update the resin-yocto-scripts submodule [Florin]
* Update resin-yocto-scripts to master [Will]

# v2.0.3+rev1
## (2017-05-12)

* Update the meta-resin submodule to version v2.0.3 [Florin]
* Fix serial console [Theodor]
* Set wlan0 MAC address to EEPROM value [Will]

# v2.0.2+rev2
## (2017-05-01)

* Bump resin-yocto-scripts to fix Jenkins deployment [Andrei]

# v2.0.2+rev1
## (2017-04-24)

* Update the meta-resin submodule to version v2.0.2 [Andrei]
* Generate a bmap file for the resinos-img image [Michal]

# v2.0.0+rev4
## (2017-04-13)

* Bump resin-yocto-scripts to include compressed images in deployment too [Andrei]

# v2.0.0+rev3
## (2017-04-13)

* Bump resin-yocto-scripts to include deployment routine [Andrei]
* Add support for Beaglebone Blue [Will]

# v2.0.0+rev2
## 2017-04-04

* Bump resin-yocto-scripts to fix resinOS docker registry push [Andrei]

# v2.0.0+rev1
## (2017-04-03)

* Fix OS version to be semver compliant [Andrei]

# v2.0.0.rev1
## (2017-04-01)

* Update the meta-resin submodule to version v2.0.0 [Andrei]

# v2.0.0-rc6.rev1
## (2017-03-31)

* Update the meta-resin submodule to version v2.0.0-rc6 [Andrei]

# v2.0.0-rc5.rev1
## (2017-03-26)

* Update meta-resin submodule to version v2.0.0-rc5 [Andrei]

# v2.0.0-rc4.rev1
## (2017-03-20)

* Update meta-resin submodule to version v2.0.0-rc4 [Andrei]

# v2.0.0-rc3.rev1
## (2017-03-14)

* Update meta-resin submodule to version v2.0.0-rc3 [Florin]

# v2.0.0-rc1.rev1
## (2017-03-10)

* Adapt for using initramfs kernel images [Andrei]
* Implement resin-uboot specification 2.0 for beaglebone [Andrei]

# v2.0.0-beta12.rev2
## (2017-02-27)

* Switch beaglebone-black, beaglebone-green and beaglebone-green-wifi to using Poky Morty [Florin]

# v2.0.0-beta12.rev1
## (2017-02-27)

* Bump resin-yocto-scripts to current HEAD [Andrei]
* meta-resin: Bump to 2.0.0-beta12 [Andrei]

# v2.0.0-beta11.rev1
## (2017-02-15)

* Update meta-resin to v2.0.0-beta.11 [Andrei]

# v2.0.0-beta10.rev1
## (2017-02-14)

* Update meta-resin to v2.0.0-beta.10 [Andrei]

# v2.0.0-beta.9
## (2017-02-08)

* Update meta-resin to v2.0-beta.9 [Andrei]

# v2.0.0-beta.8
## (2017-01-27)

* Update meta-resin to v2.0-beta.8 [Andrei]
* Tune memory to prevent higher-order allocation failures [petrosagg]
* Update resin-yocto-scripts to HEAD of the master branch [Florin]

# v2.0.0-beta.7
## (2016-12-05)

* Update meta-resin to v2.0-beta.7 [Florin]

# v2.0.0-beta.6
## (2016-12-05)

* Update meta-resin to v2.0-beta.6 [Andrei]

# v2.0.0-beta.5
## (2016-11-30)

* Update meta-resin to v2.0-beta.5 [Andrei]
* Set a predefined sequence to abort or delay booting [Michal]

# v2.0.0-beta.3
## (2016-11-07)

* Update meta-resin to v2.0-beta.3 [Andrei]
* Cleanup docker-resin-supervisor-disk of unneeded variables [Andrei]
* Update resin-yocto-scripts to fix logging in container builds
* Apply the mmc fix (set vm.vfs_cache_pressure=400) [Michal]
* Don't compress kernel modules [Michal]

# v2.0.0-beta.1
## (2016-10-11)

* Update meta-resin to v2.0-beta.1 [Andrei]
* Add meta-filesystem as we need aufs-utils [Andrei]
* Add build support for resinos [Andrei]
* Update resin-yocto-script to include changes in our image types [Theodor]
* Replace the concept of a debug image with a development image [Theodor]
* Update meta-resin to include avahi [Florin]
* Update resin-yocto-scripts to include kernel headers handling as gzip [Florin]

# v1.16.0
## (2016-09-27)

* Update meta-resin to v1.16 [Florin]

# v1.15.0
## (2016-09-24)

* Update meta-resin to v1.15 [Florin]

# v1.14.0
## (2016-09-23)

* Update meta-resin to v1.14 [Florin]

# v1.13.0
## (2016-09-23)

* Update meta-resin to v1.13 [Florin]
* Update kernel to tag 4.4.21-ti-rt-r46 [Florin]

# v1.12.0
## (2016-09-21)

* Update meta-resin to v1.12 [Florin]
* Update resin-yocto-scripts to include resinhup upload to dockerhub [Florin]
* Update kernel to tag 4.4.21-ti-rt-r45 [Florin]
* Update kernel to tag 4.4.20-ti-rt-r44 [Florin]
* Update meta-resin [Florin]
* Change .coffee to announce partition 1 now holds config.json and also introduce versioning (v1) [Florin]
* Update kernel to version 4.4.19 [Florin]

# v1.11.0
## (2016-08-31)

* Update meta-resin to v1.11 [Florin]

# v1.10.0
## (2016-08-24)

* Update meta-resin to v1.10 [Florin]

# v1.9.0
## (2016-08-24)

* Update meta-resin to v1.9 [Florin]
* Update resin-yocto-scripts for including kernel modules headers deploy [Florin]
* Add support for the beaglebone green board [Florin]
* Update yocto-resin-scripts for host nodejs detection improvements [Florin]

# v1.8.0
## (2016-08-02)

* Bump meta-resin to v1.8 [Andrei]
* Bump resin-device-types to include partial manifest support [Andrei]
* No more debug images in staging

# v1.7.0
## (2016-07-14)

* Update meta-resin to v1.7

# v1.6.0
## (2016-07-06)

* Update meta-resin to v1.6 [Florin]

# v1.5.0
## (2016-07-04)

* Update meta-resin to v1.5 [Florin]

# v1.5.0rc4
## (2016-06-29)

* Update meta-resin to include supervisor update to v1.11.6 [Florin]

# v1.5.0rc3
## (2016-06-29)

* Update meta-resin to include openvpn-resin.service refactoring [Florin]

# v1.5.0rc2
## (2016-06-28)

* Update meta-resin to include docker key.json fix [Florin]
* Update meta-resin to include flasher fixes [Florin]

# v1.4.0
## (2016-06-27)

* Update meta-resin to v1.4 [Florin]
* Update meta-resin to allow let error out [Florin]
* Update meta-resin to allow patching of kernel-modules-headers [Florin]
* Bump meta-resin to fix various issues [Andrei]
* Fix a small syntax error in meta-resin [Andrei]
* Fix automation fix for debug image [Andrei]
* Replace RESIN_STAGING_BUILD by DEBUG_IMAGE [Andrei]

# v1.3.0
## (2016-06-24)

* Update meta-resin to v1.3 [Florin]
* Custom docker images in connectable builds [Andrei]
* Add support for optional supervisor image [Andrei]
* Update meta-resin to include kernel modules compress support [Andrei]
* Compress kernel modules [Andrei]
* Replace SUPERVISOR_TAG by TARGET_TAG [Andrei]
* Update meta-resin to v1.2 [Andrei]
* Bump meta-resin to HEAD [Andrei]
* Use new flasher strategy (specify internal bootloader config file and location where to copy it) [Florin]
* Update meta-resin submodule for including bootloader specific removal changes [Florin]
* Bump yocto-resin-scripts to bring in improvements for in-docker builds [Andrei]
* Configure builds with RM_OLD_IMAGE [Theodor]

# v1.4.1
## (2016-05-19)

* New machine support: BeagleBone Green Wireless [Theodor]
* Provide dtb to control on-board wireless for the BeagleBone Green [Theodor]
* Allow users to use UART5 [Theodor]
* Bump meta-resin to include switch from rce to docker [Andrei]

# v1.4.0
## (2016-04-16)

# v1.1.1
## (2016-03-16)

* Transition from fido -> jethro [Theodor]
