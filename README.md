Circle CI uses a yaml file to handle the configuration of pipelines and jobs.


<b>version:</b>	Specifies the version of CircleCI's runner you want to use. Most of the time, use the latest.
<b>jobs:</b>	List of jobs.
<b>commands:</b>	List of reusable commands that can be used as steps in jobs.
<b>orbs:</b>	Makes available some pre-written functionality that you can include in your jobs. Orbs become step types which we will see later when we talk more about jobs.
<b>workflows</b>	Puts the jobs in execution order, sets up dependencies.