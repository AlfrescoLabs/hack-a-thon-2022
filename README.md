# Alfresco Global Virtual Hack-a-thon 2022

## Instructions

**For people with a project idea**

For each project, you should consider addressing the following:

* The idea owner(s)
* A brief description
* Any prep work for the project, such as developer tools or skills participants should understand

We encourage you to keep your project idea short and provide any additional details in separate document or blog post within the Collaborate space. This may also allow you to coordinate with potential team members via the comments there without being mixed in with any discussions on this page.

**For people looking to join a project**

Please feel free to add your name to any project(s) you are interested in participating. Don't hesitate to add your name to multiple projects if you are considering multiple at this point. We encourage you to use this platform to contact the owner of an idea to discuss any details you are unsure about or even improve upon the idea.

Apart from any plans you make with the owner of an idea, you are not bound to actually participate in the project you indicated here. When you join the hack-a-thon on the day of the event you can check with other project teams and join a different project, if that turns out to be a better fit for you.

**For everyone**

The global virtual hack-a-thon is as much a social event as it is a coding one. This means a lot of the attendees for this event often use it to exchange ideas and discuss other matters in the general Alfresco context. To do this, everyone that attends the global virtual hack-a-thon should be prepared to join any of the commonly used communication channels for this event. In the past the main tools have been the IRC chat #alfresco (via chat.alfresco.com or a desktop client) and Google Hangouts.

After the event has come to an end, we encourage everyone that worked on a specific project idea to update the listing on this page with an overview of the project team and a link / reference to the results of the project (e.g. a GitHub repository, document or blog post in this space).

## Projects

### Community Platform / Engagement

**Developing Alfresco using Apple Silicon**

Idea owner: Angel Borroy

Description: The aim of this project is to test Alfresco SDK and Alfresco Docker Images with Apple Silicon computers.

Prep work: Get an Apple Silicon computer!

Result: https://github.com/aborroy/alfresco-dockerx-builder

Interested parties:

* Pavel Titenkov ([@titenkov](https://github.com/titenkov))

--


### Content Services

**Removing Search Services Suggester Temporal Files**

Idea owner: Angel Borroy

Description: When using suggester in Search Services, old temporary files are not removed once the new ones are calculated. A Shell or Job can be developed in order to purge that directory periodically.

Prep work: https://github.com/Alfresco/SearchServices/blob/master/search-services/alfresco-search/src/main/resources/solr/instance/templates/rerank/conf/solrcore.properties#L219

Result: https://hub.alfresco.com/t5/alfresco-content-services-blog/understanding-alfresco-auto-suggest-feature/ba-p/311162

--

**Animated GIF using Alfresco Transformer**

Idea owner: Tom Page

Description: Integrate FFMeg software with Alfresco by using the new Transform Service structure.

Prep work: https://github.com/Alfresco/alfresco-helloworld-transformer

Result:

* https://hub.alfresco.com/t5/alfresco-content-services-blog/hackathon-project-animated-gif-transformer/ba-p/311115
* https://github.com/tpage-alfresco/animated-gif-transformer

--

**Continue Work on Fork of JavaScript Console into OrderOfTheBee Support Tools**

Idea owner: Axel Faust

Description: During the last hack-a-thon, work was started on forking the JavaScript Console addon and integrate it into the OrderOfTheBee Support Tools. There still is work left to be done to adapt the code base (i.e. Share client files) to the project's standards / code format, and ideally optimise / clean it up. Due to high load of project work for business, I did not manage to work on that much in the last couple of months, and want to use the hack-a-thon to continue it now...

Prep work: https://github.com/AFaust/ootbee-support-tools/tree/feature/js-console-fork


### Process Services

**Finalizing and improving APS SDK 2.x**

Idea owner: Piergiorgio Lucidi

Description: The aim of this project is to finalize the development of APS SDK 2.x. The new branch is started but we need to work together for collecting feedbacks, ideas and contributions. The overall goal is to let developers to be focused only on their implementation project and not in setupping Maven modules of Alfresco. 

Roadmap:
* Add support for APS 2.x (2.0.1 and 2.1.0)
* Add a new Maven module to generate the Java Swagger client (for all the APS versions)
* Add a new Maven module for integration tests
* Add an example of integration test

Prep work: Fork the APS SDK project and checkout the branch 2.x:
https://github.com/OpenPj/alfresco-process-services-project-sdk/tree/2.x
