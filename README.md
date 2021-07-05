# Executive Overview
The process of Cloud Adoption can be a daunting one, requiring both high-level strategic thinking and detailed, execution level understanding. Over the last few years there has been an explosion of offerings in the cloud arena, everything from Cognitive Services providing AI and Computer Vision through to the lowly Web Application Firewall. This leads us to the problem of how to develop a cloud strategy that is both meaningful to non-technical stake holders, but also useful to those tasked with its implementation.

We often see that big ideas can easily become detached from reality while an overly delivery focused agenda can be myopic in its scope. We can spend our time producing beautiful slide decks, detailed project plans and delightfully complex business process diagrams, but the problem with these approaches is that you still end up with a high risk of “Failure to Implement”. Their weakness, when used to drive a Cloud Transformation, is that they are typically very poor at delivering the following key requirements:

1. Easy to understand.
2. Able to encompass a strategic vision.
3. Technically meaningful.
4. Able to explain the implementation process.
5. Drive consistency of approach where appropriate.
6. Describe the skills required to develop and manage the platform.
7. Able to remain relevant and up to date.

Once technical and business requirements have been considered and worked through, how do we then communicate this within the organisation in a meaningful way? Several clients we have worked with have benefited from the following approach to “Cloud Capability Modelling”, in one instance still benefiting from and enhancing the original vision 4 years into their Cloud Transformation programme.

# Introduction
The purpose of this document is to introduce an approach that I have been using with clients over the last four years to help address the issues above. The approach is intended to work alongside a “Cloud First” strategy, so you may recognise parts that have been “borrowed” from traditional approaches, and some may be new to you. The goal of this document is to help you build a vendor agnostic capability model.

As with all sensible methodologies, you have the freedom to pick and choose the parts that you think are useful. There is only one golden rule “If you can’t draw it, you can’t build it.”

# Step 1: Gathering the required capabilities
From a cloud perspective there are several key capabilities that are considered as standard, which include things like Authentication, Operations Management, Secure Communications etc. It is recommended that you arrange a small number of meetings with stakeholders and IT staff to ensure that the list of requirements is complete and aligns with the business strategy going forward. Getting people to write the capabilities that they need on Post-It notes and put them on a wall is my preferred approach.

Next, work through the Post-It notes to remove duplicates or fine distinctions, and try to merge items that don’t materially impact the strategy or are technically identical. We’re trying to add simplicity at this stage. If your organisation has a universally known tool that isn’t going to be replaced any time soon, put it in, as it will help people understand what’s being designed.

Don’t worry if you’ve missed some as this is intended as a living document. Finally, under no circumstances use this as an opportunity to select products or services. The credibility of the Cloud Capability Model rests on its objectivity, and you don’t know what the best tools are at this stage.

Appendix A has a “Straw Man” list of capabilities to get you started, so feel free to crib from this list. I would recommend that you don’t rush to exclude items though, including something like Machine Learning in your strategy is sensible, even if you don’t have an immediate need for it.

# Step 2: Draw Out “Cloud Capability Model” Version 1
Use of a design or presentation tool is required here. Follow your own approach – what you are aiming for is something visually appealing. Typically I would use Visio, though PowerPoint or Adobe In-Design could be used. See Appendix B for an example.

We can now use colours to separate out the location of services. Also, where a capability is present now, colour it in grey to denote its existence. Don’t be afraid to work in A3 or A2 sizes. Once drafted, we would look to gain agreement that this is what was discussed and then seek executive approval of the “Cloud Capability Model”. Explain that this is not going to be used to start a grand cloud roll-out process, merely a considered vision of the future. After all, if you don’t know where you are going, how can you get there?

Loop around this step until all parties agree, or at least until you have sign off. At this stage, I would recommend printing of a large/full-size copy to mount in a prominent location.

# Step 3: Shortlist of Projects and Technologies
The next task is to go through your upcoming project list and identify, for example, your top 3 projects that will use the new architecture. These first 3 will be used to draw out the stages you will go through as part of your Cloud Transformation.

