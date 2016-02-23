# Mozilla Hungary Education - Fall Semester, 2016

A plan to revamp current efforts around [Firefox OS Education]
and transition the [Firefox OS university course] into a more open,
more webby format, keeping the mobile focus still, but embracing
emerging standards from the last few years around progressive
webapps.

## The 2015 fall semester
After several several early invocations, the 2015 fall semester was
the first year in which Mozilla was actively contributing to the success
of the program. With support from the Mozilla Reps program, and under the
guidance of Brian King the semester launched with the course being
implemented at 4 different colleges and universities, coming close to 100
students picking up the course at the start of the semester.

Krisztián Karóczkai, author and teacher of the course was not just
building the MOOC course material and teaching it at his home
institution, University of Óbuda, but brought his alma mater,
College of Dunaújváros into the program as well as with the
support of Mozilla taught guest-lectures at the other institutes'
classes and presented the program at [Hungarian educational conferences].

### Outcomes
In the 2015/2016 fall semester from the 96 subscribed student
39 managed to complete the success requirement (building a Firefox OS
application), some of those (28) already live in the Firefox Marketplace.

Among the apps are some pretty well-received ones, such as [Snakey]
([full list of submissions]). The program was [presented at various]
conferences on education & edutech.


# Mozilla Progressive Mobile WebApplication Development Course

The 2016 Fall semester, instead of focusing on Firefox OS as previous
iterations of the program did, will focus on cross-platform mobile
development. Earlier editions were, in fact themselves very portable
in the baseline webapp development knowledge taught, we are keeping
those parts and best practices intact, while replacing most of the
FirefoxOS-specific details (packaged apps, marketplace, non-standard
APIs) with their nascent, standard and more widely supported technologies
(including, but not limited to [Web App Manifests], [service workers],
[Push API] and Notifications API, etc.)

The current [Firefox OS Course material] would have needed to be updated
soon anyway due to changes in aspects of Firefox OS at 2.5/2.6 (such
as the new security architecture), these efforts now can be channeled
into deprecating the parts that are no longer useful, and advocating
cross-browser, standard solutions.

This doesn't mean ditching Firefox OS in the slightest, au contraire,
as service workers and other Progressive WebApps-related features land
in Gecko, FxOS phones used at previous occasions could be (if updated to
latest versions of Firefox OS, running an up-to-date Gecko) could still
be used to develop and test apps with the new curriculum.  
On top on that, though, students can create and test their applications
using their own personal devices, using either Firefox (for Android/iOS)
or the built-in browser. This would bring the acquired knowledge closer
to the real-world usecases, which, in turn would increase the appeal
towards the course, on both universities' & students' sides.


[Firefox OS Education]: https://wiki.mozilla.org/Firefox_OS/Community/Hungary/Education/2015-2016_fall_semester
[Firefox OS university course]: https://wiki.mozilla.org/Firefox_OS/Community/Hungary/Education/Courses/Firefox_OS#Current_work:_2015.2F2016_fall_semester
[bug #1185379]: https://bugzilla.mozilla.org/show_bug.cgi?id=1185379
[Web App Manifests]: https://www.w3.org/TR/appmanifest/
[Push API]: https://w3c.github.io/push-api/
[service workers]: https://slightlyoff.github.io/ServiceWorker/spec/service_worker/index.html

[Firefox OS Course material]: https://github.com/MozillaHU/firefox-os-course

[Snakey]: https://marketplace.firefox.com/app/snakey/
[Hungarian educational conferences]: http://oktatastervezes2016.uni-eger.hu/hu/program/
[presented at various]: https://twitter.com/meetoff/status/695932512103755776
[full list of submissions]: https://bugzilla.mozilla.org/show_bug.cgi?id=1185379#c32
