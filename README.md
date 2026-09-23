# Bun 1.4 and Coding Agents

Article: [Bun 1.4](https://bun.com/blog/bun-v1.4)

What I find most interesting about Bun 1.4 is how Jarred used coding agents to help pull off the rewrite from Zig to Rust. He goes into more detail in [his post about the rewrite](https://bun.com/blog/bun-in-rust). Rewriting a project as big as Bun is already a huge task. Seeing agents help with that kind of work makes me rethink what they are capable of. I'm inspired by how he uses agents while finding ways to verify their work and build confidence in the results.

## Ryan's Comment
the verification part is very interesting. coding agent can make a rewrite much faster, but in a project like Bun, small mistakes can have heavt consequences. As agents get better at coding, it seems that the role of the engineer is shifting to designing good tests and reviewing output and reviewing the generated code. 
