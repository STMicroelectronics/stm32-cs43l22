---
pagetitle: Release Notes for CS43L22 Component Drivers
lang: en
---

::: {.row}
::: {.col-sm-12 .col-lg-4}

::: {.card .fluid}
::: {.sectione .dark}
<center>
# <small>Release Notes for</small> <mark>CS43L22 Component Drivers</mark>
Copyright &copy; 2014 STMicroelectronics\
    
[![ST logo](../../../../_htmresc/st_logo.png)](https://www.st.com){.logo}
</center>
:::
:::

# License

Licensed by ST under BSD 3-Clause license (the \"License\"). You may
not use this package except in compliance with the License. You may
obtain a copy of the License at:

[https://opensource.org/licenses/BSD-3-Clause](https://opensource.org/licenses/BSD-3-Clause)

# Purpose

This directory contains the CS43L22 component drivers.

:::

::: {.col-sm-12 .col-lg-8}
# Update History

::: {.collapse}
<input type="checkbox" id="collapse-section22" checked aria-hidden="true">
<label for="collapse-section22" aria-hidden="true">V2.0.4 / 03-April-2019</label>
<div>			

## Main Changes

- Update release notes format

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section20" aria-hidden="true">
<label for="collapse-section20" aria-hidden="true">V2.0.3 / 31-August-2018</label>
<div>			

## Main Changes

- Reformat the BSD 3-Clause license declaration in the files header (replace license terms by a web reference to OSI website where those terms lie)

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section19" aria-hidden="true">
<label for="collapse-section19" aria-hidden="true">V2.0.2 / 02-October-2015</label>
<div>			

## Main Changes

- cs43l22.c/.h: 
  - Move VOLUME_CONVERT macro from cs43l22.h to cs43l22.c as internally used to convert volume.
  - Add literals instead of magic number for cs34l22 registers

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section18" aria-hidden="true">
<label for="collapse-section18" aria-hidden="true">V2.0.1 / 16-September-2015</label>
<div>			

## Main Changes

- cs43l22.c: 
  - Enable the digital soft ramp to avoid clac noise
  - Improve mute/unmute by muting/unmuting also the DAC inputs

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section18" aria-hidden="true">
<label for="collapse-section18" aria-hidden="true">V2.0.0 / 24-June-2015</label>
<div>			

## Main Changes

- cs43l22.c/.h: 
  - Add codec de-initialization function: cs43l22_DeInit()
  - Add Audio IO de-initialization function prototype: AUDIO_IO_DeInit()
  
**[[NOTE]{style="font-size: 10pt; font-family: Verdana; color: black;"}]{.underline}**  
This release must be used with BSP Common driver V4.0.0 or later

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section17" aria-hidden="true">
<label for="collapse-section17" aria-hidden="true">V1.1.0 / 10-February-2015</label>
<div>			

## Main Changes

- cs43l22.c/.h: 
  - Add AUDIO_FREQUENCY_xxx defines for frequencies capabilities (8K to 192K)
  - Add codec reset function: cs43l22_Reset()


</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section16" aria-hidden="true">
<label for="collapse-section16" aria-hidden="true">V1.0.1 / 02-December-2014</label>
<div>			

## Main Changes

- cs43l22.c: change "\\" by "/" in the include path to fix compilation issue under Linux


</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section15" aria-hidden="true">
<label for="collapse-section15" aria-hidden="true">V1.0.0 / 18-February-2014</label>
<div>			

## Main Changes

- First official release of CS43L22 audio codec


</div>
:::

:::
:::

<footer class="sticky">
For complete documentation on <mark>STM32 Microcontrollers</mark> ,
visit: [http://www.st.com/STM32](http://www.st.com/STM32)
</footer>
