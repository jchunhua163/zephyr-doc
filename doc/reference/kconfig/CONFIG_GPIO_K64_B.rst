:orphan:

.. title:: GPIO_K64_B

.. option:: CONFIG_GPIO_K64_B:
.. _CONFIG_GPIO_K64_B:

Enable config options for Freescale K64-based GPIO port B.



:Symbol:           GPIO_K64_B
:Type:             bool
:Value:            "n"
:User value:       (no user value)
:Visibility:       "n"
:Is choice item:   false
:Is defined:       true
:Is from env.:     false
:Is special:       false
:Prompts:

 *  "Freescale K64-based GPIO Port B" if GPIO_K64 (value: "n")
:Default values:

 *  n (value: "n")
 *   Condition: GPIO_K64 (value: "n")
 *  y (value: "y")
 *   Condition: (none)
 *  y (value: "y")
 *   Condition: (none)
:Selects:
 (no selects)
:Reverse (select-related) dependencies:
 (no reverse dependencies)
:Additional dependencies from enclosing menus and ifs:
 GPIO_K64 && BOARD_FRDM_K64F (value: "n")
:Locations:
 * ../drivers/gpio/Kconfig.k64:55
 * ../boards/arm/hexiwear_k64/Kconfig.defconfig:101
 * ../boards/arm/frdm_k64f/Kconfig.defconfig:101