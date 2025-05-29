# ld-agent RFCs (Request for Comments)

**Design proposals and architecture decisions for ld-agent**

This repository tracks significant changes to the ld-agent specification, architecture, and ecosystem through a structured RFC (Request for Comments) process.

## What is an RFC?

RFCs are design documents that describe new features, significant changes, or architectural decisions for ld-agent. They provide a consistent and controlled path for community input on substantial changes.

## When to Submit an RFC

Consider submitting an RFC for:

- **New plugin specification features** (e.g., plugin versioning, security model)
- **Breaking changes** to existing APIs or specifications
- **New language implementations** or major implementation changes
- **Ecosystem-wide changes** (e.g., plugin registry format, distribution mechanisms)
- **Architecture decisions** that affect multiple repositories

**Small changes** like bug fixes, documentation improvements, or minor feature additions don't typically need RFCs - just open a PR in the relevant repository.

## RFC Process

1. **Discuss the idea** in [GitHub Discussions](https://github.com/ld-agent/discussions) first
2. **Fork this repository** and create your RFC in `rfcs/0000-your-feature.md`
3. **Submit a pull request** with your RFC
4. **Community discussion** happens in the PR comments
5. **RFC acceptance** by the ld-agent team
6. **Implementation** tracked through regular issues/PRs

## Active RFCs

*No active RFCs yet - submit the first one!*

## Implemented RFCs

*No implemented RFCs yet*

## RFC Template

Use this template for new RFCs:

```markdown
# RFC 0000: Your Feature Name

- Start Date: YYYY-MM-DD
- RFC PR: (leave blank initially)
- Implementation Issue: (leave blank initially)

## Summary

Brief one-paragraph summary of the proposal.

## Motivation

Why are we doing this? What use cases does it support? What problems does it solve?

## Detailed Design

Detailed design of the proposal. Include:
- API changes
- Specification updates  
- Implementation details
- Examples

## Drawbacks

Why should we *not* do this? 

## Alternatives

What other designs were considered? What's the impact of not doing this?

## Unresolved Questions

What parts of the design do you expect to resolve through RFC discussion?
```

## Contributing

1. Fork this repository
2. Copy `0000-template.md` to `rfcs/0000-my-feature.md`
3. Fill in the RFC template
4. Submit a pull request

The RFC will be assigned a number during the review process.

## License

MIT License - see [LICENSE](LICENSE) file for details.

---

**Have a big idea for ld-agent?** Start the discussion in [GitHub Discussions](https://github.com/ld-agent/discussions) first! 
