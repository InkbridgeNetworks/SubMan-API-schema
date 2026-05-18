# SubMan API Schema

This API runs natively in OpenResty/NGINX to provide a high performance RESTful layer around an LDAP instance.
The API should be mostly object agonistic, but has some special endpoints for managing specific object classes.

## Contents
- The Open API schema
- OpenLDAP schema/ldif files for adding custom object definitions into OpenLDAP.

## For ease of consumption
Rendered documentation lives at <https://inkbridgenetworks.github.io/SubMan-API-schema/>, with links from there to the OpenAPI reference (hosted on Stoplight) and the AsyncAPI reference for the SSE event streams (served by every listing endpoint when called with `?subscribe=1`).
