# SubMan API Schema

This API runs natively in OpenResty/NGINX to provide a high performance RESTful layer around an LDAP instance.
The API should be mostly object agonistic, but has some special endpoints for managing specific object classes.

## Contents
- The Open API schema
- OpenLDAP schema/ldif files for adding custom object definitions into OpenLDAP.

## For ease of consumption
A rendered version of the Open API schemas can be found [here](https://networkradius.stoplight.io/docs/ldap-subscriber-api).

The AsyncAPI spec for the SSE event streams (served by every listing endpoint when called with `?subscribe=1`) is rendered separately at <https://inkbridgenetworks.github.io/SubMan-API-schema/>.
