ansible-archagent
=========

[![Build Status](https://travis-ci.org/archsaber/ansible-role-archagent.svg?branch=master)](https://travis-ci.org/archsaber/ansible-role-archagent)

[ansible](http://docs.ansible.com/ansible/) module for the [ArchSaber](http://archsaber.com) monitoring agent.


Usage
--------------

Download the latest [release](https://github.com/archsaber/ansible-role-archagent/releases/latest) and copy the extracted content to role directory of your anisble. Rename the directory `ansible-role-archagent` to `archagent`. Change the code & templates & use the role as per your preference.

Or, install it using ansible galaxy as Below

``` bash
ansible-galaxy install ansible-role-archagent
```

Role Variables
--------------

The license key is needed and can be set in the role's `default/main.yml` as below:

``` yml
archsaber_license: yourlicensekey
```



You can also use the `archagent_sync_data_config`, `archagent_sync_metric_config` variables along with their respective templates to sync the `archagent` config files (`data.json` & `metrics.json`).


License
-------

BSD

Copyright 2017 Omnisaber Labs Pvt. Ltd.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
