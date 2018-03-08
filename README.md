# statcache
Static Caching Extra for MODX Revolution

Forked from Opengeek to update with fixes for compatibility with latest core MODX version.

## Notes
- statcache won't save static files if there is a syntax error in MODX tag markup anywhere in the chain eg. missing closing bracket on this causes total fail to save static: [[- /#wrapper-content ]
