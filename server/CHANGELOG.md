## 5.3.1 (April 5th, 2021)

Improvements:
* Adding Changelog

## 5.3.2 (May 4th, 2021)

Improvements:
* Updated Readme
* Added Maintenance Db support [#246](https://github.com/aquasecurity/aqua-helm/pull/246)
* added annotations support for SA creation  [#249](https://github.com/aquasecurity/aqua-helm/pull/249)

## 5.3.3 (May 24th, 2021)

Bug Fixes:
* Fixed LoadBalancerIP issue [#142](https://github.com/aquasecurity/aqua-helm/issues/142) for server chart in aks environment - [#269](https://github.com/aquasecurity/aqua-helm/pull/269)

Improvements:
* added simple way to add certificates to enable mTLS/SSL for server gateway components and updated relevant Readme - [#268](https://github.com/aquasecurity/aqua-helm/pull/268)
* Updated Readme - [#274](https://github.com/aquasecurity/aqua-helm/pull/272)

## 5.3.4 (June 15th, 2021)

Fixes:
* Fixed disabling DB persistence doesn't working issue [#289](https://github.com/aquasecurity/aqua-helm/pull/289)
* Fixed issue [#290](https://github.com/aquasecurity/aqua-helm/issues/290) - [#292](https://github.com/aquasecurity/aqua-helm/pull/292)

Improvements:
* Envoy config templated and TLS certs for listener and cluster [#284](https://github.com/aquasecurity/aqua-helm/pull/284)

## 5.3.5 (July 15th, 2021)

Fixes:
* Fixed envoy config template issue - [#301](https://github.com/aquasecurity/aqua-helm/pull/301)

Improvements:
* Added Giant Swarm platform support - [#299](https://github.com/aquasecurity/aqua-helm/pull/299)
* Added K3s platform support - [#302](https://github.com/aquasecurity/aqua-helm/pull/302)

## 5.3.6 (Aug 4th, 2021)

Fixes:
* Fixing rootca file not found issue when using CA certificates - [#328](https://github.com/aquasecurity/aqua-helm/pull/328)

Improvements:
* Allowing web ingress path to be configured - [#336](https://github.com/aquasecurity/aqua-helm/pull/336)
* Adding aquasec envoy image and making certs mount for envoy optional - [#331](https://github.com/aquasecurity/aqua-helm/pull/331)