---
title: Rentalcars.com
layout: post
modal-id: 2
date: 2019-02-18
img-full: device-rc.png
alt: Screenshot of rentalcars non-airport search
project-date: 2019-02-18
client: Rentalcars
role: UX Designer
tasks: Sketching, competitor research, visual design, prototyping, user testin
caption: Rentalcars.com
category: Portfolio
excerpt: Ideation and implementation of an improved UX for a 'none airport' search traffic which resulted in a 8% increase in conversion rates.
---

# Non-airport Car search UX

```
Client RentalCars.com
Date 18th February 2019
Platform Desktop web
Goal Improve conversion rate by at least 5% for users
in the non-airport sales funnel.
Responsibilities Discovery, design and testing of suitable UI
component to capture precise location data and
present this to the user.
UX methods used Sketching, competitor research, visual design,
prototyping, user testing,
Link to final project http://www.rentalcars.com
Team members John Aspinall - UX Designer
Khalid Lee Conway - Product Owner
Multiple people - Developers
```
## The client

Rentalcars.com is a car rental agency that allows a user to book a hire car from
numerous partner branches located throughout the world. The branches are
primarily located near airports and this is where users generally pick up and
drop off their hire cars.

## The problem

There are occasions, however, when the user would search to pick up the car
from non-airport locations, such as a city e.g. London, Manchester, etc. On
these occasions, the user would mostly type a city name as their pick up point.
This caused a problem for both the user and the client as RentalCars were not
able to present the most relevant search results, as they did not know exactly
where in the city the user wanted to pick up the car from. There was a
hypothesis from the business that this was the reason conversion rates were
significantly lower than ‘airport’ searching users.

## My role & responsibilities

My goal was to deliver a UX change to the main car search component in order
to encourage the user to enter a precise pickup location when performing a
“non-airport search” with these specific goals and requirements:

1. Improve conversion rates by at least 5% for users in this sales funnel.
2. The change to the component had to be _only_ visible to users who
    performed a non-airport search and must not impact the existing sales
    funnel in any way.
3. The work needed to be completed in a short time frame, so had to be
    straightforward to implement and involve minimal additional
    development work.
4. Collaborate with product development and engineering teams to research, design and implement this project.

## Competitor research

To kick start the ideation process, I performed a non-airport search on the main
competitors' sites and took relevant screenshots from each site.

I compiled the competitor research list, along with some of my own ideas, into a
shortlist of potential approaches and wrote each approach onto a post-it notes
and stuck them on the wall in a discovery meeting with stakeholders and
developers.

I did this to give the ideas visibility and to encourage discussion on the most
suitable solution(s) in the meetings.

## Wireframes & Sketching

After distilling the customer research and shortlisting some approaches, I
created low-fidelity wireframes in order to iterate through design
options quickly. 

I held a brief meeting with the product owner and developer to present the
low-fidelity wireframes which I used as a starting point to discuss the most
suitable option to solve the problem.

_[Figure 2: Sketched wireframes for potential solutions]_

Following a review of the wireframes, it was agreed that we go with the following
solution:

● Display a secondary search input text field (only for users in this type of
search funnel), below the primary search field, called ‘ **tailor pick-up
point’** which would only display when the user entered a non-airport
pick-up location.

● This field would then allow the user to perform an auto-completed
search term which contains major landmarks, districts and buildings
(such as train stations) in order for them to provide their exact pick-up
point.

We chose this solution to take to design and prototype for the reasons:

1. We already had this type of auto-complete metadata available (such as
    train station, district, etc) in the search results algorithm.
2. We felt that the user wouldn’t know that you can search by this metadata
    type, so adding a specific search field would encourage them to do so.
3. We felt this was the most suitable solution to implement within the strict time
    constraints of the project.
4. I had initially wanted to implement a GPS based location solution, but this
    would have involved a lot of additional development work, time and
    budget. The user would also have to specifically allow the browser to
    access their GPS location, which may have caused issues.

## Visual Design

Following agreement on which approach to take, I designed high fidelity screen
mockups with, two variations on the style of the new search field. I also
designed a screen for each stage in the search journey of the new interface.
The image below _[Figure 3]_ was the search component in its original state:

_[Figure 3: Current search component]_
In my first variation _[figure 4]_ below, I added a blue border and step tab around a
new secondary search field called “tailor pick-up point”. The purpose of this was
to visually draw the users' eyes to the field to encourage them to complete it.
Although the field was not mandatory, a project goal was to encourage
interaction with this field and obtain accurate pick-up location data.

_[Figure 4: Design solution 1]_
The second variation _[Figure 5]_ below featured the secondary field in a more
a subtle way that mirrored the design pattern of the existing search field.

_[Figure 5: Design solution 2]_
I visually grouped both the search fields (on both solutions) with an existing
dotted border style which was already present on the page too. This was to
ensure design consistency and not put an additional cognitive load on the user.
I also added the common ‘tool tip’ icon next to the form label with an
information panel appearing on hover/click, the purpose of which was to explain
what the function of this field was to the user. I felt this would be quite important to include as it may not be obvious what the purpose of this field was.

## Prototype

I produced two high fidelity prototypes in order to illustrate the user journey to
stakeholders and to facilitate and validate the solutions in a user testing session.
One prototype had a blue border and steps _[Figure 4]_ and the other without
the blue border _[Figure 5]._ Included below is a link to the prototype based on
_[Figure 4]_, the design with the blue border and tab around the secondary search
field

