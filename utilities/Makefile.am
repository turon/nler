#
#    Copyright (c) 2018 Nest Labs, Inc.
#    All rights reserved.
#
#    Licensed under the Apache License, Version 2.0 (the "License");
#    you may not use this file except in compliance with the License.
#    You may obtain a copy of the License at
#
#    http://www.apache.org/licenses/LICENSE-2.0
#
#    Unless required by applicable law or agreed to in writing, software
#    distributed under the License is distributed on an "AS IS" BASIS,
#    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
#    See the License for the specific language governing permissions and
#    limitations under the License.
#

#
#    Description:
#      This file is the GNU automake template for the Nest Labs
#      Embedded Runtime utilities library.
#

include $(abs_top_nlbuild_autotools_dir)/automake/pre.am

lib_LIBRARIES                   = \
    libnlerutilities.a            \
    $(NULL)

libnlerutilities_a_CPPFLAGS     = \
    -I$(top_srcdir)/include       \
    $(NULL)

libnlerutilities_a_SOURCES      = \
    nllist.c                      \
    nlresendabletimer.c           \
    nlsettings.c                  \
    $(NULL)

include $(abs_top_nlbuild_autotools_dir)/automake/post.am

