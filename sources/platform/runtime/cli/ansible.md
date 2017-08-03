page_main_title: Ansible CLI Overview
main_section: Platform
sub_section: Runtime
sub_sub_section: CLIs
page_title: Ansible CLI Overview

# Ansible CLI
Ansible is available for all [Jobs](/platform/workflow/job/overview) that you can execute as part of Shippable DevOps Assembly Lines Platform. All language images and all Operating Systems support this CLI

## Supported OS Versions
This CLI is installed on to the base OS image along with other CLIs. The following are tags and release dates of the base OS Image

### Ubuntu 16.04

|Image| Release Date |Available in AMI | 
|----------|------------|-----|
[drydock/u16all:v5.7.3](/platform/runtime/os/ubuntu16#v573)  | Jul 2017 - Latest | [v5.7.3](/platform/tutorial/runtime/ami-v573)
[drydock/u16all:v5.6.1](/platform/runtime/os/ubuntu16#v561)  | Jun 2017 | [v5.6.1](/platform/tutorial/runtime/ami-v561)
[drydock/u16all:v5.5.1](/platform/runtime/os/ubuntu16#v551)  | May 2017 | [v5.5.1](/platform/tutorial/runtime/ami-v551)
[drydock/u16all:v5.4.1](/platform/runtime/os/ubuntu16#v541)  | Apr 2017 | [v5.4.1](/platform/tutorial/runtime/ami-v541)
[drydock/u16all:v5.3.2](/platform/runtime/os/ubuntu16#v532)  | Mar 2017 | [v5.3.2](/platform/tutorial/runtime/ami-v532)


### Ubuntu 14.04

|Image| Release Date |Available in AMI | 
|----------|------------|-----|
[drydock/u14all:v5.7.3](/platform/runtime/os/ubuntu14#v573)  | Jul 2017 - Latest | [v5.7.3](/platform/tutorial/runtime/ami-v573)
[drydock/u14all:v5.6.1](/platform/runtime/os/ubuntu14#v561)  | Jun 2017 | [v5.6.1](/platform/tutorial/runtime/ami-v561)
[drydock/u14all:v5.5.1](/platform/runtime/os/ubuntu14#v551)  | May 2017 | [v5.5.1](/platform/tutorial/runtime/ami-v551)
[drydock/u14all:v5.4.1](/platform/runtime/os/ubuntu14#v541)  | Apr 2017 | [v5.4.1](/platform/tutorial/runtime/ami-v541)
[drydock/u14all:v5.3.2](/platform/runtime/os/ubuntu14#v532)  | Mar 2017 | [v5.3.2](/platform/tutorial/runtime/ami-v532)


## Supported Versions
This table helps you choose the right tag based on the version of the CLI you might want to use

| Version  |  Tags    
|----------|---------
|2.3.0.0  | v5.7.3 and below

## Further Reading
* [Everything about Shippable AMIs](/platform/tutorial/runtime/ami-overview)
* [Quick Start to CI](/getting-started/ci-sample)
* [CI YML](ci/yml-structure)
* [RunSh Job](/platform/workflow/job/runsh)