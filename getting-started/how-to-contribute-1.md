# How to contribute?

That's amazing that you reached this page!

Memphis is and always will be open-source and community-driven. Our community is our power.

### Why you should become a contributor?

{% hint style="info" %}
"Working on Memphis helped me earn many of the skills I later used for my studies in university and my actual job. I think working on open source projects helps me as much as it helps the project!"
{% endhint %}

Contributing to open source can be a rewarding way to learn, teach, and build experience in just about any skill you can imagine.

Whether it’s coding, user interface design, graphic design, writing, or organizing, if you’re looking for practice, there’s a task for you on an open-source project.

### 1. Establish memphis dev environment

&#x20; 0\. Join to Memphis [discord](https://discord.gg/WZpysvAeTf) channel

&#x20; 1\. Fork Memphis [broker](https://github.com/memphisdev/memphis-broker)

&#x20; 2\. Clone the forked repo to your local station

&#x20; 3\. Run a local memphis-mongodb using docker

```
curl -s https://memphisdev.github.io/memphis-docker/docker-compose-mongo.yml -o docker-compose-mongo.yml && docker compose -f docker-compose-mongo.yml -p memphis up
```

&#x20; 4\. Install broker dependencies - enter the cloned directory and run

```
go get -d -v .
```

&#x20; 5\. Run the broker in debug mode (If you're using an IDE like vscode, click F5)

### 2. You are

* [Frontend Developer](how-to-contribute-1.md#frontend-contributions)
* Backend Developer
* Data Engineer
* DevOps
* QA

### Frontend Contributions

&#x20; 1\. The source files of the UI can be found in a directory called ״[ui\_src](https://github.com/memphisdev/memphis-broker/tree/master/ui\_src)״

&#x20; 2\. Navigate to "ui\_src" dir

&#x20; 3\. Install dependencies by running `npm install`

&#x20; 4\. Run the UI locally by running `npm start`

&#x20; 5\. Start coding!

&#x20; 6\. Once done - push your code and create a pull request to merge your updates with memphis main repo