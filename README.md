# Elon_Sherlock

I once came across a news [story](https://twitter.com/elonmusk/status/1579105206004252677) about Tesla's whistleblower identification tactic of sending all employees emails with the same appearance. In fact, however, each email contained variations in the number of spaces between sentences. This created a unique binary signature for each email, allowing for precise identification of the whistleblower. And based on that, I decided to do this task for CTF.


## Usage

To use Elon Sherlock, you can build and run the Docker image using the following commands:

```bash
$ docker build -t elon_sherlock
$ docker run -dit --name my-running-app -p 8080:80 elon_sherlock
```

If you don't want to include a Dockerfile in your project, you can directly use the pre-built image from Docker Hub:

```bash
$ docker run -dit --name my-running-app -p 8080:80 glook137/elon-sherlock
```

