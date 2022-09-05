### Ann Hancer

Web applications serve billions of clients across various business domains. Spring has dominated web applications with developer-friendly programming features to ease web development, which creates an eager need of static analysis to detect bugs and vulnerabilities in Spring web applications. Call graph generation is the foundation of inter-procedural static analysis. However, to the best of our knowledge, no previous call graph generation approach supports the feature of annotations which are commonly used in Spring web applications. Fortunately, Spring annotations contain valuable semantics that can help enhance call graph generation.

In this paper, we first conduct an in-depth empirical study on 104 annotations, and find that 74 annotations in three categories can be used to enhance call graph generation via adding missing calls or pruning spurious calls. Inspired by our study, we then propose ANNHANCER to enhance call graph with the help of annotation usages. Experiments on 10 Spring web applications have demonstrated that ANNHANCER can add 229 direct missing calls and prune 58 direct spurious calls for a project with high accuracy.

The paper has been submitted to ICSE 2023.
