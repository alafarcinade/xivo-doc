***************
XiVO agentd API
***************

You can view the API documentation at http://api.xivo.io.

Changelog
=========

15.15
-----

* The resources returning agent statuses, i.e.:

  * GET /agents
  * GET /agents/by-id/{agent_id}
  * GET /agents/by-number/{agent_number}

  are now returning an additional argument named "state_interface", which is "the interface (e.g.
  SIP/alice) that is used to determine if an agent is in use or not".
