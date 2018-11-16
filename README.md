# scheduler-demo

This demo is will showcase how to schedule task using
the annotation. `@Scheduled` 

This annotation is added to methods with details about
when to be executed. Under the hood Spring Boot internally uses the `TaskScheduler`
interface for scheduling the annotated methods for execution.
