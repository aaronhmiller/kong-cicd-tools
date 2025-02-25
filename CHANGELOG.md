# Changelog

## 3.5.0 (2023-01-03)

* Updated base nodejs image to most current Node 15 / buster (as always)
* Updated Kong to 3.1.0
* Updated Kuma to 2.0.1
* Updated Kong Mesh to 2.0.1
* Updated deck to 1.17.1
* Updated portal cli to 3.5.0
* Updated yq to 4.30.6
* Updated helm to 3.10.3
* Updated k6 to 0.42.0
* Updated postgresql clients to 11.18

## 3.4.0 (2022-11-04)

* Updated base nodejs image to most current Node 15 / buster (as always)
* Updated yq to 4.29.2
* Updated helm to 3.10.1
* Updated k6 to 0.41.0
* Updated Kuma to 1.8.1
* Updated Kong Mesh to 1.9.1
* Updated kubeadm / kubectl to 1.25.3
* Updated Kong portal template to a87e14b

## 3.3.0 (2022-10-04)

* Updated base nodejs image to most current Node 15 / buster (as always)
* Updated Kong Gateway to 3.0.0
* Updated deck to 1.15.1
* Updated inso cli to 3.6.0
* Updated yq to 4.27.5
* Updated helm to 3.10.0
* Updated k6 to 0.40.0
* Updated spectral to 6.5.0
* Updated kubeadm / kubectl to 1.25.2
* Updated Kong portal template to cbc4ca2 (3.0.0.0)

## 3.2.0 (2022-09-01)

* Updated base nodejs image to most current Node 15 / buster (as always)
* Updated deck to 1.14.0
* Updated yq to 4.27.3
* Updated helm to 3.9.4
* Updated Kuma to 1.8.0
* Updated Kong Mesh to 1.9.0
* Updated inso cli to 3.5.0
* Updated kubeadm / kubectl to 1.25.0
* Updated Kong portal template to 5659d53
* Updated postgresql clients to 11.17

## 3.1.0 (2022-08-01)

* Updated base nodejs image to most current Node 15 / buster (as always)
* Updated deck to 1.13.0
* Updated yq to 4.26.1
* Updated helm to 3.9.2
* Updated k6 to 0.39.0
* Updated Kuma to 1.7.1
* Updated Kong Mesh to 1.8.1
* Updated portal cli to 3.4.0
* Updated kubeadm / kubectl to 1.24.3
* Updated Kong portal template to 93fbafd
* instead of entrypoint we are using cmd now to easily do a `docker run -ti svenwal/kong-cicd-tool /bin/bash`

## 3.0.0 (2022-07-01)

🆕 The image now has an entrypoint which will keep it running to make it for example easy usable on a Kubernetes deployment

* 🆕 Kong Gateway added
* 🆕 Kong Mesh added
* 🆕 Kuma added
* Updated base nodejs image to most current Node 15 / buster (as always)
* Updated deck to 1.12.2
* Updated yq to 4.25.3
* Updated helm to 3.9.0
* Updated k6 to 0.38.3
* Updated inso cli to 3.3.0
* Updated kubeadm / kubectl to 1.24.2
* Updated Kong portal template to 2662c8d (2.8.1.1)
* Updated postgresql clients to 11.16
* The Dockerfile is now more readable as all version numbers are now defined at the top

## 2.4.0 (2022-05-02)

* Updated base nodejs image to most current Node 15 / buster (as always)
* Updated deck to 1.12.0
* Updated yq to 4.25.1
* Updated helm to 3.8.2
* Updated kubeadm / kubectl to 1.23.6
* Updated Kong portal template to 2662c8d

## 2.3.0 (2022-04-01)

* Updated base nodejs image to most current Node 15 / buster (as always)
* Updated yq to 4.24.2
* Updated helm to 3.8.1
* Updated k6 to 0.37.0
* Updated kubeadm / kubectl to 1.23.5
* Update Kong developer template to 3042c03 (2.8.0.0)
* Fix: yq was missing from the last ARM64 version of the image

## 2.2.0 (2022-03-01)

* Updated base nodejs image to most current Node 15 / buster (as always)
* Updated deck to 1.11.0
* Updated yq to 4.21.1
* Updated kubeadm / kubectl to 1.23.4
* Updated Kong portal template to 3042c03

## 2.1.0 (2022-02-01)

* Updated base nodejs image to most current Node 15 / buster (as always)
* Updated yq to 4.18.1
* Update k6 to 0.36 - also added now an ARM64 version
* Updated kubeadm / kubectl to 1.23.3
* Updated helm to 3.8.0
* Updated Kong portal template to 8ef5079


