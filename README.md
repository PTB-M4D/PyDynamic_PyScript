# PyDynamic_PyScript

This is a very quick demo of the capabilities of PyDynamic in conjunction with
[PyScript](https://pyscript.net/). The code of one of our examples (namely
[PyDynamic.examples.Interpolating.validation_spline_interp_with_MC.py](https://github.com/PTB-M4D/PyDynamic/blob/main/src/PyDynamic/examples/Interpolating/validation_spline_interp_with_MC.py)
) is loaded with a very slight modification in the very end to display the result in
the browser. This is done by simply replacing `plt.show()` by `pyscript.write('plot',
plt.gcf())`.

The intent building upon that is to create a demonstrator for PyDynamic in the
browser.

## Getting started

All there is to do to run the example is opening the file
[_example.html_
](https://github.com/PTB-M4D/PyDynamic_PyScript/blob/main/src/example.html)
in browser on a machine with internet access.

## Disclaimer

This software is developed at Physikalisch-Technische Bundesanstalt (PTB). The software
is made available "as is" free of cost. PTB assumes no responsibility whatsoever for its
use by other parties, and makes no guarantees, expressed or implied, about its quality,
reliability, safety, suitability or any other characteristic. In no event will PTB be
liable for any direct, indirect or consequential damage arising in connection with the
use of this software.

## License

This repository is licensed under the
[_EUPL-1.2-or-later_](https://github.com/PTB-M4D/PyDynamic_PyScript/blob/main/LICENSE).