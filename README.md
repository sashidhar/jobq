<h1 align="center">JobQ</h1>
<div align="center">
 <strong> Status: Under Development </strong> <br><br>
 <strong>  
    JobQ is a language-agnostic distributed background job system. This is a durable, highly scalable and reliable system which doesn't need any additional infrastructure 
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
