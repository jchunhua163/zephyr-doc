:orphan:

.. title:: NETWORK_IP_STACK_DEBUG_IPV6_ND

.. option:: CONFIG_NETWORK_IP_STACK_DEBUG_IPV6_ND:
.. _CONFIG_NETWORK_IP_STACK_DEBUG_IPV6_ND:

Enables IPv6 Neighbour Discovery code part to output debug messages



:Symbol:           NETWORK_IP_STACK_DEBUG_IPV6_ND
:Type:             bool
:Value:            "n"
:User value:       (no user value)
:Visibility:       "n"
:Is choice item:   false
:Is defined:       true
:Is from env.:     false
:Is special:       false
:Prompts:

 *  "Debug IPv6 Neighbour Discovery" if NETWORKING_WITH_IPV6 || NET_IPV6 (value: "n")
:Default values:

 *  n (value: "n")
 *   Condition: NETWORKING_WITH_IPV6 || NET_IPV6 (value: "n")
:Selects:
 (no selects)
:Reverse (select-related) dependencies:
 (no reverse dependencies)
:Additional dependencies from enclosing menus and ifs:
 (NETWORKING_WITH_LOGGING || NET_LOG) && NETWORKING (value: "n")
:Locations:
 * ../net/ip/Kconfig.debug:116