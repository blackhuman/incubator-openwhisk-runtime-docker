<!--
#
# Licensed to the Apache Software Foundation (ASF) under one or more
# contributor license agreements.  See the NOTICE file distributed with
# this work for additional information regarding copyright ownership.
# The ASF licenses this file to You under the Apache License, Version 2.0
# (the "License"); you may not use this file except in compliance with
# the License.  You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#
-->

# Apache OpenWhisk Docker Runtime Container

## 1.3.2
Changes:
  - Fixes bug where a log maker is emitted more than once.

## 1.3.1
Changes:
  - Disallow re-initialization by default. Added environment variable to enable re-initialization for local development.

## 1.3.0
Changes:
  - Added openssh-client.

## 1.2.0
Changes:
  - Added utilties curl and wget.

## 1.1.0
Changes:
  - Allow input parameter larger than 128KB.
  - Added perl language support.
  - Added utilties jq, zip, git.

## 1.0.0
Initial version.
