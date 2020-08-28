
## DevOps Workshop

- [DevOps Workshop](#devops-workshop)
- [About this Workshop](#about-this-workshop)
- [Lectures](#lectures)
  - [Current](#current)
- [Hands-on Labs](#hands-on-labs)
  - [Current](#current-1)
- [IBM DevOps](#ibm-devops)
- [Compatibility](#compatibility)
- [Credits](#credits)

## About this Workshop

The DevOps Workshop covers different technologies and strategies to deploy Microservices and 12-Factor Apps to Kubernetes and OpenShift: from Helm, Istio, OpenShift build strategies (Docker, Source-to-Image (S2I), Custom, Pipeline), Tekton, Operator Framework, and Open Source projects and solutions by IBM, Red Hat, CD Foundation, and CNCF.

## Lectures

### Current

| Duration | Title | Description | Comments |
| - | - | - | - |
| - | [An Overview of CI/CD for Microservices](https://ibm.box.com/s/06x65zghsfze7p2el80pdb3i91ai9t59) | Complete overview with code examples | - |
| - | [Microservices](https://ibm.box.com/s/juwyhpy4yt99ckvigd43140tlx3j53rb) | Principles, Patterns and Implementation Considerations | (updated: 2019-06-20) |
| - | [12-Factor Apps](https://ibm.box.com/s/2pgg87vtq3nh3nn4k24324i4pwzp4bxc) | - | (updated: 2019-05-22) |
| - | [App Modernization Migration Approaches](https://ibm.box.com/s/h9c5357a72xm2c0p8whqkv8dyl0c7is0) | - | (updated: 2020-06-29) |
| - | [Cloud Pak for Apps: DevFiles and Odo](https://ibm.box.com/s/90vdp32dkjhdp2vss3qwkpdnws6jmz95) | - | - |
| - | [Tekton Overview](https://ibm.box.com/s/kisshn88w4a79jzz557o5h6c5k55o9ze) | - | - |
| - | [Cloud Paks: Adding Value with Cloud Pak for Applications](https://ibm.box.com/s/y4wh104vdos1vw5kdjwwuhebf8jgq580) | - | - |


## Hands-on Labs

### Current

| Duration | Title | Description | Comments |
| - | - | - | - |
| 45 mins | [Helm 101](https://github.com/IBM/helm101/) | - | - |
| 45 mins | [Istio 101](https://github.com/IBM/istio101) | - | - |
| - | [OpenShift 101: Build with Source-to-Image (S2I)](https://ibm-developer.gitbook.io/openshift101/workshop/exercise-01) | - | - |
| - | [OpenShift 101: Build with Docker](https://ibm-developer.gitbook.io/openshift101/alternates/exercise-01b) | - | - |
| - | [OpenShift 101: BuildConfig](https://ibm-developer.gitbook.io/openshift101/alternates/exercise-06b) | - | - |
| - | [OpenShift 101: Jenkins](https://github.com/IBMAppModernization/app-modernization-openshift-cicd-lab-shared) | Use the OpenShift Web Console to create a Jenkins Pipeline | - |
| 60-90mins | [OpenShift 201: Customizing Source-to-Image (S2I)](https://github.com/IBM/s2i-open-liberty-workshop) | Using Source-to-Image (S2I) Build Strategy with Universal Base Image (UBI), Custom Builder and Runtime Images, Templates, BuildConfig and DeploymentConfig | - |
| - | [OpenShift 201: Jenkins to OpenShift Pipelines](https://github.com/remkohdev/jenkins101) | From Jenkins Pipelines to OpenShift Pipelines | - | 
| - | [Tekton 201](https://github.com/IBM/tekton-tutorial-openshift) | - | - |
| 45 mins | [Operators 201: From Existing Helm Charts](https://github.com/rojanjose/guestbook-helm-operator) | Custom Resources, Operator Framework and Creating Operators from Existing Helm Charts | - |
| - | [Operators 301: Bind an IBM Cloud Service to a Cluster with the IBM Operator](https://github.com/timroster/digidevcon-iks/tree/master/workshop) | - | - |
| - | OpenShift 101: [Logging, Monitoring and Telemetry](https://ibm-developer.gitbook.io/openshift101/workshop/exercise-02) | - | - |
| - | [Portable Development Environments using DevFile](https://github.com/odrodrig/devfile-lab) | - | - |


## IBM DevOps 

The [Cloud Native Computing Foundation (CNCF)](https://landscape.cncf.io/) includes among other the following `Open Source` licensed projects in the category `App Definition and Development - Continuous Integration and Delivery`:
- Argo,
- Gitlab,
- Jenkins,
- JenkinsX,
- Spinnaker,
- Tekton, 
- Travis CI.

The CNCF includes among other the following `Open Source` licensed projects in the category `App Definition and Development - Application Definition and Image Build`:
- Buildpacks.io,
- Docker Compose,
- Helm,
- Kaniko,
- Kudo,
- OpenAPI Initiative,
- Operator Framework,
- Podman.

The [Continuous Delivery Foundation (CDF)](https://cd.foundation) includes the following founding projects:
- Jenkins,
- JenkinsX,
- Spinnaker,
- Tekton,
- Screwdriver.cd.

The primary build strategies on OpenShift 4.x are:
- Docker build,
- Source-to-Image (S2I) build,
- Custom build with Buildah,
- Pipeline build.

[Red Hat Open Source projects](https://redhatofficial.github.io/#!/main) include among other:
- OpenSCAP,
- Podman,
- Buildah,
- Tekton,
- Ansible,
- Operator Framework,
- Quay,
- CRI-O,
- Jaeger,
- SELinux.

[IBM Open Source projects]() include among other:

## Compatibility

This workshop has been tested on the following platforms:

* **OpenShift**: version 4.3

## Credits

* [Remko de Knikker](https://github.com/remkohdev)
* [Oliver Rodriguez](https://github.com/odrodrig)
* [Tim Robinson](https://github.com/timroster)
* [John Zaccone](https://github.com/jzaccone)
* [Rojan Jose](https://github.com/rojanjose)