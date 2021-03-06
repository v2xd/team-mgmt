# Kanban - How work gets organized (a tl;dr;)

The IPFS Org follows a Quarterly Planning schedule based on [OKRs](OKR). Within each quarter, work gets tracked using Github and Kanban boards, using Waffle.io.

- Github is used for discussions and track current endeavours.
- Waffle gives us a [Kanban](https://en.wikipedia.org/wiki/Kanban) view over the work at hand.

![](https://ipfs.io/ipfs/QmWNd86qtjyFnygSAHkZDy4fUB1WnRa4WNt8gt1rSiq7of)

In the Waffle board, we have 4 columns:

- **Inbox** - New issues or PRs that haven't been evaluated yet
- **Backlog** - Issues that are blocked or discussion threads that are not currently active
- **Ready** - Issues Ready to be worked on
- **In Progress** - Issues that someone is already tackling. Contributors should focus on a few things rather than many at once.
- **Done** - Issues are automatically moved here when the issue is closed or the PR merged.

You can learn about existing [Kanban boards in the README](README.md#kanban)

## Issue labels and how to use filters

We use labels to tag urgency and the difficulty of an issue. The current label system has:

- `difficulty:{easy, moderate, hard}` - This is an instinctive measure give by the project lead or leads. It is a subjective best guess, however the current golden rule is that an issue with difficulty:easy should not require more than a morning (3~4 hours) to do and it should not require having to mess with multiple modules to complete. Issues with difficulty moderate or hard might require some discussion around the problem or even request that another team (i.e go-ipfs) makes some changes. The length of moderate or hard issue might be a day to ad-aeternum.
- `priority (P0, P1, P2, P3, P4)` - P0 is the most important while P4 is the least.
- `help wanted` - Issues perfect for new contributors. They will have the information necessary or the pointers for a new contributor to figure out what is required. These issues are never blocked on some other issue be done first.
