# vertical-tabs
With vertical tabs, you can create a sleek showcase of your work and organize your content efficiently.

## Tutorial
For detailed instruction's, view Solodev's [How To Showcase Your Project Content with Vertical Tabs](https://www.solodev.com/blog/web-design/how-to-showcase-your-project-content-with-vertical-tabs.stml)

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/qmur7o4j/).

## HTML
The tutorial contains the following basic HTML markup.

```
 <div class="container">
  <div class="row">
    <div class="tabs-wrapper mt-5 mb-5">
      <div class="row">
        <div class="col-md-3">
          <ul class="nav nav-tabs normal-tabs-nav text-center-sm" role="tablist">
            <li class="active" role="presentation">
              <a onclick="documentTrack('#opportunity');" aria-controls="opportunity" data-toggle="tab" href="#opportunity" role="tab">Opportunity</a>
            </li>
            <li class="" role="presentation">
              <a onclick="documentTrack('#solution');" aria-controls="solution" data-toggle="tab" href="#solution" role="tab">Solution</a>
            </li>
            <li class="" role="presentation">
              <a onclick="documentTrack('#success');" aria-controls="success" data-toggle="tab" href="#success" role="tab">Success</a>
            </li>
          </ul>
        </div>
        <div class="col-md-8">
          <div class="tab-content normal-tabs-content">
            <div class="tab-pane active fade in" id="opportunity" role="tabpanel">
              <h2>
                At LunarXP, we’re dreamers and explorers. We’ve always looked up for purpose – and we’ve never looked back. As a company, we believe that the future of mankind lies beyond earth and in the stars.
              </h2>
              <p>
                Our fleet of advanced spacecraft have revolutionized the lunar economy and provided safe travel for thousands of scientists, engineers, technicians, medical staff and civilians. These amazing vessels are also paving the way for reaching Mars in the next decade.
              </p>
              <p>
                Lorem Ipsum is the standard filler text used in design throughout the world. It’s been the standards since the 1500’s and it’s time for an update. The NASA OpenGov team took the opportunity at Science Hack Day to create a new online tool to generate filler text based on a database of historical space quotes. The project serves as an example of what can be done to utilize historic NASA data and mash it up in a new and exciting way.
              </p>
            </div>
            <div class="tab-pane fade" id="solution" role="tabpanel">
              <h2>
                LunarXP introduced different types of spacecraft to make transportation more efficient
              </h2>
              <ul>
                <li>Valkyrie-1: medium-sized lift and reentry vehicles designed for ground-to-orbit escape velocity and safe, reusable landings on both the earth and the moon
                </li>
                <li>Lunar XPlorer: space-based container vessels capable of moving large quantities of people and supplies   from earth orbit to lunar orbit
                </li>
                <li>Talon-2: small, low-altitude atmospheric vehicles designed for lunar takeoff, landing and internship transport
                </li>
              </ul>
            </div>
            <div class="tab-pane fade" id="success" role="tabpanel">
              <h2>
                LunarXP has won a prestigious award for its participation in a variety of cosmic explorations.
              </h2>
              <p>(Cape Canaveral, FL) LunarXP, the leader in moon exploration and colonization, is proud to announce that it is the recipient of the prestigious "Space Innovator of the Year" Award. This marks the third year in a row that the private interstellar travel and resource development organization has received the distinction.</p>

              <blockquote>"We're thrilled to be honored by the international space community once again this year," said Shane Morrison, Chief Space Officer of LunarXP and commander of the moon-based container fleet. "This company was founded on a dream: to explore the stars. Together, we've been able to make that dream a reality and turn this mission into a commercially viable enterprise. We look forward to continuing our exploration to Mars and beyond in the coming years."</blockquote>

              <p>LunarXP is running daily flights from Cape Canaveral, FL and San Jose, CA to the orbiting XPlatform, where multiple Lunar XPlorer vessels ferry passengers to a growing number of lunar habitats. LunarXP is currently hiring specialists in a number of key areas for part- and full-time employment in their permanent moon settlements.</p>

              <p>"Not only is LunarXP exploring new worlds, but our scientists are developing new technologies that are impacting the earth's reliance on fossil fuels and renewable energy sources," said Morrison. "We're mining new types of metals and minerals that have unlimited applications across industries. We excited to be sharing our discoveries with the world."</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div> 
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<!-- Bootstrap CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
<!-- FontAwesome CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.css">
<!-- jQuery first, then Popper.js, then Bootstrap JS -->
<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
```