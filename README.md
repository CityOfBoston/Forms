# Forms
A list of City of Boston Forms, along with some related data and project notes.

We're working to eliminate all paper forms and pdfs in the City of Boston. If you want to come to City Hall to do business with us, we'll be here for you. But if you *have* to come to City Hall to do business with us, then we're not doing our job. This is where we are storing a database of files, owners, and status documents. There's no real code, but since we integrate so closely with the web team, it helps to keep it in the same place. 

# How we use this repo

Visit the issues sections. Each issue represents a paper, pdf, or web form. Comments and labels provide more information about that form and indicate it's status in the process. Closed issues represent forms successfully moved online. 

If you have any questions, please contact joshua.gee@boston.gov.

# Project History

When we started, we didn't even have a list of what forms residents can fill out. We had to start with a scrape of the website for all pdf files. That, plus interviews with departments and reviews of other documentation helped us pull together a list. Even with months of auditing, we're still finding new forms every day. 

Early in the process, we went through a bid process for a web form tool. We solicited three bids and procured a partner, 
[SeamlessDocs](https://www.seamlessdocs.com), as part of a pilot program. Our goal in the pilot was to move fast and learn. We weren’t trying to fix every department’s process but to focus on the customer experience and eliminating paper forms and pdfs. We've uploaded a copy of our bid document which you should feel free to use or modify if you're attempting a similar project.

# Things we learned

* There is huge demand to move forms online in the departments;
* we initially thought there would be a strong demand for submissions that look exactly like current paper forms. That hasn't been the case. 
* departments almost immediately asked for tools to help them move to all-digital processes; 
* we've avoided getting into workflow changes, but there is a growing need for a workflow tool; 
* functionality around conditional fields, logic, and branching are really important;

# Where we are going

We've learned that not all forms are created equal. Some are simple, but most of them are either interrelated or kick off complicated business processes. Just moving those online isn't much help. Some are really also better served as applications. A good example is death certificates. After learning more about the process, we realized that a [form](https://github.com/CityOfBoston/Forms/issues/230) isn't a good solution since we wanted to give residents the ability to look up and order a certificate once they knew we had it (Right now, they request a record blind). So we are building [an entire application](https://github.com/CityOfBoston/registry-certs/) that allows residents to look up and order death certificates. 

As we expand, we'll need both a tool for building forms and a flexible workflow tool into which information from simple forms and web applications can be fed. We've done some analysis, and are working on an RFP around that. Since that's a bigger project, we're currenctly coordinating among multiple stakeholders to release the RFP. 

However, the pilot has also shown us we'll always need the ability to quickly and easily create branded forms. 
