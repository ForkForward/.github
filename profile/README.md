# ForkForward

**Open code. Moving forward.**

ForkForward continues open-source libraries after their original line of development stops being open. We start from the last version published under a permissive licence, keep its history and its credits, and keep it building on current platforms.

Website and documentation: **[forkforward.dev](https://forkforward.dev)**

- **Developed with AI tools.** Changes are written by AI coding tools and automation.
- **Reviewed by people.** A named maintainer reviews every change and decides what is released.
- **Credit stays with the authors.** Every project says which library it continues, who wrote it, and under which licence. Original copyright and licence notices are never removed.
- **Independent.** ForkForward is not affiliated with, sponsored by, or endorsed by the authors of the projects it continues. If you want their newer versions or commercial support, use the official project.
- **Clean origin.** Nothing is copied from versions released after a licence change.

## Projects

### .NET

| Repository | Documentation | Package | Continues | Status |
|---|---|---|---|---|
| [dotnet-cargo](https://github.com/ForkForward/dotnet-cargo) | [forkforward.dev/dotnet-cargo](https://forkforward.dev/dotnet-cargo/) | [`ForkForward.Cargo`](https://www.nuget.org/packages/ForkForward.Cargo) | MassTransit 8.5.12 (Apache 2.0) by Chris Patterson, Dru Sellers and contributors | Previews on nuget.org |
| [dotnet-mapper](https://github.com/ForkForward/dotnet-mapper) | [forkforward.dev/dotnet-mapper](https://forkforward.dev/dotnet-mapper/) | [`ForkForward.Mapper`](https://www.nuget.org/packages/ForkForward.Mapper) | AutoMapper 14.0.0 (MIT) by Jimmy Bogard and contributors | Stable: 14.1.1 on nuget.org |
| [dotnet-mediator](https://github.com/ForkForward/dotnet-mediator) | [forkforward.dev/dotnet-mediator](https://forkforward.dev/dotnet-mediator/) | [`ForkForward.Mediator`](https://www.nuget.org/packages/ForkForward.Mediator) | MediatR 12.5.0 (Apache 2.0) by Jimmy Bogard and contributors | Stable: 12.8.0 on nuget.org |

## How repositories are named

`<ecosystem>-<project>`, in lower case: `dotnet-`, `js-`, `python-`, `jvm-`, `go-`, `rust-`.

Every repository carries the topic `forkforward`, a technology topic and a function topic. GitHub leaves forks out of search results unless you ask for them, so search like this:

```
org:ForkForward topic:dotnet fork:true
```

## Suggest a library

Open an issue in the repository of the closest project and tell us which library, which version was the last one under a permissive licence, and what you need it for.
