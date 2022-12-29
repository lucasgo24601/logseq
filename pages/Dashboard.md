- Todo
  query-table:: false
	- {{query (todo later todo) )}}
- In progress
	- {{query (todo now)}}
- Writing plan
	- {{query (and (todo now) [[Writing]] )}}