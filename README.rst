Wavelet scattering tutorials
============================

This is a collection of Jupyter notebooks aimed at learning and experimenting
with the **Wavelet Scattering Transform (WST)**[#]_ and its variants [#]_. The WST is
used to extract information from non-Gaussian processes. The WST is similar to 
a ConvNet in that it cascades convolutions and non-linear activation functions.
However, the weights are wavelets of different scale (and orientation in 2D),
and therefore are not learnt, which makes this technique interesting when
data is parsimonious.

In the tutorials we use the dedicated Python package kymatio_, but also our
own implementation using PyTorch_. Best performance are obtained using a 
cuda-enabled GPU.

.. _kymatio: https://www.kymat.io/
.. _PyTorch: https://pytorch.org/



License
-------
Copyright (C) 2022 by Etienne Rognin <ecr43 at cam.ac.uk>

Permission to use, copy, modify, and/or distribute this software for any purpose
with or without fee is hereby granted.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH 
REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND
FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT,
INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS
OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER
TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF
THIS SOFTWARE.



Related packages
----------------

kymatio_
  Active wavelet scattering package.

.. _kymatio: https://www.kymat.io/


References
----------

.. [#] Invariant Scattering Convolution Networks (https://arxiv.org/abs/1203.1513)
.. [#] Scale Dependencies and Self-Similar Models with Wavelet Scattering Spectra