[Click this link to access the prototype.](https://sketch.cloud/s/Jr0a0/a/xnoDyW/play)

## User Testing & Personas

I had to glean usability insights in order to validate that the proposed solution
would achieve the project goal. To achieve this, I set up a user testing session
using the ‘What users do’ online platform.

To facilitate the session, I wrote two user personas and gave each group a
specific goal.

● Group A - I assigned their pick-up point as ‘Euston station’.
● Group B - I assigned their pick-up point as ‘London’.

I created these two groups as I wanted to gain insights into how users in Group
B would behave when they only know the name of the city as a pick-up point. If
a user has zero local knowledge of a city, how would they know where exactly to
pick up the car? What would they do?

I ran the test on six people, three of which adopted the persona ‘A’ group, and the
other three personas ‘B’.

### User testing - results & observations

**Persona B** - ‘Euston’ pick-up:
    ● Started typing in London in the primary search field to begin with.
    ● Then started typing in Euston in the secondary field. Thought it was
       obvious that was what you were meant to do.
    ● Found the interface easy to use.
● When I asked; “If you didn't know you had to pick it up at Euston and
just wanted the generic location in London”, she said she didn't
know what to do and just said, “Surely I know where I am picking up
from?”.
● Did not cross my mind to just hit search.

**Persona A** - ‘London’ pick-up:
    ● talked through, said he would choose London and then did so
    ● When the second box type came in he said he would just think of
       place in London that is central
    ● Did not cross his mind to just hit search
    ● When seeing the multiple choices for Euston on the interface, he
       thought customers could get confused and choose the wrong one.

 **Persona B** - ‘Euston’ pick-up:
     ● Starting typing - Said he would type in Euston immediately. _
       prototype goes straight to London generic
    ● When the second box came up - said he would search for Euston
       immediately.
    ● When asked, if you didn't know where in London to pick up - he said
       he would find somewhere in London he wanted to pick up
    ● Did not think to just hit search and search for all of London

**Persona A** - ‘London’ pick-up:
    ● Started to type in London
    ● When the second box appeared, she said she would want to type in
       her hotel or where it is she is staying
    ● She said it wasn't too obvious what it is she needed to do and
       would prefer to see a drop-down list of locations
    ● She said she would check google maps beforehand if there was a
       drop-down list and didn't know what the locations are
    ● Didn't think to just hit search and search for all of London

**Persona B** - ‘Euston’ pick-up:
    ● Started typing, said he would have typed Euston station
       immediately, proto takes you to London
    ● When the second box appeared he said he would type in Euston
    ● From the choices that came, he said it wasn't obvious that Euston
       was the station on not a town. (he missed the label station)
    ● When asked, if he didn't know where in London he said he didn't
       know what he would do.

**Persona A** - ‘London’ pick-up:
    ● Started to type in London - when the options appeared he said he
       would have chosen victoria station from the suggestions because
       that's something he knows.
    ● The second box appeared - he thought he lost his options - seemed
       really puzzled about what to do
    ● After some questions said he would have typed in victoria stations
       cos that's where he knows.
    ● Then hits search
    ● Didn't think it was clear what he had to do until he read the tooltip.
● Didn't think to just hit search.

### User testing - insights

The main takeaway points from the user testing were:

1. Everyone felt compelled to enter something in the ‘tailor pick-up point’
box and not one person thought to just hit search and see everything in
London.
2. Only one person went to type ‘Euston’ in the primary search field.
3. A couple of people seem confused by the secondary search field until they
clicked the help icon.
4. The majority of users reported that they thought the second field
was mandatory, particularly in the design variation where the field had a
blue border and tab around it.

The insights obtained from the usability testing helped in selecting a design
option. The product owner and I decided to select the second design option,
without the blue borer and tab. 

The user feedback on this option was that the blue border and tab made it appear as if the field was mandatory and this was
not the case as the field was optional. We didn’t want users dropping out of the
funnel at this early stage because of this so decided to drop it.

We all agreed another prototype iteration was unnecessary and would be a
waste of time and therefore moved forward with design option two _[Figure 5]_
into development.

## Project Learnings

1. It’s very easy to get married to a design solution and adopt a blinkered “it's
my baby” attitude. Just because an interaction pattern is obvious to you
and those around you, it may not be to the end-user and that is ultimately
what can make or break the success of a project. You must always test your
assumptions with users in order to validate your hypothesis, no matter
how ‘right’ you think you are!
2. I learned that in a project with a short time frame, it is best to really
nail down exactly what the stakeholder requires. It was apparent the
stakeholder had a specific idea of how to solve the problem and I could
have saved some research time had this been more accurately
communicated to me. I will double and treble check project requirements
of this ilk in the future!
3. During the user research process, I was surprised to learn that users
thought the new secondary field was mandatory, as it did have an
asterisk attached to it - as is the usual design pattern to indicate this.
Again, never assume anything, just because I know an element is a
‘globally recognised design pattern’, doesn’t mean that end-users think
and know this.
4. The project had many challenges, but the most difficult piece was
communicating with the remote offshore development team in Minsk as
they had broken English and sometimes conversations were difficult when
spoken. Thankfully we were able to get everyone on Slack, which made
back-and-forth changes and conversations much more fluid.
5. While the whole project was a great learning experience, I especially
enjoyed seeing how users interacted with my designs, even though they
did not behave exactly as I thought they might!

```
# Result

When development and QA were complete, the new search component was initially run in production as an A/B experiment where 50% of users performing the
non-airport search got the original search component and the other 50% got the new secondary search field. The experiment ran for four weeks and the results
can be found in the ‘result’ section at the end of this document.

Before we turned on the experiment, we measured the conversion rate of
each user who went on to book a car and performed a non-airport location
search. When we turned the experiment on, we saw **conversion rates jump
up by 8%** over a two week period of testing. We also saw engagement and the number of interactions on each screen - increase.
```