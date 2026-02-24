API Overview
============

Authentication
--------------

All API requests require a bearer token in the Authorization header.

Example:

.. code-block:: http

   GET /api/tasks
   Authorization: Bearer <token>

Response Format
---------------

Responses are returned in JSON format.

Example response:

.. code-block:: json

   {
      "id": 123,
      "name": "Sample Task",
      "status": "completed"
   }
