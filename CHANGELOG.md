# 1.0.0 (2022-09-17)


### Bug Fixes

* Added missing releaserc.json ([27af6e5](https://github.com/Caiuse/GenericScriptableArchitecture/commit/27af6e542a9f0d49897b64fd32734e519a822038))
* Added the missing enabled checkbox to ScriptableEventListener component in inspector ([c3b5b34](https://github.com/Caiuse/GenericScriptableArchitecture/commit/c3b5b348a82258ee8b6d7f03ffb337f9e4340b76))
* Added TimelineInternals sln and csproj files to git repo ([22c30db](https://github.com/Caiuse/GenericScriptableArchitecture/commit/22c30db68ebdbec768017d3651543599587de185))
* Deleted accidentally added cache file ([62f9563](https://github.com/Caiuse/GenericScriptableArchitecture/commit/62f95635bd6a333f3cbb5e8e333dbb2891c423bf))
* Fixed an issue where an editor of the generated component is lost and the wildcard listener doesn't show the generated component UI even though it exists ([d782af0](https://github.com/Caiuse/GenericScriptableArchitecture/commit/d782af04a067c8cd8ae18a344f72a94754487c96))
* Fixed an issue with missing generic MonoBehaviours after pulling changes from git ([e25cc42](https://github.com/Caiuse/GenericScriptableArchitecture/commit/e25cc4276d8a59f8cb8003c0f8413a6e6af938ba))
* Fixed bugs in GenericUnityObjects and ExtEvents ([090bba6](https://github.com/Caiuse/GenericScriptableArchitecture/commit/090bba6990ff1f7e82d25522b9a35a0fbbe3cf10))
* Fixed bugs in the GenericUnityObjects dependency package ([ebfd9d2](https://github.com/Caiuse/GenericScriptableArchitecture/commit/ebfd9d2e6897b49335f68fa1658de67062837fe7))
* Fixed compilation error when using Timeline 1.4.8 ([a0c9768](https://github.com/Caiuse/GenericScriptableArchitecture/commit/a0c976802ad819991293c6cc181d514346de88b8))
* Fixed drawing of a serializable class without custom property drawer inside Reference ([79c6f60](https://github.com/Caiuse/GenericScriptableArchitecture/commit/79c6f609fc2be77560d2015626d8f5d6aae981fa))
* Fixed error in TimelineInternals.dll when Timeline package is not installed ([8c73f40](https://github.com/Caiuse/GenericScriptableArchitecture/commit/8c73f402037648812d2a0d7e403472847ca19252))
* Fixed exceptions when using UnityEvents interface and when creating new generic unity objects ([167318c](https://github.com/Caiuse/GenericScriptableArchitecture/commit/167318c4ad54c9a11ee24f496937ecee58e39b9f))
* Fixed generic header not being shown for Variable and Constant ([befc150](https://github.com/Caiuse/GenericScriptableArchitecture/commit/befc150941b2ebf9a18381e1c8ed2053d527ca32))
* Fixed icon assets not being loaded when installing a package from git or openupm ([e62b8c4](https://github.com/Caiuse/GenericScriptableArchitecture/commit/e62b8c4c92de59a2bda4bd31fa0ecd993e200459))
* Fixed incompatibilities with Unity 2021.2 ([411aa8c](https://github.com/Caiuse/GenericScriptableArchitecture/commit/411aa8c689f5686d2e5da38c5095896b6d688282))
* Fixed MissingReferenceException sometimes appearing on MacOS ([dc3b3de](https://github.com/Caiuse/GenericScriptableArchitecture/commit/dc3b3de4fec71023d10a211bfafd3e6d64b7f51e))
* Fixed NRE when opening a type dropdown on MacOS ([3d5b3ad](https://github.com/Caiuse/GenericScriptableArchitecture/commit/3d5b3adb84a4207ea4eaf2a633bbb2d851b2fe11))
* Fixed OnEnable not running for Variable and VariableWithHistory in Editor with PlayMode options enabled ([1f20864](https://github.com/Caiuse/GenericScriptableArchitecture/commit/1f20864cb2253cf30c4de5ff2227cc9ec0c3a769))
* Fixed reference to the Timeline assembly ([566fb24](https://github.com/Caiuse/GenericScriptableArchitecture/commit/566fb2456a1c478ca32c2f4755b0861a08e3d22b))
* Fixed the error in console regarding the immutable Changelog file ([a5f3b3b](https://github.com/Caiuse/GenericScriptableArchitecture/commit/a5f3b3bb816196ec5048bba7593a7dc09182d9db))
* Fixed the ReorderableList.ClearCache method not being found through reflection ([afcd012](https://github.com/Caiuse/GenericScriptableArchitecture/commit/afcd012da5e75d19102d732a269e6dd4ee1d4d6e))
* Fixed various bugs in GenericUnityObjects and ClassTypeReference ([c2292bf](https://github.com/Caiuse/GenericScriptableArchitecture/commit/c2292bf07e4cca47fd778d714ee80590ee96f5d6))
* Fixed various issues in GenericUnityObjects ([f2e76d6](https://github.com/Caiuse/GenericScriptableArchitecture/commit/f2e76d6b3935c81561dc5db0c4dbeaa06548687a))
* In Variables, when current values is changed through inspector, the previous value is sent through event ([33321e6](https://github.com/Caiuse/GenericScriptableArchitecture/commit/33321e6d84a69d730b28f8ebd024116bb0cc25b1))
* Integrated fixes from SolidUtilities and GenericUnityObjects ([0741d83](https://github.com/Caiuse/GenericScriptableArchitecture/commit/0741d83e2a15d247e4db4e9ae43f7c9e9ec0ff09))
* Removed Net Standard 2.1 features to support older versions of Unity ([990c860](https://github.com/Caiuse/GenericScriptableArchitecture/commit/990c860602c69e1318e89bf027822a1d6fd75f89))
* Started saving config changes to disk immediately after a change in generated assemblies ([f08cc24](https://github.com/Caiuse/GenericScriptableArchitecture/commit/f08cc24e25abfe28a8c77bdc04709781fcdf7b68))
* Updated GenericUnityObjects to fix issues with using git ([acf79ff](https://github.com/Caiuse/GenericScriptableArchitecture/commit/acf79ff751cb938a39e797e05a8ed7780e7a83d7))


### Features

* Added a toggle to show hidden generated components for ScriptableEventListener ([38cad41](https://github.com/Caiuse/GenericScriptableArchitecture/commit/38cad41eab9a081b0283d7ce800f8977f36a7a52))
* Added a warning suggesting to show the generated components if the number of generated components is higher than the wildcard (visible) ones ([6285100](https://github.com/Caiuse/GenericScriptableArchitecture/commit/628510032d4f204b770a88c364a7079e2f015bd3))
* Added ability to set custom argument names for ScriptableEventListeners and Invoke button in Scriptable Event Inspector ([9d80a46](https://github.com/Caiuse/GenericScriptableArchitecture/commit/9d80a46091af2b569f74fa404ef03cc1e52e693f))
* Added an ability to traverse the hierarchy of types in the dropdown ([2c1b045](https://github.com/Caiuse/GenericScriptableArchitecture/commit/2c1b04508403107759e40d10c006b64000e888ee))
* Added CI to release the package ([dc7c47a](https://github.com/Caiuse/GenericScriptableArchitecture/commit/dc7c47a048cea7b1656ca600bdf89fd256d07913))
* Added EventInstancer support to scriptable event listeners ([3046706](https://github.com/Caiuse/GenericScriptableArchitecture/commit/304670647d8a05a904771aa0e9f64417dbd1eae5))
* Added EventInstancers ([859ffb8](https://github.com/Caiuse/GenericScriptableArchitecture/commit/859ffb8ea7dfba4d544b6bec27297ea164814792))
* Added EventReference class to be able to choose between Scriptable Event and Event Instancer in inspector ([b64929d](https://github.com/Caiuse/GenericScriptableArchitecture/commit/b64929d293724a803ae0dbfe2941fe79b9885c05))
* Added public getters for min and max values of ClampedInt, ClampedFloat ([aca2c65](https://github.com/Caiuse/GenericScriptableArchitecture/commit/aca2c65fa6cc6937ff6e0ee6ca161073cb2477bb))
* Added variable instancer with history ([2053cc3](https://github.com/Caiuse/GenericScriptableArchitecture/commit/2053cc30e46579a622d6823315da759fc7b7d23e))
* Added VariableInstancer ([89da192](https://github.com/Caiuse/GenericScriptableArchitecture/commit/89da192b7334fa91d28fffd2dcea21c79fa14d23))
* Added VariableInstancer as a choice in Reference ([0057915](https://github.com/Caiuse/GenericScriptableArchitecture/commit/00579151c0192b37d81af088e3092a96cf1bb2e6))
* Exposed initial value of a variable as a get-only property ([4cb0324](https://github.com/Caiuse/GenericScriptableArchitecture/commit/4cb03243af6ceb53fce368315f5294dad21ad9df))
* Fixed emitters for new Timeline package version and added a custom action menu for generating generic emitters ([07ed92c](https://github.com/Caiuse/GenericScriptableArchitecture/commit/07ed92c35c84d697bea0b6444e65cac7771e58a9))
* Integrated MissingScriptType into custom editors ([fff8f26](https://github.com/Caiuse/GenericScriptableArchitecture/commit/fff8f26100e7727b9e1769a370839d117f59f549))
* Made so that the set up serialized response does not disappear if the changed event reference of ScriptableEventListener has the same generic arguments as the previous reference ([39c3f7d](https://github.com/Caiuse/GenericScriptableArchitecture/commit/39c3f7dea653c5eba9c56460b280edc4cb9f9f38))
* Renamed ReferenceBase to Reference, made ValueType, Variable, and Constant public properties ([6798f54](https://github.com/Caiuse/GenericScriptableArchitecture/commit/6798f54be6ba61d51182dc0f75a31eecce313ea1))
* Replaced deep copy of variable initial values with serializing value to binary and back using odin serializer ([411ce63](https://github.com/Caiuse/GenericScriptableArchitecture/commit/411ce6376ee175e824f5648771c40588934fcfd3))
* Replaced UnityEvent with ExtEvent in ScriptableEventListeners ([0ada411](https://github.com/Caiuse/GenericScriptableArchitecture/commit/0ada411d3a998934071561bd0ff8b27b8afa490f))
* Started generating emitters with each new concrete ScriptableEvent ([0090890](https://github.com/Caiuse/GenericScriptableArchitecture/commit/0090890d8f3c31b8ca801c37684b38bcb7fe836d))
* Started using the new ApplyToChildren attribute on ScriptableEventEmitters ([235f36e](https://github.com/Caiuse/GenericScriptableArchitecture/commit/235f36e4f6dcfce9a5501b6bffa06ef1f8fd4768))
* Switched from GUID to assembly names in asmdefs ([cf9d124](https://github.com/Caiuse/GenericScriptableArchitecture/commit/cf9d12430e6337f5cf8a2f11059515f5d4a177e3))

## [1.4.1](https://github.com/SolidAlloy/GenericScriptableArchitecture/compare/1.4.0...1.4.1) (2022-08-02)


### Bug Fixes

* Fixed generic header not being shown for Variable and Constant ([befc150](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/befc150941b2ebf9a18381e1c8ed2053d527ca32))

# [1.4.0](https://github.com/SolidAlloy/GenericScriptableArchitecture/compare/1.3.3...1.4.0) (2022-07-25)


### Bug Fixes

* Added the missing enabled checkbox to ScriptableEventListener component in inspector ([c3b5b34](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/c3b5b348a82258ee8b6d7f03ffb337f9e4340b76))
* Fixed an issue where an editor of the generated component is lost and the wildcard listener doesn't show the generated component UI even though it exists ([d782af0](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/d782af04a067c8cd8ae18a344f72a94754487c96))


### Features

* Added a toggle to show hidden generated components for ScriptableEventListener ([38cad41](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/38cad41eab9a081b0283d7ce800f8977f36a7a52))
* Added a warning suggesting to show the generated components if the number of generated components is higher than the wildcard (visible) ones ([6285100](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/628510032d4f204b770a88c364a7079e2f015bd3))
* Added ability to set custom argument names for ScriptableEventListeners and Invoke button in Scriptable Event Inspector ([9d80a46](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/9d80a46091af2b569f74fa404ef03cc1e52e693f))
* Added EventInstancer support to scriptable event listeners ([3046706](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/304670647d8a05a904771aa0e9f64417dbd1eae5))
* Added EventInstancers ([859ffb8](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/859ffb8ea7dfba4d544b6bec27297ea164814792))
* Added EventReference class to be able to choose between Scriptable Event and Event Instancer in inspector ([b64929d](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/b64929d293724a803ae0dbfe2941fe79b9885c05))
* Added public getters for min and max values of ClampedInt, ClampedFloat ([aca2c65](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/aca2c65fa6cc6937ff6e0ee6ca161073cb2477bb))
* Added variable instancer with history ([2053cc3](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/2053cc30e46579a622d6823315da759fc7b7d23e))
* Added VariableInstancer ([89da192](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/89da192b7334fa91d28fffd2dcea21c79fa14d23))
* Added VariableInstancer as a choice in Reference ([0057915](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/00579151c0192b37d81af088e3092a96cf1bb2e6))
* Exposed initial value of a variable as a get-only property ([4cb0324](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/4cb03243af6ceb53fce368315f5294dad21ad9df))
* Integrated MissingScriptType into custom editors ([fff8f26](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/fff8f26100e7727b9e1769a370839d117f59f549))
* Made so that the set up serialized response does not disappear if the changed event reference of ScriptableEventListener has the same generic arguments as the previous reference ([39c3f7d](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/39c3f7dea653c5eba9c56460b280edc4cb9f9f38))
* Renamed ReferenceBase to Reference, made ValueType, Variable, and Constant public properties ([6798f54](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/6798f54be6ba61d51182dc0f75a31eecce313ea1))
* Replaced deep copy of variable initial values with serializing value to binary and back using odin serializer ([411ce63](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/411ce6376ee175e824f5648771c40588934fcfd3))
* Switched from GUID to assembly names in asmdefs ([cf9d124](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/cf9d12430e6337f5cf8a2f11059515f5d4a177e3))

## [1.3.3](https://github.com/SolidAlloy/GenericScriptableArchitecture/compare/1.3.2...1.3.3) (2022-05-08)


### Bug Fixes

* Fixed the ReorderableList.ClearCache method not being found through reflection ([afcd012](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/afcd012da5e75d19102d732a269e6dd4ee1d4d6e))

## [1.3.2](https://github.com/SolidAlloy/GenericScriptableArchitecture/compare/1.3.1...1.3.2) (2022-02-13)


### Bug Fixes

* Fixed bugs in GenericUnityObjects and ExtEvents ([090bba6](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/090bba6990ff1f7e82d25522b9a35a0fbbe3cf10))

## [1.3.1](https://github.com/SolidAlloy/GenericScriptableArchitecture/compare/1.3.0...1.3.1) (2022-02-03)


### Bug Fixes

* Fixed the error in console regarding the immutable Changelog file ([a5f3b3b](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/a5f3b3bb816196ec5048bba7593a7dc09182d9db))

# [1.3.0](https://github.com/SolidAlloy/GenericScriptableArchitecture/compare/1.2.5...1.3.0) (2022-02-03)


### Bug Fixes

* Fixed drawing of a serializable class without custom property drawer inside Reference ([79c6f60](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/79c6f609fc2be77560d2015626d8f5d6aae981fa))
* Removed Net Standard 2.1 features to support older versions of Unity ([990c860](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/990c860602c69e1318e89bf027822a1d6fd75f89))


### Features

* Replaced UnityEvent with ExtEvent in ScriptableEventListeners ([0ada411](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/0ada411d3a998934071561bd0ff8b27b8afa490f))

## [1.2.5](https://github.com/SolidAlloy/GenericScriptableArchitecture/compare/1.2.4...1.2.5) (2021-11-21)


### Bug Fixes

* Fixed various issues in GenericUnityObjects ([f2e76d6](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/f2e76d6b3935c81561dc5db0c4dbeaa06548687a))

## [1.2.4](https://github.com/SolidAlloy/GenericScriptableArchitecture/compare/1.2.3...1.2.4) (2021-11-16)


### Bug Fixes

* Fixed incompatibilities with Unity 2021.2 ([411aa8c](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/411aa8c689f5686d2e5da38c5095896b6d688282))

## [1.2.3](https://github.com/SolidAlloy/GenericScriptableArchitecture/compare/1.2.2...1.2.3) (2021-10-24)


### Bug Fixes

* Fixed various bugs in GenericUnityObjects and ClassTypeReference ([c2292bf](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/c2292bf07e4cca47fd778d714ee80590ee96f5d6))

## [1.2.2](https://github.com/SolidAlloy/GenericScriptableArchitecture/compare/1.2.1...1.2.2) (2021-10-22)


### Bug Fixes

* Fixed NRE when opening a type dropdown on MacOS ([3d5b3ad](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/3d5b3adb84a4207ea4eaf2a633bbb2d851b2fe11))

## [1.2.1](https://github.com/SolidAlloy/GenericScriptableArchitecture/compare/1.2.0...1.2.1) (2021-10-17)


### Bug Fixes

* Fixed exceptions when using UnityEvents interface and when creating new generic unity objects ([167318c](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/167318c4ad54c9a11ee24f496937ecee58e39b9f))

# [1.2.0](https://github.com/SolidAlloy/GenericScriptableArchitecture/compare/1.1.9...1.2.0) (2021-10-13)


### Features

* Added an ability to traverse the hierarchy of types in the dropdown ([2c1b045](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/2c1b04508403107759e40d10c006b64000e888ee))

## [1.1.9](https://github.com/SolidAlloy/GenericScriptableArchitecture/compare/1.1.8...1.1.9) (2021-10-07)


### Bug Fixes

* Fixed error in TimelineInternals.dll when Timeline package is not installed ([8c73f40](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/8c73f402037648812d2a0d7e403472847ca19252))

## [1.1.8](https://github.com/SolidAlloy/GenericScriptableArchitecture/compare/1.1.7...1.1.8) (2021-09-30)


### Bug Fixes

* Started saving config changes to disk immediately after a change in generated assemblies ([f08cc24](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/f08cc24e25abfe28a8c77bdc04709781fcdf7b68))

## [1.1.7](https://github.com/SolidAlloy/GenericScriptableArchitecture/compare/1.1.6...1.1.7) (2021-09-29)


### Bug Fixes

* Fixed MissingReferenceException sometimes appearing on MacOS ([dc3b3de](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/dc3b3de4fec71023d10a211bfafd3e6d64b7f51e))

## [1.1.6](https://github.com/SolidAlloy/GenericScriptableArchitecture/compare/1.1.5...1.1.6) (2021-09-27)


### Bug Fixes

* Integrated fixes from SolidUtilities and GenericUnityObjects ([0741d83](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/0741d83e2a15d247e4db4e9ae43f7c9e9ec0ff09))

## [1.1.5](https://github.com/SolidAlloy/GenericScriptableArchitecture/compare/1.1.4...1.1.5) (2021-09-16)


### Bug Fixes

* Fixed an issue with missing generic MonoBehaviours after pulling changes from git ([e25cc42](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/e25cc4276d8a59f8cb8003c0f8413a6e6af938ba))

## [1.1.4](https://github.com/SolidAlloy/GenericScriptableArchitecture/compare/1.1.3...1.1.4) (2021-09-05)


### Bug Fixes

* Updated GenericUnityObjects to fix issues with using git ([acf79ff](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/acf79ff751cb938a39e797e05a8ed7780e7a83d7))

## [1.1.3](https://github.com/SolidAlloy/GenericScriptableArchitecture/compare/1.1.2...1.1.3) (2021-08-31)


### Bug Fixes

* Deleted accidentally added cache file ([62f9563](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/62f95635bd6a333f3cbb5e8e333dbb2891c423bf))
* Fixed bugs in the GenericUnityObjects dependency package ([ebfd9d2](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/ebfd9d2e6897b49335f68fa1658de67062837fe7))

## [1.1.2](https://github.com/SolidAlloy/GenericScriptableArchitecture/compare/1.1.1...1.1.2) (2021-08-30)


### Bug Fixes

* Fixed icon assets not being loaded when installing a package from git or openupm ([e62b8c4](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/e62b8c4c92de59a2bda4bd31fa0ecd993e200459))

## [1.1.1](https://github.com/SolidAlloy/GenericScriptableArchitecture/compare/1.1.0...1.1.1) (2021-08-29)


### Bug Fixes

* Fixed compilation error when using Timeline 1.4.8 ([a0c9768](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/a0c976802ad819991293c6cc181d514346de88b8))

# [1.1.0](https://github.com/SolidAlloy/GenericScriptableArchitecture/compare/1.0.1...1.1.0) (2021-08-28)


### Bug Fixes

* Added TimelineInternals sln and csproj files to git repo ([22c30db](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/22c30db68ebdbec768017d3651543599587de185))


### Features

* Fixed emitters for new Timeline package version and added a custom action menu for generating generic emitters ([07ed92c](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/07ed92c35c84d697bea0b6444e65cac7771e58a9))
* Started generating emitters with each new concrete ScriptableEvent ([0090890](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/0090890d8f3c31b8ca801c37684b38bcb7fe836d))
* Started using the new ApplyToChildren attribute on ScriptableEventEmitters ([235f36e](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/235f36e4f6dcfce9a5501b6bffa06ef1f8fd4768))

## [1.0.1](https://github.com/SolidAlloy/GenericScriptableArchitecture/compare/1.0.0...1.0.1) (2021-08-23)


### Bug Fixes

* Fixed reference to the Timeline assembly ([566fb24](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/566fb2456a1c478ca32c2f4755b0861a08e3d22b))

# 1.0.0 (2021-08-22)


### Bug Fixes

* Added missing releaserc.json ([27af6e5](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/27af6e542a9f0d49897b64fd32734e519a822038))
* Fixed OnEnable not running for Variable and VariableWithHistory in Editor with PlayMode options enabled ([1f20864](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/1f20864cb2253cf30c4de5ff2227cc9ec0c3a769))
* In Variables, when current values is changed through inspector, the previous value is sent through event ([33321e6](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/33321e6d84a69d730b28f8ebd024116bb0cc25b1))


### Features

* Added CI to release the package ([dc7c47a](https://github.com/SolidAlloy/GenericScriptableArchitecture/commit/dc7c47a048cea7b1656ca600bdf89fd256d07913))
