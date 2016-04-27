---
layout: workshop
root: .
---


<h2>Schedule</h2>

<div class="row">
  <div class="col-md-6">
    <h3>Day 1</h3>
    <table class="table table-striped">
      <tr> <td>09:30</td> <td>Welcome and introductions</td>
      <td> SSI Instructor Training. Who we are. Who you are.</td>
      <td>Aleksandra</td></tr>
      <tr> <td>09:40</td> <td>Overview: key concepts and training goals</td> <td>Educational psychology. PCK. Why we do this training. Evidence-based training.</td>
      <td>Steve</td>
      </tr> 
      <tr> <td>09:45</td> <td>Mental models. </td> <td>Mental models vs simple facts knowledge. Novices and competent practitioners. </td>
      <td>Steve</td>
      </tr> 
       <tr> <td>09:55</td> <td>Formative vs. summative assessment </td> <td>Diagnosing broken mental models. Formative vs summative assessment. Multiple Choice Questions (show example!)  </td>
      <td>Steve</td>
      </tr>
      <tr> <td>10:05</td> <td>Exercise - formative assessment</td>
      <td>Participants to design a MCQ (plausible distractors!) on a first-year undergrad topic from their domain. Find a partner. Exchange.</td>
      <td>Steve</td></tr>
      <tr> <td>10:30</td> <td>Coffee break</td></tr>
      <tr> <td>11:00</td> <td>Peer instruction</td>
      <td>Show the peer instruction video and explain. Remind the participants "this is the sound of classroom learning and this is what you did  with MCQs".</td>
      <td>Aleksandra</td></tr>
      <tr> <td>11:10</td> <td>Teaching as performance art</td>
      <td> Lesson study ("Building a better teacher"). Giving and receiving feedback.</td>
       <td>Steve</td></tr>
       <tr> <td>11:20</td> <td> Exercise - video 1</td>
       <td> Up to 2 minutes on "The coolest thing about my job". 2 min feedback each (grid: +/- ; delivery/contents) </td>
       <td>Steve</td></tr>
      <tr> <td>11:55</td> <td>Feedback on stickies</td> <td>Steve</td></tr>
      <tr> <td>12:00</td> <td>Lunch break</td></tr>
      <tr> <td>13:00</td> <td> Expertise</td> <td> What makes an expert? Dense connections between ideas. </td>
      <td>Steve </td> </tr>
      <tr> <td>13:10</td> <td> Managing memory</td> 
      <td> Short and long term memory in learning process. 7 +/- 2 rule.</td> 
      <td>Steve </td> </tr>
      <tr> <td>13:20</td> <td> Concept maps</td> 
      <td> Representing and externalising expertise and knowledge. Purpose of concept maps. Concept maps != mind maps, diagrams, flowcharts </td>
      <td> Steve and Aleksandra</td> </tr>
      <tr> <td>13:30</td> <td> Concept maps - exercise</td> <td> Participants to develop a concept map (7+/-2 rule!) on the topic they used for the MCQ before lunch. Exchange maps with a partner.</td> </tr>
      <tr> <td>14:15</td> <td> Discussion on Concept Maps</td> <td> Aleksandra</td> </tr>
      <tr> <td>14:30</td> <td>Coffee break</td> </tr>
      <tr> <td>15:00</td> <td>Learning objectives</td>
      <td> </td> <td>Steve </td> </tr>
      <tr> <td>15:20</td> <td>Learning objectives - exercise</td><td>Participants to develop learning objectives for the concept they used for MCQ and for the concept map </td>  </tr>
      <tr> <td>15:45</td> <td>Concept maps - discussion</td><td>2 participants to present their concept maps on whiteboard and discuss</td><td>Steve </td> </tr>
      <tr> <td>15:50</td> <td>Teaching as performance art</td> <td>Participants to teach up to 5 min each on the concept they worked on (MCQ, concept map, learning objectives). 3 min feedback each.</td></tr>
      <tr> <td>16:40</td> <td>Homework overview</td> <td> a) read Operations Guide and write your questions into Etherpad; b) prepare 5 minutes to live teach from one of the DC/SWC lessons </td> <td> Aleksandra </td></tr>
       <tr> <td>16:40</td> <td>Wrap-up</td> 
        <td>Feedback on sticky notes </td> <td> Steve</td></tr>
    </table>
  </div>
  
  <div class="col-md-6">
    <h3>Day 2</h3>
    <table class="table table-striped">
      <tr> <td>09:30</td> <td>Recap and homework review<br></td> </tr>
      <tr> <td>10:00</td> <td>Alternative formative assessment techniques</td> </tr>
      <tr> <td>10:30</td> <td>Coffee break</td> </tr>
      <tr> <td>11:00</td> <td>Live coding and active learning</td> </tr>
      <tr> <td>12:00</td> <td>Lunch break</td> </tr>
      <tr> <td>13:00</td> <td>Overview of Software and Data Carpentry infrastructure</td> </tr>
      <tr> <td>13:30</td> <td>Setting up and running a workshop</td> </tr>
      <tr> <td>14:30</td> <td>Coffee break</td> </tr>
      <tr> <td>15:00</td> <td>Overview of existing materials; how to contribute</td> </tr>
      <tr> <td>16:00</td> <td>Next steps</td> </tr>
      <tr> <td>16:45</td> <td>Wrap-up</td> </tr>
      <tr> <td>17:00</td> <td>Close</td> </tr>
    </table>
  </div>
