Now I want to point out something that you might have heard of and discuss a little bit about event

driven architecture and pub sub.

Now event driven architecture is often mentioned with pub sub.

You might have heard about the pub sub architectural style and you might be wondering how exactly it

stacks against the event driven architecture.

Now pub sub, if you are not familiar with this term, basically means publish and subscribe.

And this is a messaging pattern used by the event driven architecture.

So when we are talking about a pub sub, we are looking at an architecture which is very similar to

the event driven architecture, and it also has three components.

And with the pub sub, the components are publisher, broker and subscriber as opposed to producer channel

and consumer found in event driven architecture.

So what is basically the difference between idea and the pub sub?

Well, as we saw, event driven architecture and the pub sub are extremely similar.

So what is the difference between them?

Well, the main difference is that Iida describes the whole architecture of the system, while pub sub

is a messaging pattern used by the system and not exclusively.

That means that your ADA architecture might contain, in addition to event driven components, also

some direct calls such as rest API or similar.

But Pub Sub is a specific component implementing the event driven aspects of the architecture.

So for example, you can definitely say something like this.

My event driven architecture uses mainly pub sub for inter service communication, but I do have some

rest APIs for synchronous queries.

So to sum it up, pub sub is a specific component publishing the event and the idea is the whole architecture

which mainly contains pub sub engines, but again, not exclusively.

So this is the pub sub.


