<h1 align="center">JobQ</h1>
<div align="center">
 <strong> Status: Under Development </strong> <br><br>
 <strong>  
    JobQ is a language-agnostic distributed background job system for AI and backend workflows at any scale. This is a durable, highly scalable and reliable system which doesn't need any additional infrastructure 
like Redis, Postgres/mysql or pub/sub for it's operation.
 </strong>
</div>

<br />

# Features
- Simple API to produce/consume jobs
- No additional infra - beyond optional backup
- Language agnostic - uses TCP protocol,  clients/workers can be implemented in any language
- Job scheduling
- Automatic retries on job failure or timeouts
- Batch job submission

# Phase 1: Core features local development (In Progress)
The following are being tested locally.
- Push job
- Fetch job
- Flush job, flush all jobs
- Mark job as success
- Fail job
- Automatic retries on job failures
- Pending development
  - Job scheduling
  - APIs to produce/consume jobs local development

# Phase 2: APIs to produce/consume jobs (Planned)
- TBD - REST API 
  
# Phase 3: Web UI (Planned)
- Expose a web UI that shows status of queues, jobs and workers. Perform some operations via UI (TBD).  

# Phase 4: Advanced features (Planned) 
- Batch job submission
- Workflows
  
