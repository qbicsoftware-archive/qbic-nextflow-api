# Job-object specification

- **id**: _string_, primary key, e.g. `$workflow.sessionId`
- **status**: _enum_, job status, e.g. `[CREATED, RUNNING, FAILED, FINISHED]`
- **userId**: _string_, unix id, e.g. `>whoami -> result`
- **wfType**: _enum_, the workflow type, e.g. `[RNASEQ, WXS, WGS, ...]`
- **wfRepo**: _string_, GitHub repo url, e.g. `https://github.com/qbicsoftware/qbic-nextflow-api` 
- **wfTag**: _string_, GitHub repo version tag, e.g. `v1.0`
- **start**: _string_, Workflow start timestamp (ISO 6801?), e.g. `2007-08-31T16:47+00:00`
- **completion**: _string_, Workflow completion timestamp (ISO 6801?), e.g. `2007-08-31T16:47+00:00`