Service-Now  send insident to service now from command line  - Eashwar Raghunathan
===========
#USAGE ssh or windows

./snowsendinsident.py "$sysparm_action" "$category" "$impact" "$urgency" "$caller_id" "$cmdb_ci" "$short_description"

# example usage

./snowsendinsident.py 'insert' 'software' 1 1 'Abel Tuter' 'Email' 'new incident from eashwar'


