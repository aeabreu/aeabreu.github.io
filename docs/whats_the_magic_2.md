
# What is the magic?: a good document

You may have come across this diagram at Dropbox ([courtesy of Diataxis](https://diataxis.fr/)) suggesting that all technical documentation falls into one of four categories:

* [Tutorials](#Tutorials),
* [How-to Guides,](#How-to-guides)
* [Explanations](#Explanation), or
* [References](#Reference).

This is a helpful IA idea, but each of these categories deserve some explanation. And here’s is some top-notch analysis from I’d Rather Be Writing:

[https://idratherbewriting.com/blog/what-is-diataxis-documentation-framework](https://idratherbewriting.com/blog/what-is-diataxis-documentation-framework) 

![](media/what_is_the_magic_features_of_good_docs_part_2_/image_1.png)

[https://www.youtube.com/watch?v=p0PPtdRHG6M](https://www.youtube.com/watch?v=p0PPtdRHG6M) 

Or, if you have the time and interest, this disarming writer from Django explains the idea very well. I’ll borrow his great cooking metaphor below.

### Tutorials

Tutorials are **guided lessons by an expert teacher for a beginner**. Think of it like teaching a child to cook. It doesn’t matter that the user isn’t a pro at the end, but the process should inspire confidence and help the user see the usefulness of what they’ve done.

[https://www.gatsbyjs.com/docs/tutorial/getting-started/part-1/](https://www.gatsbyjs.com/docs/tutorial/getting-started/part-1/) 

I love that Gatsby includes a video in this example, placed below the introduction and offering the experience of a live teacher for the user to follow along.

* Oriented toward the user’s learning process rather than a specific task.
* Offers practical, action-oriented knowledge, not theoretical knowledge or context. Learning proceeds from the particular to the abstract.
* Content must be repeatable, and it must always work as described.
* Don’t distract with options or alternatives.
* Make a learner into an enthusiastic user.

### How-to guides

Guides are step-by-step **directions to achieve a specific end**. These are like recipes, presenting the solutions to tasks your user will be looking to complete.

[https://www.twilio.com/docs/flex/end-user-guide/dialpad-use](https://www.twilio.com/docs/flex/end-user-guide/dialpad-use) 

Notice the docs that support this how-to guide in the left sidenav. Reference docs are readily available, and there’s a page on keyboard shortcuts to make an interested user a power user.

* Problem oriented and goal oriented.
* In how-to guides, the user knows the problem and is seeking the solution. Not typically for first-time users.
* Must contain listed steps to follow.
* Guides are not explanations. They should be action oriented.
* Built with flexibility so that steps may be applied to similar problems.

### Explanation

Explanations are **discussions presented to clarify the history or subtleties of a topic**. This is like [a book about cooking](https://www.amazon.com/Catching-Fire-Cooking-Made-Human/dp/0465020410/ref=asc_df_0465020410/?tag=hyprod-20&linkCode=df0&hvadid=312090128349&hvpos=&hvnetw=g&hvrand=3946481143853556325&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1014226&hvtargid=pla-491669019510&psc=1) as a practice.

[https://aws.amazon.com/cloudops/monitoring-and-observability/?whats-new-cards.sort-by=item.additionalFields.postDateTime&whats-new-cards.sort-order=desc&blog-posts-cards.sort-by=item.additionalFields.createdDate&blog-posts-cards.sort-order=desc](https://aws.amazon.com/cloudops/monitoring-and-observability/?whats-new-cards.sort-by=item.additionalFields.postDateTime&whats-new-cards.sort-order=desc&blog-posts-cards.sort-by=item.additionalFields.createdDate&blog-posts-cards.sort-order=desc) 

This example explains AWS Observability, a concept that justifies the CloudWatch service. Notice the “Related services” section ties this concept directly to existing services.

* Oriented toward deeper understanding, illuminating the history or discussion around a topic.
* Suggest alternative approaches or different ways of thinking about a use case or technical problem.
* Help readers make connections between related concepts, and form a better understanding of a tool apart from the hardware.

### Reference

Reference guides are **designed to describe componenets in a system**. These are like encyclopedia entries for the ingredients in a recipe.

[https://stripe.com/docs/api/events/object](https://stripe.com/docs/api/events/object)

Notice all these objects and endpoints are on a single webpage, so all can be readily searched. Notice that summary information is not included here, just a link to the “related guide” where that more specific context resides.

* Technical descriptions of software or hardware (key classes, functions, endpoints). These are code determined. Reference doc structure should mirror the structure of the codebase.
* Information oriented. Should list existing components, but not the place for tasks or context.
* Consistent simple formatting and tone.
* Accuracy and being up-to-date are the highest priorities.
* To many developers this is the primary, sometimes only doc.

# Applying this idea

It may be too much to go back through old documentation to convert the material to these types. It can be enough to [approach new and updated content with these categories in mind](https://diataxis.fr/how-to-use-diataxis/) so that order emerges over time.

These documentation principles aren’t dogmatic. They work best as guide rails, not hurdles. Intent can be more effective than strict rules. Content is flexible so principles should be too, because there are often a number of ways to achieve a successful outcome. 

