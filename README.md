# Github-Actions-Conditional
Demonstrate how to use conditional logic in Github Action workflows to control Step and Job executions.

### Conditional Jobs and Step:
- Control Step and Job executions with `if` and dynamic expression
- Change default behavior with `failure()`.
- Use continue-on-error to ignore step failure

### Matrix Jobs:
- Run mulitple job configurations in parallel
- determine wether single failing jobs cancel the workflow with continue-on-error

### Reusable Workflows
- `workflow_call` event: Allows the workflow to be callable by other workflows. 
- useful for passing data to and from workflows. 
