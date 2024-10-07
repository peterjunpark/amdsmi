---
myst:
  html_meta:
    "description lang=en": "AMD SMI documentation and API reference."
    "keywords": "amdsmi, lib, cli, system, management, interface, amdgpu"
---

# AMD SMI documentation

The AMD System Management Interface (AMD SMI) library offers a unified tool for
managing and monitoring GPUs, particularly in high-performance computing
environments. It provides a user-space interface that allows applications to
control GPU operations, monitor performance, and retrieve information about the
system's drivers and GPUs.

Find the source code at <https://github.com/ROCm/amdsmi>.

```{eval-rst}
.. note::

   AMD SMI is a successor to `<https://github.com/ROCm/rocm_smi_lib>`__.

.. grid:: 2
   :gutter: 3

   .. grid-item-card:: Install

      * :doc:`AMD SMI installation <./install/install>`

   .. grid-item-card:: How to

      * :doc:`Use AMD SMI for C++ library <how-to/using-amdsmi-for-C++>`
      * :doc:`Use AMD SMI for Python library <how-to/using-amdsmi-for-python>`
      * :doc:`Use AMD SMI CLI tool <how-to/using-AMD-SMI-CLI-tool>`

   .. grid-item-card:: API reference

      * :doc:`Files <../doxygen/docBin/html/files>`
      * :doc:`Globals <../doxygen/docBin/html/globals>`
      * :doc:`Data structures <../doxygen/docBin/html/annotated>`
      * :doc:`Modules <../doxygen/docBin/html/modules>`
      * :doc:`Data fields <../doxygen/docBin/html/functions_data_fields>`

   .. grid-item-card:: Tutorials

      * `AMD SMI GitHub samples <https://github.com/ROCm/amdsmi/tree/develop/example>`_
      * `ROCm SMI Github samples <https://github.com/ROCm/rocm_smi_lib/tree/develop/docs>`_

To contribute to the documentation, refer to
:doc:`Contributing to ROCm <rocm:contribute/contributing>`.

Find ROCm licensing information on the
:doc:`Licensing <rocm:about/license>` page.

.. rubric:: Disclaimer

   The information contained herein is for informational purposes only, and is
   subject to change without notice. While every precaution has been taken in the
   preparation of this document, it may contain technical inaccuracies, omissions
   and typographical errors, and AMD is under no obligation to update or otherwise
   correct this information. Advanced Micro Devices, Inc. makes no representations
   or warranties with respect to the accuracy or completeness of the contents of
   this document, and assumes no liability of any kind, including the implied
   warranties of noninfringement, merchantability or fitness for particular
   purposes, with respect to the operation or use of AMD hardware, software or
   other products described herein.

   AMD, the AMD Arrow logo, and combinations thereof are trademarks of Advanced
   Micro Devices, Inc. Other product names used in this publication are for
   identification purposes only and may be trademarks of their respective
   companies.

   Copyright (c) 2014-2024 Advanced Micro Devices, Inc. All rights reserved.
```