## 2.0.0 (2022-01-03)

* 🆕 this image is now available for AMD64 and ARM64
* Updated base nodejs image to most current Node 15 / buster (as always)
* Updated decK to 1.10.0
* Updated inso cli to 2.4.1 (also falling back to npm install for easier cross plattform script)
* Updated portal cli to 3.3.1
* Updated yq to 4.16.2
* Updated kubeadm / kubectl to 1.23.1
* Updated Kong portal template to ef6a6c2

## 1.12.0 (2021-12-01)

* Updated base nodejs image to most current Node 15 / buster (as always)
* Updated yq to 4.15.1
* Updated portal cli to 3.3.0
* Updated redis tools to 5.0.14
* Updated k6 to 0.35.0
* Updated kubeadm / kubectl to 1.22.4
* Updated postgresql clients to 11.14

## 1.11.0 (2021-11-01)

* Updated base nodejs image to most current Node 15 / buster (as always)
* Updated inso to 2.4.0 - also the new binary release
* Updated yq to 4.14.1
* Updated spectral to 6.1.0
* Updated kubeadm / kubectl to 1.22.3
* Updated helm to 3.7.1
* Updated postgresql clients to 11.13
* Updated Kong portal template to dfde738

## 1.10.0 (2021-10-01)

* Updated base nodejs image to most current Node 15 / buster (as always)
* Updated decK to 1.8.2
* Updated yq to 4.13.2
* Updated k6 to 0.34.1
* Updated kubeadm / kubectl to 1.22.2
* Updated helm to 3.7.0
* Updated Kong portal template to a9a387b (2.5.0.2)

## 1.9.1 (2021-09-01)

* 🆕 Added Redis tools 5.0.3

## 1.9.0 (2021-09-01)

* Updated base nodejs image to most current Node 15 / buster (as always)
* Updated inso cli to 2.3.2
* Updated yq to 4.12.1
* Updated kubeadm / kubectl to 1.22.1
* Updated portal theme template to ff36b65

## 1.8.0 (2021-08-02)

* Updated base nodejs image to most current Node 15 / buster (as always)
* Updated portal cli to 3.2.0
* Updated helm to 3.6.3
* Updated yq to 4.11.2
* Updated spectral 5.9.2
* Updated kubeadm / kubectl to 1.21.3

## 1.7.0 (2021-07-01)

* Updated base nodejs image to most current Node 15 / buster (as always)
* 🆕 Added kubeadm / kubectl 1.21.2
* 🆕 Added helm 3.6.2
* Updated inso cli to 2.3.0
* Updated yq to 4.9.6
* Updated k6 to 0.33.0

## 1.6.0 (2021-06-01)

* Updated base nodejs image to most current Node 15 / buster
* 🆕 Added PostgreSQL clients (pg_dump and more) 11.12
* Updated decK to 1.7.0
* Updated inso cli to 2.2.35
* Updated yq to 4.9.3
* Updated k6 to 0.32.0
* Updated Spectral 5.9.1

## 1.5.0 (2021-05-03)

* Updated base nodejs image to most current Node 15 / buster
* Updated decK to 1.6.0
* Updated inso cli to 2.2.33
* Updated yq to 4.7.1
* Updated k6 to 0.31.1
* Updated Spectral 5.9.0
* Updated portal theme template to 5206ac7 (Kong Enterprise 2.4)

## 1.4.0 (2021-04-01)

* Updated base nodejs image to most current latest
* Updated decK to 1.5.1 (this version is able to work with Konnect SaaS)
* Updated inso cli to 2.2.33
* Updated yq to 4.6.3
* Updated k6 to 0.31.1
* Updated Spectral 5.9.0

## 1.3.0 (2021-03-05)

* Updated base nodejs image to most current latest
* Updated decK to 1.4.0
* Updated inso cli to 2.2.30
* Updated yq to 4.6.1
* Updated k6 to 0.30.0
* Added Spectral 5.8.1

## 1.2.0 (2021-01-18)

* Updated base nodejs image to most current latest
* Updated decK to 1.3.0
* Updated inso cli to 2.2.28
* Updated yq to 4.4.1 - *BREAKING CHANGE* - see <https://mikefarah.gitbook.io/yq/v/v4.x/upgrading-from-v3>
* Updated k6 to 0.29

## 1.1.0 (2020-11-09)

* Updated base nodejs image to most current latest
* Added k6 for load testing
* Updated decK to 1.2.2

## 1.0.0 (2020-10-29)

* Initial public release
