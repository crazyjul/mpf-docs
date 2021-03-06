playfields:
===========

*Config file section*

+----------------------------------------------------------------------------+---------+
| Valid in :doc:`machine config files </config/instructions/machine_config>` | **YES** |
+----------------------------------------------------------------------------+---------+
| Valid in :doc:`mode config files </config/instructions/mode_config>`       | **NO**  |
+----------------------------------------------------------------------------+---------+

.. overview

The ``playfields:`` section of your config is where you...

.. todo::
   Add description.

Optional settings
-----------------

The following sections are optional in the ``playfields:`` section of your config. (If you don't include them, the default will be used).

ball_search_failed_action:
~~~~~~~~~~~~~~~~~~~~~~~~~~
Single value, type: ``string``. Default: ``new_ball``

.. todo::
   Add description.

ball_search_interval:
~~~~~~~~~~~~~~~~~~~~~
Single value, type: ``time string (ms)`` (:doc:`Instructions for entering time strings) </config/instructions/time_strings>` . Default: ``150ms``

.. todo::
   Add description.

ball_search_phase_1_searches:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Single value, type: ``integer``. Default: ``3``

.. todo::
   Add description.

ball_search_phase_2_searches:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Single value, type: ``integer``. Default: ``3``

.. todo::
   Add description.

ball_search_phase_3_searches:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Single value, type: ``integer``. Default: ``4``

.. todo::
   Add description.

ball_search_timeout:
~~~~~~~~~~~~~~~~~~~~
Single value, type: ``time string (ms)`` (:doc:`Instructions for entering time strings) </config/instructions/time_strings>` . Default: ``15s``

.. todo::
   Add description.

ball_search_wait_after_iteration:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Single value, type: ``time string (ms)`` (:doc:`Instructions for entering time strings) </config/instructions/time_strings>` . Default: ``5s``

.. todo::
   Add description.

ball_search_block_events:
~~~~~~~~~~~~~~~~~~~~~~~~~
Default: ``flipper_cradle``

.. versionadded:: 0.33

TODO

ball_search_unblock_events:
~~~~~~~~~~~~~~~~~~~~~~~~~~~
Default: ``flipper_cradle_release``

.. versionadded:: 0.33

TODO

ball_search_enable_events:
~~~~~~~~~~~~~~~~~~~~~~~~~~
Default: None

.. versionadded:: 0.33

TODO

ball_search_disable_events:
~~~~~~~~~~~~~~~~~~~~~~~~~~~
Default: None

.. versionadded:: 0.33

TODO

debug:
~~~~~~
Single value, type: ``boolean`` (Yes/No or True/False). Default: ``False``

.. todo::
   Add description.

enable_ball_search:
~~~~~~~~~~~~~~~~~~~
Single value, type: ``boolean`` (Yes/No or True/False). Default: ``None``

.. versionchanged:: 0.31

.. todo::
   Add description.

label:
~~~~~~
Single value, type: ``string``. Default: ``%``

.. todo::
   Add description.

tags:
~~~~~
List of one (or more) values, each is a type: ``string``. Default: ``None``

.. todo::
   Add description.
