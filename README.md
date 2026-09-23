# Bun 1.4 and Coding Agents

Article: [Bun 1.4](https://bun.com/blog/bun-v1.4)

What I find most interesting about Bun 1.4 is how Jarred used coding agents to help pull off the rewrite from Zig to Rust. He goes into more detail in [his post about the rewrite](https://bun.com/blog/bun-in-rust). Rewriting a project as big as Bun is already a huge task. Seeing agents help with that kind of work makes me rethink what they are capable of. I'm inspired by how he uses agents while finding ways to verify their work and build confidence in the results.

### Tony Zhou's Comment

I found this interesting because rewriting a large project like Bun is already very difficult, and using coding agents adds another layer of complexity. What stood out to me is that the agents were not just used to generate code, but also had to be checked and verified carefully. I think this shows that AI can be very useful for large software projects as long as developers still understand the code and make sure the results are reliable.

— Tony Zhou

## Ryan's Comment
the verification part is very interesting. coding agent can make a rewrite much faster, but in a project like Bun, small mistakes can have heavt consequences. As agents get better at coding, it seems that the role of the engineer is shifting to designing good tests and reviewing output and reviewing the generated code. 

## Comment from Victor Derani

I found this article interesting because it shows how much engineering work can go into improving the performance and compatibility of a development tool. I was especially interested in Bun's effort to become more compatible with Node.js while also reducing memory and CPU usage and improving startup speed.

## Comment by GoodrainCN

I also found the use of coding agents in Bun's rewrite interesting. It shows how AI can help developers handle large amounts of work, but careful review is still important to make sure the results are reliable.

### Jiaming
This is a very inspiring article. The Zig to Rust rewrite proves that coding agents can feasibly migrate giant codebases. At that scale, it is more important to review the migration pipeline than reviewing the 1 million line diff.
