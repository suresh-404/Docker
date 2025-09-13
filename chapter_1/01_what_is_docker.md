# What is Docker?

Docker is an open source project for building, shipping, and running programs. It is a command-
line program, a background process, and a set of remote services that take a logistical approach
to solving common software problems and simplifying your experience installing, running, publishing,
and removing software. It accomplishes this by using an operating system technology called containers.

## Running Your First Docker Container

### Command to run:

```bash
docker run dockerinaction/hello_world
```

### What happens under the hood when we run "docker run" command?
- Docker starts and downloads necessary components.
- Eventually, it prints: hello world
- If you run the command again: It directly prints hello world without downloading again.

### Key points about the command:
- docker run triggers Docker to start a container.
- The command sequence installs and runs a program inside a container.

This process is illustrated in below figure 1.1 .
![figure 1.1: How docker run works](images/how_docker_run_works.png)


✍️  *Reference: Notes adapted from **Docker in Action***

