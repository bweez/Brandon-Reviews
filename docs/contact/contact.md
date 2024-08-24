# Contact Me

I'd love to hear from you! Whether you have feedback, questions, or ideas for new content, there are a few ways to get in touch:

## Leave a Comment
You can share your thoughts directly on each blog post by leaving a comment using our [comment system](comments.md). 

## Submit a Pull Request
If you're familiar with GitHub, feel free to contribute directly! Check out our [guide on submitting a pull request](pull-requests.md) to get started.

## Email
Prefer to send a private message? You can reach me at [brandonwebdev@gmail.com](mailto:brandonwebdev@gmail.com).

Looking forward to connecting!

## Prompt

**You said:**
I want to build a Contact me page for my blog.  I was considering figuring out how to add comments to blog posts within a mkdocs page.  Another thought was to just let people submit pull requests, but that may be too much to ask of a casual reader.  It would be simple to create an article to with instructions on creating a pull request.

**ChatGPT said:**

It sounds like you're weighing the pros and cons of how to engage with your readers on your blog. Let's break down your options:
1. Adding Comments to Blog Posts in MkDocs

    Pros:
        Direct Reader Engagement: Allowing comments lets readers easily share their thoughts, feedback, and questions directly on the blog posts.
        Community Building: It fosters a sense of community where readers can interact not only with you but also with each other.
        SEO Benefits: User-generated content like comments can positively impact your SEO by keeping your pages updated and relevant.

    Cons:
        Implementation Complexity: Adding comments to MkDocs isn't as straightforward as it is with other platforms like WordPress. You'll likely need to integrate a third-party service (e.g., Disqus, Utterances for GitHub issues).
        Moderation: Managing and moderating comments can be time-consuming, especially if spam becomes an issue.

2. Allowing Pull Requests

    Pros:
        Collaborative Contribution: This approach encourages readers who are familiar with GitHub to contribute directly, making your blog more of a collaborative project.
        Version Control: Pull requests make it easy to track changes, review contributions, and maintain the quality of your content.

    Cons:
        Technical Barrier: Expecting casual readers to submit pull requests could be a high barrier, potentially discouraging engagement.
        Limited Audience: Not everyone is comfortable with GitHub, so you might miss out on feedback from non-technical readers.

3. Creating an Article on How to Submit a Pull Request

    Pros:
        Educational Content: You'd be providing value by teaching your readers a useful skill—how to use GitHub and submit pull requests.
        Encourages Engagement: It could lower the barrier for those who are interested but not familiar with the process.
    Cons:
        Reader Commitment: Even with instructions, some readers may find the process too cumbersome and choose not to engage.
        Content Focus: This approach could shift the focus from your blog's core topics to GitHub tutorials, which may or may not align with your audience's interests.

Recommended Approach

Why not combine these options? Here's a possible plan:

    Use a Comment System: Integrate a simple, lightweight comment system like Utterances (which uses GitHub issues) or Disqus for direct reader engagement. This approach lowers the barrier for casual readers to leave feedback.

    Guide to Pull Requests: Create a dedicated article or page explaining how to contribute via pull requests. This could be a resource linked from your "Contact Me" page or your blog footer. It allows more technical readers to contribute directly to your content.

    "Contact Me" Page: Set up a simple "Contact Me" page where readers can either:
        Leave a Comment: Using the integrated comment system.
        Submit a Pull Request: Link to your GitHub repository with instructions for contributing.
        Email: Provide an email address for more private feedback.

This approach offers flexibility and caters to both technical and non-technical audiences, while also keeping your blog open to collaboration.
Example of a "Contact Me" Page in Markdown

Here's a simple template for your "Contact Me" page:

```markdown

# Contact Me

I'd love to hear from you! Whether you have feedback, questions, or ideas for new content, there are a few ways to get in touch:

## Leave a Comment
You can share your thoughts directly on each blog post by leaving a comment using our [comment system](comments.md). 

## Submit a Pull Request
If you're familiar with GitHub, feel free to contribute directly! Check out our [guide on submitting a pull request](pull-requests.md) to get started.

## Email
Prefer to send a private message? You can reach me at [brandonwebdev@gmail.com](mailto:brandonwebdev@gmail.com).

Looking forward to connecting!

This structure keeps everything simple and accessible while encouraging different forms of interaction.
```