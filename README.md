Questions to ask an engineering organization!

* How big is the engineering team? How many of those are backend or platform?

* What is code review like? How many people review a change? How large are reviews? How much iteration do reviews go through? Do you review small changes? Do junior devs review patches by seniors?

* How is code deployed? How often is code deployed? Who does it? How does engineering verify that nothing broke? How are incidents communicated? How long does a rollback take?

* Who is on call for what? How often do people get paged? If you have a larger rotation and the on call person gets paged for a service they don't directly work on, how might that play out? What is the post-mortem process?

* Walk me through the process of spinning up a new service.
  * Is there an architecture or design review process?
  * How do I get hardware, cloud or otherwise?
  * What's your approach to service discovery?
  * Monitoring and telemetry?
  * Suppose we realize it needs a DB or Kafka. Walk me through that process. Who would I talk to? Is it self-serve? Who is responsible for capacity planning? How does the rollout of that service work -- does the storage team help at all? How are DB migrations handled, reviewed, run, verified?

* Do you ever have the situation where I'm working on service Foo, which depends on service Bar which is owned by another team? Where any degradations or outages Bar experiences will affect Foo. How does engineering approach this scenario? Is a third team (platform/SRE) involved? Are there frameworks or tools to deal with fault isolation? How about tracking such dependencies? How are outages discovered and communicated?

* Tell me how your company might go about changing RPC frameworks. What team or teams might own such a project? Would other teams or developers be involved? How would such a project be communicated? How do you think it would be rolled out?

* Can you tell me about a time a tech debt-introducing change was caught and preempted? How was the change discovered and stopped?

* How does platform measure their success? Tell me about how platform communicates with backend engineers.

* Do people go to conferences? Which people, and which conferences? Do they share what they learned with engineering/their team? Do people give talks at conferences?

* What’s the single biggest issue or problem facing the team/department/company? What’s currently being done to address it? (from https://jvns.ca/blog/2013/12/30/questions-im-asking-in-interviews/)
