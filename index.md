---

layout: col-sidebar
title: OWASP Las Vegas
tags: meetings-tag conferences-tag leadership-tag
level: 0
region: North America
meetup-group: OWASP-Las-Vegas-Chapter
country: USA
postal-code: 89101

---

### Welcome

Welcome to the OWASP Las Vegas chapter! We're excited to have a dedicated group of application security professionals and enthusiasts, and we'd love to have you join us. All meetings are free, oriented towards knowledge sharing, practical learning, and having lots of fun!

Join our [Meetup Group](https://www.meetup.com/OWASP-Las-Vegas-Chapter/). All OWASP Las Vegas events are announced and tracked there.

### Check our Upcoming Meetup Events:
{% include chapter_events.html group=page.meetup-group %}

<script type='text/javascript'>
  $(function(){
    $(".timeclass").hover(function() {
      utc_str = $(this).text();
      ndx = utc_str.indexOf(':');
      st_hour_str = utc_str.substring(0, ndx);
      st_min_str = utc_str.substring(ndx + 1, ndx + 3);
      utc_dt = luxon.DateTime.utc(2020, 06, 06, parseInt(st_hour_str), parseInt(st_min_str), 0);
      start_dt = utc_dt.setZone(luxon.DateTime.local().zoneName);

      ndx = utc_str.lastIndexOf(':');
      end_hour_str = utc_str.substring(ndx - 2, ndx - 1);
      end_min_str = utc_str.substring(ndx + 1, ndx + 3);
      utc_dt = luxon.DateTime.utc(2020, 06, 06, parseInt(end_hour_str), parseInt(end_min_str), 0);
      end_dt = utc_dt.setZone(luxon.DateTime.local().zoneName);
      popstr = start_dt.toLocaleString(luxon.DateTime.TIME_WITH_SECONDS) + ' to ' + end_dt.toLocaleString(luxon.DateTime.TIME_WITH_SHORT_OFFSET);
      $(this).prop('title', popstr);
    });
  });
</script>
<br>

### Participation

The Open Worldwide Application Security Project (OWASP) is a nonprofit foundation that works to improve the security of software. All of our projects, tools, documents, forums, and chapters are free and open to anyone interested in improving application security. 

Chapters are led by local leaders in accordance with the  NEW Chapter Policy. To be a SPEAKER at ANY OWASP Chapter in the world simply contact the local chapter leader with details of what OWASP Project, independent research, or related software security topic you would like to present.

Everyone is welcome and encouraged to participate in our [Projects](https://owasp.org/projects/), [Local Chapters](https://owasp.org/chapters), [Events](https://owasp.org/events), [Online Groups](https://groups.google.com/a/owasp.com/), and [Community Slack](https://owasp.slack.com/). We especially encourage diversity in all our initiatives. OWASP is a fantastic place to learn about application security, network with like-minded people, and even build your reputation as a professional. We also encourage you to be [become a paid member](https://owasp.org/membership) or consider [making a donation](https://owasp.org/donate) to support our ongoing work (financial contributions should only be made online using the authorized online donation feature).
