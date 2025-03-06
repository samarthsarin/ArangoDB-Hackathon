Why we participated:

Our participation in this hackathon was fueled by our passion for innovation and our commitment to solving real-world challenges at the intersection of technology and finance. As someone currently working at a financial organization, I understand firsthand the critical need for timely, actionable insights to drive effective decision-making in the financial world. This application can be solved in the following use cases?

1. Proactive Risk Management: In finance, early detection of global events, such as geopolitical tensions, economic shifts, or emerging crises, is vital for mitigating risk. By leveraging the GDELT dataset’s real-time global news monitoring, we can capture and analyze signals that might indicate market volatility or systemic risks before they fully materialize.

2. Investment Decision Support: The detailed sentiment analysis and event taxonomy provided by GDELT empower us to track what is happening around the globe and how these events are perceived. This nuanced perspective can be instrumental in shaping investment strategies, identifying emerging market opportunities, or foresee downturns in specific regions.

3. Innovative Use of Graph Analytics: By using ArangoDB’s graph capabilities to structure and analyze the interconnected data from GDELT, we can reveal patterns and relationships that are not immediately apparent through traditional data analysis. This approach aligns with the evolving needs in the financial sector where understanding complex relationships, be it between geopolitical events, market movements, or investor sentiment can provide a competitive edge.

These are some impactful use cases from a financial world which have not yet been solved using Knowledge Graphs and LLMs. We participated in this hackathon to showcase real-world impact and demonstrate how combining open-source datasets with advanced analytics can drive innovations that are not just theoretically impressive but also practically valuable, especially for high-stakes environments like the financial industry.

Problem Statement:

Every day, news outlets worldwide publish news reports on conflicts, crises, and significant events. Critical information is often lost in this data – for instance, early signs of social unrest or emerging health crises may go unnoticed until it's too late. Manual monitoring can’t keep up with the sheer volume and velocity of global news.

This lack of timely insight can lead to delayed responses, missed opportunities, or unchecked escalation of crises. Our application tackles this problem by automatically monitoring and analyzing real-world events in real time, distilling actionable insights from worldwide news. The goal is to improve global situational awareness and decision-making



Why we chose this dataset -> we chose the GDELT dataset for its strengths that align perfectly with our application's needs and approach:

1. Real-Time Global Coverage: GDELT monitors news media across virtually every country in over 100 languages, updating continuously (every 15 minutes) with new and updated events​. This ensures our application is fed with information from all corners of the world, not just English or Western sources, providing a truly global perspective.

2. Built-in Sentiment Analysis: The dataset doesn’t only catalog events, but it also captures the sentiment of how each event is reported, essentially measuring how the world is feeling about what’s happening​. This is very important for our application, as we can gauge public sentiment or tension around an issue (e.g. whether a protest is portrayed positively or ominously) in real time. By incorporating this sentiment signal, our tool assesses not only what is happening, but also the emotional and social impact of those events.

3. Comprehensive Event Taxonomy: GDELT classifies events into over 300 categories, ranging from peaceful interactions to violent conflicts​. This rich taxonomy means our application can distinguish between different types of events – for example, differentiating a diplomatic exchange from a protest or a humanitarian crisis. With this granularity, we derive more nuanced geopolitical insights, such as identifying spikes in specific event types (like a surge in protests in a region) or tracking how certain kinds of events (e.g. peace talks vs. clashes) evolve over time.

4. Geographical and Geopolitical Context: Every GDELT event is tied to locations and actors (like countries, organizations, individuals), enabling deep geopolitical analysis. The data provides attributes like geographical coordinates and actor information, so our application can map events on a world map and filter by region or actor. We can highlight, for instance, hotspots of unrest or trace the spread of an issue across borders. This context helps users immediately grasp where and who is involved in a developing story, making the insights far more actionable.

5. Network/Graph Data: GDELT essentially weaves all these entities and events into a massive interconnected graph. It “connects every person, organization, location, etc. and event across the planet into a single massive network/graph” capturing global activity and context​. We leverage this structure by treating the data as a network of nodes and edges: for example, in our application, key entities (like countries or organizations) are nodes and an event linking them becomes an edge. This graph-based approach lets us uncover patterns that isolated events might miss – such as identifying a central influencer that appears in many related events, or discovering clusters/communities of related incidents through shared participants or locations. By using GDELT’s network data, our solution can literally connect the dots between disparate news reports and reveal the bigger picture.

By using an open, well-established dataset like GDELT, we also ensured our project is built on a reliable and scalable foundation, rather than a narrow or proprietary data source. GDELT’s breadth and openness allowed us to focus on innovation – building the analysis and visualization – instead of spending time collecting or licensing data.