</div>

{% if page.etherpad %}
<p>
  <strong>Etherpad:</strong> <a href="{{page.etherpad}}">{{page.etherpad}}</a>.
  <br/>
  We will use this Etherpad for chatting, taking notes, and sharing URLs and bits of code.
</p>
{% endif %}

<hr/>

<h2>Syllabus</h2>

<p>
  Please see <a href="{{site.swc_githubio}}instructor-training">this website</a> for the course material.

</p>


<hr/>

<h2 id="preparation" name="preparation">Preparation</h2>
<ol>
    <li>
      Please read
      Porter et al's
      <a href="{{site.swc_files}}/training-course/2013/08/p34-porter.pdf">"Success
      in Introductory Programming: What Works?"</a>, which is a good
      recent summary of results specific to teaching programming, and
      Mark Guzdial's
      <a href="http://cacm.acm.org/blogs/blog-cacm/189498-top-10-myths-about-teaching-computer-science/fulltext">"Top 10 Myths About Teaching Computer Science"</a>,
      which is a nice overview of things that <em>are not</em> true, but are widely believed.
    </li>
    <li>
    Please read also <a href="http://f1000research.com/articles/3-62/v2/pdf">
    a new version of “Software Carpentry: Lessons Learned”</a> which explains why we do things the way we do.
    </li>
    <li>
      Please also pick up a copy of
      <a href="http://www.amazon.com/How-Learning-Works-Research-Based-Jossey-Bass/dp/0470484101/">"How
      Learning Works"</a>, which is currently the best summary of research
      in education. It is full of useful insights, and a lot of how we
      teach is based on the findings it reports.
    </li>
    <li>
      Finally, please go
      to <a href="{{site.swc_site}}/lessons.html">Software Carpentry's
      lessons page</a> and <a href="{{site.dc_site}}/lessons/">Data Carpentry's lessons page</a>
      to see what is currently taught by each.
    </li>
</ol>
<p>
  If you are interested in doing more
  reading, <a href="http://www.amazon.com/Teaching-What-You-Dont-Know/dp/0674066170">Huston's
    "Teaching What You Don't Know"</a> is a lot of fun - many will
  recognize themselves in these stories. Past participants have
  also enjoyed
  <a href="http://www.amazon.com/Building-Better-Teacher-Teaching-Everyone/dp/0393081591">"Building
    a Better Teacher"</a>, which is a well-written look at why
  educational reforms in the past 50 years have mostly failed, and
  covers what we should be doing instead.
</p>
