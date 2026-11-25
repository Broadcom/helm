# Changelog

All notable changes for each upgraded tag of the CloudHealth Container Collector image.  Found on DockerHub: https://hub.docker.com/r/cloudhealth/container-collector

The agent has been verified against:

[Kubernetes Versions ≥ 1.12](https://kubernetes.io/releases/)</br>
[Kubernetes Versions ≤ 1.34](https://kubernetes.io/releases/)</br>
[OC Version ≥ 4.1](https://docs.openshift.com/container-platform)

All versions before June 20, 2022 (Version: 1191) have been deprecated.

## [1520] - 2026-11-25

### Security

* Vulnerabilities patched:
  * [CVE-2026-11564](https://avd.aquasec.com/nvd/cve-2026-11564)
  * [CVE-2026-11856](https://avd.aquasec.com/nvd/cve-2026-11856)
  * [CVE-2026-18924](https://avd.aquasec.com/nvd/cve-2026-18924)
  * [CVE-2026-19931](https://avd.aquasec.com/nvd/cve-2026-19931)
  * [CVE-2026-8925](https://avd.aquasec.com/nvd/cve-2026-8925)
  * [CVE-2026-8926](https://avd.aquasec.com/nvd/cve-2026-8926)
  * [CVE-2026-9079](https://avd.aquasec.com/nvd/cve-2026-9079)
  * [CVE-2026-11352](https://avd.aquasec.com/nvd/cve-2026-11352)
  * [CVE-2026-11586](https://avd.aquasec.com/nvd/cve-2026-11586)
  * [CVE-2026-13608](https://avd.aquasec.com/nvd/cve-2026-13608)
  * [CVE-2026-3805](https://avd.aquasec.com/nvd/cve-2026-3805)
  * [CVE-2026-80229](https://avd.aquasec.com/nvd/cve-2026-80229)
  * [CVE-2026-80230](https://avd.aquasec.com/nvd/cve-2026-80230)
  * [CVE-2026-80231](https://avd.aquasec.com/nvd/cve-2026-80231)
  * [CVE-2026-80255](https://avd.aquasec.com/nvd/cve-2026-80255)
  * [CVE-2026-82208](https://avd.aquasec.com/nvd/cve-2026-82208)
  * [CVE-2026-82209](https://avd.aquasec.com/nvd/cve-2026-82209)
  * [CVE-2026-9080](https://avd.aquasec.com/nvd/cve-2026-9080)
  * [CVE-2026-9545](https://avd.aquasec.com/nvd/cve-2026-9545)
  * [CVE-2026-9546](https://avd.aquasec.com/nvd/cve-2026-9546)
  * BDSA-2026-9096
  * [CVE-2026-7009](https://avd.aquasec.com/nvd/cve-2026-7009)
  * [CVE-2026-8458](https://avd.aquasec.com/nvd/cve-2026-8458)
  * BDSA-2026-37211
  * BDSA-2026-37215
  * BDSA-2026-37245
  * BDSA-2026-37247
  * [CVE-2026-86413](https://avd.aquasec.com/nvd/cve-2026-86413)
  * [CVE-2026-86414](https://avd.aquasec.com/nvd/cve-2026-86414)
  * [CVE-2026-87861](https://avd.aquasec.com/nvd/cve-2026-87861)
  * [CVE-2026-87866](https://avd.aquasec.com/nvd/cve-2026-87866)
  * [CVE-2026-92388](https://avd.aquasec.com/nvd/cve-2026-92388)
  * [CVE-2026-94265](https://avd.aquasec.com/nvd/cve-2026-94265)
  * BDSA-2026-37183
  * BDSA-2026-37222
  * BDSA-2026-37251
  * BDSA-2026-37255
  * [CVE-2026-107928](https://avd.aquasec.com/nvd/cve-2026-107928)
  * [CVE-2026-107929](https://avd.aquasec.com/nvd/cve-2026-107929)
  * [CVE-2026-86410](https://avd.aquasec.com/nvd/cve-2026-86410)
  * [CVE-2026-86412](https://avd.aquasec.com/nvd/cve-2026-86412)
  * [CVE-2026-86415](https://avd.aquasec.com/nvd/cve-2026-86415)
  * [CVE-2026-87862](https://avd.aquasec.com/nvd/cve-2026-87862)
  * [CVE-2026-87863](https://avd.aquasec.com/nvd/cve-2026-87863)
  * [CVE-2026-87865](https://avd.aquasec.com/nvd/cve-2026-87865)
  * [CVE-2026-92386](https://avd.aquasec.com/nvd/cve-2026-92386)
  * [CVE-2026-92387](https://avd.aquasec.com/nvd/cve-2026-92387)
  * [CVE-2026-92389](https://avd.aquasec.com/nvd/cve-2026-92389)
  * [CVE-2026-92390](https://avd.aquasec.com/nvd/cve-2026-92390)
  * [CVE-2026-92391](https://avd.aquasec.com/nvd/cve-2026-92391)
  * [CVE-2026-92392](https://avd.aquasec.com/nvd/cve-2026-92392)
  * [CVE-2026-94266](https://avd.aquasec.com/nvd/cve-2026-94266)
  * BDSA-2026-36539
  * [CVE-2026-113351](https://avd.aquasec.com/nvd/cve-2026-113351)
  * [CVE-2026-115506](https://avd.aquasec.com/nvd/cve-2026-115506)
  * [CVE-2026-117610](https://avd.aquasec.com/nvd/cve-2026-117610)
  * [CVE-2026-118370](https://avd.aquasec.com/nvd/cve-2026-118370)
  * [CVE-2026-66046](https://avd.aquasec.com/nvd/cve-2026-66046)
  * [CVE-2026-76957](https://avd.aquasec.com/nvd/cve-2026-76957)
  * [CVE-2026-93990](https://avd.aquasec.com/nvd/cve-2026-93990)
  * [CVE-2026-102633](https://avd.aquasec.com/nvd/cve-2026-102633)
  * [CVE-2026-50219](https://avd.aquasec.com/nvd/cve-2026-50219)
  * [CVE-2026-56131](https://avd.aquasec.com/nvd/cve-2026-56131)
  * [CVE-2026-56132](https://avd.aquasec.com/nvd/cve-2026-56132)
  * [CVE-2026-56403](https://avd.aquasec.com/nvd/cve-2026-56403)
  * [CVE-2026-56404](https://avd.aquasec.com/nvd/cve-2026-56404)
  * [CVE-2026-56405](https://avd.aquasec.com/nvd/cve-2026-56405)
  * [CVE-2026-56406](https://avd.aquasec.com/nvd/cve-2026-56406)
  * [CVE-2026-56407](https://avd.aquasec.com/nvd/cve-2026-56407)
  * [CVE-2026-56408](https://avd.aquasec.com/nvd/cve-2026-56408)
  * [CVE-2026-56409](https://avd.aquasec.com/nvd/cve-2026-56409)
  * [CVE-2026-56410](https://avd.aquasec.com/nvd/cve-2026-56410)
  * [CVE-2026-56411](https://avd.aquasec.com/nvd/cve-2026-56411)
  * [CVE-2026-56412](https://avd.aquasec.com/nvd/cve-2026-56412)
  * [CVE-2026-72522](https://avd.aquasec.com/nvd/cve-2026-72522)
  * [CVE-2026-41080](https://avd.aquasec.com/nvd/cve-2026-41080)
  * [CVE-2026-45186](https://avd.aquasec.com/nvd/cve-2026-45186)
  * [CVE-2026-32776](https://avd.aquasec.com/nvd/cve-2026-32776)
  * [CVE-2026-32777](https://avd.aquasec.com/nvd/cve-2026-32777)
  * [CVE-2026-32778](https://avd.aquasec.com/nvd/cve-2026-32778)
  * [CVE-2026-24515](https://avd.aquasec.com/nvd/cve-2026-24515)
  * [CVE-2026-40355](https://avd.aquasec.com/nvd/cve-2026-40355)
  * [CVE-2026-40356](https://avd.aquasec.com/nvd/cve-2026-40356)
  * [CVE-2026-11850](https://avd.aquasec.com/nvd/cve-2026-11850)
  * [CVE-2026-48863](https://avd.aquasec.com/nvd/cve-2026-48863)
  * [CVE-2026-48864](https://avd.aquasec.com/nvd/cve-2026-48864)
  * [CVE-2026-9149](https://avd.aquasec.com/nvd/cve-2026-9149)
  * [CVE-2026-9150](https://avd.aquasec.com/nvd/cve-2026-9150)
  * BDSA-2026-9020
  * [CVE-2026-7598](https://avd.aquasec.com/nvd/cve-2026-7598)
  * [CVE-2026-55199](https://avd.aquasec.com/nvd/cve-2026-55199)
  * [CVE-2026-55200](https://avd.aquasec.com/nvd/cve-2026-55200)
  * [CVE-2026-58050](https://avd.aquasec.com/nvd/cve-2026-58050)
  * [CVE-2026-66032](https://avd.aquasec.com/nvd/cve-2026-66032)
  * [CVE-2026-66033](https://avd.aquasec.com/nvd/cve-2026-66033)
  * [CVE-2026-66034](https://avd.aquasec.com/nvd/cve-2026-66034)
  * [CVE-2026-66035](https://avd.aquasec.com/nvd/cve-2026-66035)
  * [CVE-2025-69720](https://avd.aquasec.com/nvd/cve-2025-69720)
  * [CVE-2026-16389](https://avd.aquasec.com/nvd/cve-2026-16389)
  * [CVE-2026-2781](https://avd.aquasec.com/nvd/cve-2026-2781)
  * [CVE-2026-44604](https://avd.aquasec.com/nvd/cve-2026-44604)
  * BDSA-2026-22478
  * [CVE-2025-70873](https://avd.aquasec.com/nvd/cve-2025-70873)
  * [CVE-2026-11824](https://avd.aquasec.com/nvd/cve-2026-11824)
  * [CVE-2026-11822](https://avd.aquasec.com/nvd/cve-2026-11822)
  * [CVE-2026-27171](https://avd.aquasec.com/nvd/cve-2026-27171)
  * [CVE-2026-5588](https://avd.aquasec.com/nvd/cve-2026-5588)
  * [CVE-2025-14813](https://avd.aquasec.com/nvd/cve-2025-14813)
  * [CVE-2026-8763](https://avd.aquasec.com/nvd/cve-2026-8763)
  * [CVE-2026-13506](https://avd.aquasec.com/nvd/cve-2026-13506)
  * [CVE-2026-5598](https://avd.aquasec.com/nvd/cve-2026-5598)
  * [CVE-2026-0636](https://avd.aquasec.com/nvd/cve-2026-0636)

## [1510] - 2026-01-22

### Security

* Vulnerabilities patched:
  * [CVE-2024-3596](https://avd.aquasec.com/nvd/cve-2024-3596)
  * [CVE-2025-5914](https://avd.aquasec.com/nvd/cve-2025-5914)
  * [CVE-2025-5915](https://avd.aquasec.com/nvd/cve-2025-5915)
  * [CVE-2025-5916](https://avd.aquasec.com/nvd/cve-2025-5916)
  * [CVE-2025-5917](https://avd.aquasec.com/nvd/cve-2025-5917)
  * [CVE-2025-5918](https://avd.aquasec.com/nvd/cve-2025-5918)
  * [CVE-2025-60753](https://avd.aquasec.com/nvd/cve-2025-60753)
  * [CVE-2025-4517](https://avd.aquasec.com/nvd/cve-2025-4517)
  * [CVE-2025-4138](https://avd.aquasec.com/nvd/cve-2025-4138)
  * [CVE-2025-4330](https://avd.aquasec.com/nvd/cve-2025-4330)
  * [CVE-2025-8194](https://avd.aquasec.com/nvd/cve-2025-8194)
  * [CVE-2024-12718](https://avd.aquasec.com/nvd/cve-2024-12718)
  * [CVE-2025-6965](https://avd.aquasec.com/nvd/cve-2025-6965)
  * [CVE-2025-7709](https://avd.aquasec.com/nvd/cve-2025-7709)
  * [CVE-2025-29088](https://avd.aquasec.com/nvd/cve-2025-29088)
  * [CVE-2025-9086](https://avd.aquasec.com/nvd/cve-2025-9086)
  * [CVE-2025-10148](https://avd.aquasec.com/nvd/cve-2025-10148)
  * [CVE-2025-4947](https://avd.aquasec.com/nvd/cve-2025-4947)
  * [CVE-2025-5025](https://avd.aquasec.com/nvd/cve-2025-5025)
  * [CVE-2025-0395](https://avd.aquasec.com/nvd/cve-2025-0395)
  * [CVE-2025-4802](https://avd.aquasec.com/nvd/cve-2025-4802)
  * [CVE-2025-8058](https://avd.aquasec.com/nvd/cve-2025-8058)
  * [CVE-2025-9230](https://avd.aquasec.com/nvd/cve-2025-9230)
  * [CVE-2025-9232](https://avd.aquasec.com/nvd/cve-2025-9232)
  * [CVE-2025-32988](https://avd.aquasec.com/nvd/cve-2025-32988)
  * [CVE-2025-32990](https://avd.aquasec.com/nvd/cve-2025-32990)
  * [CVE-2025-32989](https://avd.aquasec.com/nvd/cve-2025-32989)
  * [CVE-2025-6395](https://avd.aquasec.com/nvd/cve-2025-6395)
  * [CVE-2025-59375](https://avd.aquasec.com/nvd/cve-2025-59375)
  * [CVE-2024-10963](https://avd.aquasec.com/nvd/cve-2024-10963)
  * [CVE-2025-6020](https://avd.aquasec.com/nvd/cve-2025-6020)
  * [CVE-2025-13601](https://avd.aquasec.com/nvd/cve-2025-13601)
  * [CVE-2025-4373](https://avd.aquasec.com/nvd/cve-2025-4373)
  * [CVE-2025-6141](https://avd.aquasec.com/nvd/cve-2025-6141)
  * [CVE-2025-8916](https://avd.aquasec.com/nvd/cve-2025-8916)
  * [CVE-2025-46551](https://avd.aquasec.com/nvd/cve-2025-46551)

## [1500] - 2025-04-16

### Fixed

* Minor bug fix on the log message formatting when posting the collected resources to CloudHealth.

### Security

* Vulnerabilities patched:
  * [CVE-2024-8176](https://avd.aquasec.com/nvd/cve-2024-8176)
  * [CVE-2025-27363](https://avd.aquasec.com/nvd/cve-2025-27363)
  * [CVE-2025-31115](https://avd.aquasec.com/nvd/cve-2025-31115)

## [1498] - 2024-10-28

### Security

* Vulnerabilities patched:
  * [CVE-2024-6197](https://avd.aquasec.com/nvd/cve-2024-6197)
  * [CVE-2024-7264](https://avd.aquasec.com/nvd/cve-2024-7264)
  * [CVE-2024-6197](https://avd.aquasec.com/nvd/cve-2024-6197)
  * [CVE-2024-7264](https://avd.aquasec.com/nvd/cve-2024-7264)
  * [CVE-2024-45491](https://avd.aquasec.com/nvd/cve-2024-45491)
  * [CVE-2024-45492](https://avd.aquasec.com/nvd/cve-2024-45492)
  * [CVE-2024-45490](https://avd.aquasec.com/nvd/cve-2024-45490)
  * [CVE-2024-45491](https://avd.aquasec.com/nvd/cve-2024-45491)
  * [CVE-2024-45492](https://avd.aquasec.com/nvd/cve-2024-45492)
  * [CVE-2024-45490](https://avd.aquasec.com/nvd/cve-2024-45490)
  * [CVE-2024-37371](https://avd.aquasec.com/nvd/cve-2024-37371)
  * [CVE-2024-37370](https://avd.aquasec.com/nvd/cve-2024-37370)
  * [CVE-2024-0743](https://avd.aquasec.com/nvd/cve-2024-0743)
  * [CVE-2023-27043](https://avd.aquasec.com/nvd/cve-2023-27043)
  * [CVE-2024-6923](https://avd.aquasec.com/nvd/cve-2024-6923)
  * [CVE-2024-4032](https://avd.aquasec.com/nvd/cve-2024-4032)
  * [CVE-2023-27043](https://avd.aquasec.com/nvd/cve-2023-27043)
  * [CVE-2024-6923](https://avd.aquasec.com/nvd/cve-2024-6923)
  * [CVE-2024-4032](https://avd.aquasec.com/nvd/cve-2024-4032)
  * [CVE-2024-47554](https://avd.aquasec.com/nvd/cve-2024-47554)

## [1481] - 2024-07-19

### Security

* Vulnerabilities patched:
  * [CVE-2023-5388](https://avd.aquasec.com/nvd/cve-2023-5388)
  * [CVE-2023-46218](https://avd.aquasec.com/nvd/cve-2023-46218)
  * [CVE-2023-46219](https://avd.aquasec.com/nvd/cve-2023-46219)
  * [CVE-2024-2004](https://avd.aquasec.com/nvd/cve-2024-2004)
  * [CVE-2024-2398](https://avd.aquasec.com/nvd/cve-2024-2398)
  * [CVE-2024-2511](https://avd.aquasec.com/nvd/cve-2024-2511)
  * [CVE-2024-2961](https://avd.aquasec.com/nvd/cve-2024-2961)
  * [CVE-2024-4741](https://avd.aquasec.com/nvd/cve-2024-4741)
  * [CVE-2024-5535](https://avd.aquasec.com/nvd/cve-2024-5535)
  * [CVE-2024-26256](https://avd.aquasec.com/nvd/cve-2024-26256)
  * [CVE-2024-26458](https://avd.aquasec.com/nvd/cve-2024-26458)
  * [CVE-2024-26461](https://avd.aquasec.com/nvd/cve-2024-26461)
  * [CVE-2024-26462](https://avd.aquasec.com/nvd/cve-2024-26462)
  * [CVE-2024-28085](https://avd.aquasec.com/nvd/cve-2024-28085)
  * [CVE-2024-28757](https://avd.aquasec.com/nvd/cve-2024-28757)
  * [CVE-2024-28834](https://avd.aquasec.com/nvd/cve-2024-28834)
  * [CVE-2024-28835](https://avd.aquasec.com/nvd/cve-2024-28835)
  * [CVE-2024-29857](https://avd.aquasec.com/nvd/cve-2024-29857)
  * [CVE-2024-30171](https://avd.aquasec.com/nvd/cve-2024-30171)
  * [CVE-2024-30172](https://avd.aquasec.com/nvd/cve-2024-30172)
  * [CVE-2024-33599](https://avd.aquasec.com/nvd/cve-2024-33599)
  * [CVE-2024-33600](https://avd.aquasec.com/nvd/cve-2024-33600)
  * [CVE-2024-33601](https://avd.aquasec.com/nvd/cve-2024-33601)
  * [CVE-2024-33602](https://avd.aquasec.com/nvd/cve-2024-33602)
  * [CVE-2024-34397](https://avd.aquasec.com/nvd/cve-2024-34397)
  * [CVE-2024-34447](https://avd.aquasec.com/nvd/cve-2024-34447)

## [1458] - 2024-03-11

### Added

* PersistentVolumes, PersistentVolumeClaims, Ingress and Service collected to prepare for comprehensive Kubernetes Cost Calculation

### Security

* Vulnerabilities patched:
  * [CVE-2023-0767](https://avd.aquasec.com/nvd/cve-2023-0767)
  * [CVE-2023-3320](https://avd.aquasec.com/nvd/cve-2023-3320)
  * [CVE-2023-4641](https://avd.aquasec.com/nvd/cve-2023-4641)
  * [CVE-2023-5981](https://avd.aquasec.com/nvd/cve-2023-5981)
  * [CVE-2023-6246](https://avd.aquasec.com/nvd/cve-2023-6246)
  * [CVE-2023-6779](https://avd.aquasec.com/nvd/cve-2023-6779)
  * [CVE-2023-6780](https://avd.aquasec.com/nvd/cve-2023-6780)
  * [CVE-2023-7104](https://avd.aquasec.com/nvd/cve-2023-7104)
  * [CVE-2023-29383](https://avd.aquasec.com/nvd/cve-2023-29383)
  * [CVE-2023-33201](https://avd.aquasec.com/nvd/cve-2023-33201)
  * [CVE-2023-33202](https://avd.aquasec.com/nvd/cve-2023-33202)
  * [CVE-2023-48795](https://avd.aquasec.com/nvd/cve-2023-48795)
  * [CVE-2023-52425](https://avd.aquasec.com/nvd/cve-2023-52425)
  * [CVE-2023-52426](https://avd.aquasec.com/nvd/cve-2023-52426)
  * [CVE-2024-0553](https://avd.aquasec.com/nvd/cve-2024-0553)
  * [CVE-2024-0567](https://avd.aquasec.com/nvd/cve-2024-0567)
  * [CVE-2024-0727](https://avd.aquasec.com/nvd/cve-2024-0727)
  * [CVE-2024-22365](https://avd.aquasec.com/nvd/cve-2024-22365)

## [1423] - 2023-12-14

### Added

* The collector docker image now supports the "endpoint prefix" environment variable as a replacement for the "region"
environment variable. This variable should be set to the endpoint prefix provided by CloudHealth.


## [1405] - 2023-11-06

### Added

* The collector docker image now contains more debugging logs for setting the new "region" environment variable.

## [1398] - 2023-10-18

### Added

* The collector docker image now supports the "region" environment variable. This variable should be set to the region provided by CloudHealth corresponding to the CloudHealth region where your VMware Tanzu CloudHealth account is onboarded.

## [1360] - 2023-07-19

### Added

* The collector docker image now supports collecting the UID and kubernetes agent version.

## [1325] - 2023-05-18

### Changed

* Updated base image for the CloudHealth Container Collector image to [Photon v.5](https://hub.docker.com/_/photon)

## [1308] - 2023-02-22

### Security

* Assigned ID to the container's user within the Dockerfile to allow for use of `runAsNonRoot` security context option.

## [1307] - 2023-02-16

### Security

* Vulnerabilities patched:
  * [CVE-2023-0286](https://nvd.nist.gov/vuln/detail/CVE-2023-0286)
  * [CVE-2022-25857](https://nvd.nist.gov/vuln/detail/CVE-2022-25857)
  * [CVE-2022-3996](https://nvd.nist.gov/vuln/detail/CVE-2022-3996)
  * [CVE-2022-42003](https://nvd.nist.gov/vuln/detail/CVE-2022-42003)
  * [CVE-2022-42004](https://nvd.nist.gov/vuln/detail/CVE-2022-42004)
  * [CVE-2022-43551](https://nvd.nist.gov/vuln/detail/CVE-2022-43551)


## [1285] - 2022-12-01

* Base Alpine image updated to 
[tag 3.17.0](https://hub.docker.com/layers/library/alpine/3.17.0/images/sha256-c0d488a800e4127c334ad20d61d7bc21b4097540327217dfab52262adc02380c?context=explore), 
patching multiple vulnerabilities

## [1263] - 2022-11-14

### Fixed

* Resolves intermittent java.security.InvalidAlgorithmParameterException in arm64-compatible image. 

## [1225] - 2022-10-06

### Added

* Multi-platform support for the collector image.  The Docker image now supports both arm64 & amd64 architecture.

## [1222] - 2022-09-21

### Added

* Curl command added for troubleshooting assistance

## [1203] - 2022-08-10

### Added

* Liveness Check for collector pod
  * Added a new file liveness.txt in collector pod /tmp folder. Every time collection is performed for any resource, the
    file's access date timestamp is updated.

## [1201] - 2022-08-09

### Removed

* Removed triggering requests to errors endpoint

## [1191] - 2022-07-25

### Added

* Functionality to collect additional resources from the Kubernetes API including:
  * ResourceQuotas
  * LimitRanges
  * Deployments
  * ReplicaSets
  * StatefulSets
  * DaemonSets
  * CronJobs

* Functionality to collect pod metrics from Kubernetes metrics-server
* Error handling added to provide better debug logging while retrieving data from Kubernetes API

## [1183] - 2022-07-12

### Security

* JRuby removed from final image
* Unused jar libraries removed

## [1180] - 2022-06-17

### Security

* Upgraded to Alpine 3.16.0
* Ruby Libraries Upgraded as well as a few deprecated

## [1178] - 2022-06-15

### Added

* Functionality added to refresh the service account token periodically to prevent the use of expired tokens. 

## [1173] - 2022-05-19

### Security

* Libraries Upgraded
* Vulnerabilities patched: CVE-2020-10663, CVE-2020-28052, CVE-2020-36518, CVE-2021-37714, CVE-2020-15522, CVE-2015-6748

## [1172] - 2022-05-11

### Security

* Upgraded to Alpine 3.15.4

## [1155] - 2022-03-28

### Removed

* Removed jbundler

## [1119] - 2022-03-16

### Added

* Changelog introduced
