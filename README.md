# Online Class "M101J" MongoDB Blog

This is some of the blog content used in the MongoDB University course "M101J", as of the December 2017 iteration. What this project attempts to do is to modernize some of the Java tools, and also utilize the features of MongoDB Community Edition 3.6.

## Getting Started

It appears that the original project (in the MASTER branch) was set up as an Eclipse project. One can try to import the project into a recent version of Eclipse. It utilizes the Apache Maven build tool.  

### Prerequisites

What things you need to install the software and how to install them.

This project can run on any commodity laptop or desktop computer. The principal requirement is a computer which can run an instance of MongoDB Community Edition. We suggest that you have at least 16 Gb of memory, and a sufficiently new Intel-based processor with virtualization extensions turned on, in case you want to run the project from within virtual machines in the future. The project is presented principally as an Apache Maven project, so an understanding of the Maven build tool and the specific archetype being used will be very helpful.

```
MongoDB Community Edition version 3.4.x (The posts collection can likely be installed on 3.6.x and 4.x as well)
Freemarker version 2.3.19
Spark version 1.1.1
Apache Maven 3.1.1 however the most recent available version of Maven is suggested.

```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

To obtain MongoDB Community Server, visit the [MongoDB Download Center](https://www.mongodb.com/download-center#atlas) and click on the Community Server tab. Follow the instructions for installing Community Server on your operating system. This step can take a little while to get the server running exactly right. Whenever possible, prefer an automated package installer tool to manual installation. The automated tools will figure out your settings and customize the environment to work well for the mongod server. Manual installation of the MongoDB binaries can take longer, especially if you are inexperienced in modifying the settings that must be changed.  
```
When the mongod server is up and running correctly, install the posts collection from this repository. 
The collection appears to contain 1000 documents that quote the entire text of the Amnerican Constitution.
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

This Github project was cloned from [thorveakshay](https://github.com/thorveakshay) and was updated by [BobCochran](https://github.com/BobCochran). 
All the original code and blog data was provided by MongoDB, Inc. as part of the training materials for MongoDB University course M101J.
The README was provided in template form by:
* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc

