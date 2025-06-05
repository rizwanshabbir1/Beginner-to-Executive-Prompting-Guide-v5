---
position: 2211
title: Appendix B Risk And Security For Prompting
---

## Appendix B: Risk and Security for Prompting

SHADOW AI & UNAUTHORIZED TOOLS

Let's begin with a growing challenge many organizations face: shadow AI.

Shadow AI refers to the use of unauthorized AI tools by employees without proper security vetting or organizational approval. It's similar to "shadow IT"—when employees use personal cloud storage or unapproved apps for work purposes—but with additional risks specific to AI.

This typically happens when employees discover convenient AI tools that solve immediate problems. Perhaps your company's approved AI tool is slow or struggles with specific tasks. Possibly, your organization hasn't yet provided an official AI solution. In these situations, employees often turn to public, consumer-grade AI tools, such as free chatbots or image generators, to get their work done.

While this may seem harmless, consider the following real-world example: In 2023, several major companies, including Samsung and Apple, discovered that employees had inadvertently leaked confidential code when using public AI chatbots. The

employees needed help debugging code and didn't realize that everything they shared was potentially being stored and used to further train the AI system. This not only exposed proprietary information but also created potential legal vulnerabilities around

intellectual property.

Shadow AI becomes particularly risky because many employees don't realize that information shared with these systems may be:

- Stored indefinitely
- Used to train the AI further
- Potentially accessible to the vendor's employees
- Not covered by your organization's data protection agreements
Rather than simply circumventing official channels, employees should document capabilities they need but don't currently have access to. This helps organizational leaders understand gaps in their AI strategy and address legitimate business needs through properly vetted tools.

SECURITY VULNERABILITIES IN AI USAGE

Beyond shadow AI, there are several security vulnerabilities to be aware of when using AI tools—even authorized ones.



First, be conscious of data leakage through prompts. Every piece of information you include in a prompt to an AI system could potentially be exposed. This includes customer data, employee information, financial details, or strategic plans. Before sharing information with an AI system, ask yourself: "Would I be comfortable with this information appearing on a public website?" If not, reconsider what you're sharing.

Second, understand that AI systems can sometimes reveal their training data. This phenomenon, known as "training data extraction," means that with carefully crafted prompts, someone may be able to extract the actual content on which the AI was trained. If your organization's confidential information was inadvertently included in that training data, it could potentially be extracted.

Third, recognize that interactions with AI are often more permanent than conversations with colleagues. While a verbal question to a coworker disappears after it's answered, information shared with AI systems may be logged and stored according to the vendor's data retention policies. This creates a longer vulnerability window for sensitive information.

Fourth, consider access controls. Who in your organization can utilize AI tools, and what guardrails are in place? Unrestricted access without proper training increases risk. Just as you wouldn't give everyone admin access to critical systems, consider appropriate access levels for powerful AI tools.

Take a moment to reflect: What types of information have you or your colleagues shared with AI systems recently? Would any of that information be concerning if it were exposed outside your organization?

UNINTENDED CONSEQUENCES OF AI IMPLEMENTATION

Security isn't just about data protection—it also involves understanding broader risks and unintended consequences of AI use.

Automation bias is a significant concern. This occurs when people give undue weight to AI-generated information simply because it appears to come from a seemingly objective computer system. In business contexts, this can lead to a decrease in critical thinking and an over-reliance on AI recommendations without proper scrutiny. Remember that AI tools are designed to be helpful and provide answers even when they should express uncertainty.

There's also the risk of skill atrophy. As teams become increasingly dependent on AI for tasks such as writing, analysis, or creative work, they may lose proficiency in these

fundamental skills. Organizations should consider which capabilities need to be maintained internally, regardless of the advancement of AI.



Customer and client perception issues can arise when AI is used without transparency. If clients discover that their communications were drafted entirely by AI or that automated systems addressed their concerns without human review, this could damage trust—mainly if errors occur. Being transparent about the use of AI in customer interactions is increasingly important.

Ethical considerations extend beyond immediate security concerns. AI systems can perpetuate or amplify existing biases, potentially leading to discriminatory outcomes in hiring, customer service, or product development. Without proper oversight, these issues might go unnoticed until they cause reputation damage or legal problems.

Finally, consider compliance risks specific to your industry. Healthcare organizations must ensure AI use doesn't violate HIPAA. Financial institutions must consider regulations surrounding automated decision-making. Government contractors may have restrictions on the locations where they process data. These regulatory requirements should inform your approach to AI security.

SAFE & COMPLIANT PROMPTING

Let's now discuss how to craft prompts that maintain security and compliance—the concept of "safe prompting."

First, develop clear guidelines about what should never be included in prompts to AI systems. This typically includes:

Personally identifiable information about customers or employees Financial account details or access credentials

Proprietary business strategies or trade secrets Confidential contract terms or negotiations Protected health information

Information covered by non-disclosure agreements

When working with sensitive information that requires processing by AI, utilize anonymization techniques. Replace actual names with generic identifiers. Change specific dates while maintaining relative timeframes. Modify unique identifiers, such as account numbers, while preserving the existing pattern. Alter specific dollar amounts while maintaining proportional relationships.



For example, instead of saying: "Customer Jane Smith (account #12345) complained about our premium service on March 15th, stating the $1,299 annual fee was too high compared to competitor XYZ's offering..."

You could rephrase it as: "A customer expressed concerns about our premium tier pricing, noting it was higher than a competitor's similar offering..."

Consider creating templates for everyday AI interactions that employees can adapt to their needs while maintaining compliance. These pre-approved prompt structures can guide proper use while reducing security risks.

For teams that regularly use AI with sensitive data, establish a peer review process for prompts dealing with high-risk information. Having a second set of eyes review prompts before submission can catch potential data leakage issues.

Finally, remember that complex prompts requiring detailed context can often be restructured to maintain effectiveness while reducing risk. Focus on the specific question or task without revealing unnecessary background information.

To summarize, AI security extends beyond technical measures to include how everyday business users interact with these powerful tools. By understanding shadow AI risks, being aware of security vulnerabilities, considering unintended consequences, and practicing safe prompting techniques, you can help protect your organization while still reaping the benefits of AI capabilities.