Each project will have dependencies on certain technologies:

*Phase 1* A Data Warehouse project may need to utilise a Relational Data Warehouse, Semantic Layer, Data Lake, Orchestration Engine, Bulk Loading technology, Dashboarding and Ad-hoc Analytics.

*Phase 2* A “Customer BOT” project may need a Relational Database, BOT Service, Language Understanding, B2C Authentication and Integration with your existing CRM system.

*Phase 3* An IOT solution may require Edge Compute, Stream Analytics, Big Data Store, Device Management, Time series Analytics, Machine Learning and Dashboarding.
Each cloud vendor publishes several “Reference Architectures”, and these can help you identify suitable approaches. 

When building architectures on Azure, please visit the Azure architecture centre.

Note: The first project will need to enable key security, management and communications capabilities (AKA “a scaffold”). It’s therefore advisable to not pick an overly complex project for your first.

# Step 4: Cloud and Service selection
Once you are satisfied that your Shortlist of Projects and Required Technologies is complete, it’s time to select your cloud vendor(s) and appropriate services. Depending on your organisations purchasing practises, you may have to either carry out a competitive tender or simply make a shortlist and select from that. My recommendation here is to bear in mind three key things:

Do not select different technologies between projects. We are looking for consistent technology choices for each requirement. e.g. Do not use a Microsoft Orchestration engine on one project and Amazon’s on another.
You should consider sacrificing “best in class” for simplicity and consistency of vendor and experience. You wouldn’t mix Lego with Meccano unless you had good reason.
If you do decide to adopt a multi-cloud approach, carefully consider “Data Egress Costs” and performance implications. All cloud providers will charge you for moving data out of their service. So, don’t have your data lake with a separate vendor to your big data compute because it could be expensive and slow.

# Step 5: Updating your Cloud Capability Model
Once you have made your service selection, work through each project in your list to produce a Cloud Capability Model for them. Use what you know about the required capabilities and associated data flows for each project to develop a variant of the Cloud Capability Model created in Step 2. You may want to use a colour to denote the new capability being “Activated”; I’ve chosen red. Also include the name of the product or service chosen in bold.

Once you have documented a Phase, duplicate the diagram and use it as the basis of the next. Remove the Data Flows and change the red-coloured capabilities to grey.

See examples in Appendix C, D & E to see the progression through three phases of the Cloud Transformation Program.

# Step 6: Keeping the program on-track
By developing your Cloud Capability Model and subsequent three phases you should look to entrench this approach with subsequent phases (Projects).

My recommendation is to use a “Technical Design Authority” as your primary means of ensuring subsequent development does not break with the approach or “backslide” to non-strategic point solutions. Any new project should be accompanied by its own version of the Cloud Capability Model.

For clarity, a Technical Design Authority is a group of skilled technologists and architects who convene to approve or decline projects based on several factors. In this instance, adoption of and adherence to the strategy laid down in the Cloud Capability Model.

Finally, to focus peoples’ minds on the Cloud Adoption program, I would recommend that you maintain and display a “Current” Cloud Capability Model which includes all the components that have been selected over the agreed phases. See Appendix F for an example showing the “state of play” after Phases 1,2 and 3.

# Skills and Training
This phased approach can also aid in terms of identifying which skills will be required at which stages of a program. By clearly showing the technologies that have been selected you should also be able to produce a list of required skills. You will, I hope, see a reduction in the number of non-standard projects thereby reducing the overall skills required.

# Downloads
We hope that this approach will prove to be as useful to you as it has been for our customers. You will also find a download of the Visio diagram used in this article:
CloudCapabilityModelv1 – PDF
https://github.com/sarmory/CloudCapabilityModel/blob/main/CloudCapabilityModelV1.pdf
CloudCapabilityModelv1 – Visio
https://github.com/sarmory/CloudCapabilityModel/blob/main/CloudCapabilityModelV1.vsdx
