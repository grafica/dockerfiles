# Copyright 2021 AR Grafica, Inc <https://grafica.app>
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#    https://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

FROM ubuntu:focal

RUN DEBIAN_FRONTEND=noninteractive apt-get update
RUN DEBIAN_FRONTEND=noninteractive apt-get install -y apt-utils
# TODO: Clang seems to require these, but they are not welcome.
# There seem to be some options to avoid libxml2, not sure about libtinfo5.
RUN DEBIAN_FRONTEND=noninteractive apt-get install -y libtinfo5
RUN DEBIAN_FRONTEND=noninteractive apt-get install -y libxml2
