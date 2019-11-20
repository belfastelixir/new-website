# new-website

Initial document for the new [belfastelixir.org](https://www.belfastelixir.org)
website.

## Premise

We want to build a new website for the belfast elixir meetup group for several
reasons:

- [meetup.com](https://www.meetup.com) are now starting to
  [charge](https://www.theverge.com/2019/10/15/20893343/meetup-users-furious-new-rsvp-payment-test)
per RSVP.

- The site is currently just a blog, written in jekyll. It is no longer
  actively maintained.

- We want to add new sections/features to the site that will enhance the
  website for both users and admins easily, which requires more than a 'markup
blog'

## What are the features you want?

We want to replace meetup. Meetup is really, at the guts of it - a website that
allows you send out emails to a particular group and for the recipients to RSVP
to the aforementioned meetup.

So with that thinking (this is up for discussion)  we would like the following:

- Several 'static' pages:

  - Home 
  - About Us
  - Code of Conduct 
  - Contact Us
  
- A blog to document each meetup with content via links or integrations to our
  social meadia channels.

- A blog (or a section of the blog promoted to top level status) for "Today I
  learnt"

- A RSVP page that requires a uniqueid that allows a member to say "yes" or
  "no" to a meetup email

- Unsubscribe page that requires a uniqueid that allows a member to unsubscribe
  from the email list. 

- An admin section

  - Show the status of members coming to the meetup
  
  - Able to send out a bulk email to members for a meetup

### Several Static Pages

Nothing fancy - just pages that don't need to be dynamically generated
everytime.

### Blog

Simple blog that allows an article to be pushed to the site if a certain status
is given.  Should use some sort of SEO friendly URI.
 
### Blog (TIL section)

Same as the blog above (might even make sense to have it as a sub section of
the blog but have it 'promoted' in some way. It should be a top level section
to the front end.

### RSVP page

A simple 'yes' or 'no' chocie given to the user. Uniqueid should tell us the
user and the meetup in question.

### Unsubscribe Page

A simple page that takes a unqiueid and automatically unsubscribes users from
the mailing list. 

### Admin Section

An admin section

#### Meetup Pages

##### index page

A list of meetups in descending date order. Summary information should include:

  - Meetup date (link to meetup page?)
  - Meetup Title (link to meetup page?)
  - # going/went
  - # no going/declined 
  - # no reply
  - # sent

##### Individual Page

  - List of members that went
  
##### Bulk email page

Able to send out a bulk email to members that are subscribed

## Questions

1. What is our MVP for this app?

2. We need to discuss the features first and iron them out.

As this is a meetup we don't want to spend much time talking about what we are
going to do. This is the reason for the READM, it can be amended on the flyE. 

There is enough in this document to facilitate a meetup and to start coding a MVP. 
 

