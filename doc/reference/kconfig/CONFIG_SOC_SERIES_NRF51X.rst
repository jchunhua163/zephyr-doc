:orphan:

.. title:: SOC_SERIES_NRF51X

.. option:: CONFIG_SOC_SERIES_NRF51X:
.. _CONFIG_SOC_SERIES_NRF51X:

Enable support for NRF51 MCU series


:Symbol:           SOC_SERIES_NRF51X
:Type:             bool
:Value:            "n"
:User value:       (no user value)
:Visibility:       "n"
:Is choice item:   true
:Is defined:       true
:Is from env.:     false
:Is special:       false
:Prompts:

 *  "Nordic Semiconductor nRF51 series MCU"
:Default values:
 (no default values)
:Selects:

 *  :option:`CONFIG_CPU_CORTEX_M`
 *  :option:`CONFIG_CPU_CORTEX_M0`
 *  :option:`CONFIG_SOC_FAMILY_NRF5`
 *  :option:`CONFIG_SYS_POWER_LOW_POWER_STATE_SUPPORTED`
 *  :option:`CONFIG_XIP`
 *  :option:`CONFIG_HAS_CMSIS`
 *  :option:`CONFIG_HAS_NORDIC_MDK`
:Reverse (select-related) dependencies:
 (no reverse dependencies)
:Additional dependencies from enclosing menus and ifs:
 (no additional dependencies)
:Locations:
 * ../arch/arm/soc/nordic_nrf5/nrf51/Kconfig.series:18