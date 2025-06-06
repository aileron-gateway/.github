<div align="center">

![AILERON Gateway Logo](../logos/logo-light-aileron-gateway.svg)

# :tada: Welcome to the AILERON Gateway Community :tada:

</div>

> [!NOTE]
> **AILERON Gateway — secure, high-performance API Gateway for cloud-native enterprise systems.**

AILERON Gateway leverages [Go](https://go.dev/).

![aileron-loves-go.svg](./aileron-loves-go.svg)

## Documentations

- [Website](https://aileron-gateway.github.io/)
- [Go Docs](https://pkg.go.dev/github.com/aileron-gateway/aileron-gateway)

## Repositories

| Repository | Content |
| - | - |
| [aileron-gateway](https://github.com/aileron-gateway/aileron-gateway) | Main development repository. |
| [aileron-gateway.github.io](https://github.com/aileron-gateway/aileron-gateway.github.io) | Website resources. |
| [example-extension](https://github.com/aileron-gateway/example-extension) | Example to extend the gateway. |
| [.github](https://github.com/aileron-gateway/.github) | Organization profiles. |

**Repository overview.**

```mermaid
block-beta
  columns 3

  Documentation
  block:docs:2
    github["Profile</br><a href="https://github.com/aileron-gateway/.github">.github</a>"]
    githubio["Website</br><a href="https://github.com/aileron-gateway/aileron-gateway.github.io">aileron-gateway.github.io</a>"]
  end
  space:3

  GoProjects["Go Projects"]
  block:go:2
    space
    gateway["Main repo.</br><a href="https://github.com/aileron-gateway/aileron-gateway">aileron-gateway</a>"]
  end
  space:3

  Examples
  block:example:2
    space
    extension["<a href="https://github.com/aileron-gateway/example-extension">example-extension</a>"]
  end

extension -- "use" --> gateway

style Documentation fill:transparent,stroke:none
style GoProjects fill:transparent,stroke:none
style Examples fill:transparent,stroke:none
```

## Integration

We integrate the following products and specifications.

<p align="center" float="left">
  <img src="openid.png" height="100" hspace="30"/>
  <img src="oauth_logo.svg" height="100" hspace="30"/>
  </br>
  <img src="opa.svg" height="100" hspace="30"/> 
  <img src="otel.svg" height="100" hspace="30"/> 
</p>
