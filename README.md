
## Introduction

**FeatBit** is a scalable and high-performance platform that empowers all teams to manage Feature Flags, Experimentations, Entitlement, etc. For example:

-	Reduce delivery risk by progressively releasing features to targeting users without redeployment.

-	Measure the impact of features’ rollouts and run A/B tests to improve feature quality.

-	Enable Sales and CS to close more deals with demos and feature trials at the push of a button.

-	Give Marketing the ability to fine-tune target audiences, manage customer programs, etc.

-	More use cases at https://featbit.medium.com/introducing-featbit-e0cef61572a.

## Useful links

- Main GitHub repo: [https://github.com/featbit/featbit](https://github.com/featbit/featbit/issues)

- To learn how to use FeatBit, you can visit [**FeatBit's documentation page**](https://featbit.gitbook.io/docs/)

- If you met issues, you can report it to our [**Issues page**](https://github.com/featbit/featbit/issues)

- If you have further questions and want to contact us, you can join [**FeatBit Slack Channel**](https://join.slack.com/t/featbit/shared_invite/zt-1ew5e2vbb-x6Apan1xZOaYMnFzqZkGNQ) 

## Getting Started

You can launch all the docker containers by docker compose, all the images are available on [docker hub](https://hub.docker.com/u/featbit).

Before launching FeatBit, make sure you have git and docker installed. Then do the following steps:

Clone the repository to your server or local machine and boot up the services.
```
git clone https://github.com/featbit/featbit
cd featbit
docker compose up -d
```
Once all containers have started, go to FeatBit's portal [http://localhost:8081](http://localhost:8081) and use the default credentials to log in.
- username: **test@featbit.com**
- password: **123456**

**Attention** : with the default configuration, the UI is accessible only from the local machine (on which you have run docker compose), please read [the doc](https://featbit.gitbook.io/docs/installation#attention) to make it accessible publicly.

## Tech Stack

◆  [Architecture](https://featbit.gitbook.io/docs/tech-stack/architecture) - Architecture of FeatBit.

◆  [Benchmark](https://featbit.gitbook.io/docs/tech-stack/benchmark) - More detailed reports on FeatBit's benchmark test. 

## License

FeatBit is under the MIT license. See the [LICENSE](https://github.com/featbit/featbit/blob/main/LICENSE) file for details.
