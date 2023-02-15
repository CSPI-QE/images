# install-operators

## Overview

This simple image is to be used in the [`install-operators` ref in OpenShift CI](https://github.com/openshift/release/pull/36381). The image has been created because this ref requires the `jq` tool as well as the `oc` tool. To solve for this issue we have pulled the `origin-cli` image and installed `jq`.

**GitHub Build/Push Action**: [`deploy-install-operators`](../.github/workflows/deploy-install-operators.yaml)
**Image Repository**: [quay.io/cspi-qe-images/ocp-ci-install-operators](https://quay.io/repository/cspi-qe-images/ocp-ci-install-operators?tab=info)