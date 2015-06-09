
var runSequence = require('run-sequence'); // Temporary solution until Gulp 4 // https://github.com/gulpjs/gulp/issues/355


Neben einem kurzem Einstieg in die Historie von Gulp und einem Kurzausflug zu Grunt geht der Vortrag darauf ein, wie man Gulp effizient verwendet (die meisten Gulp-Skripte sind nämlich nicht effizient ...). Dazu wird ein Standard-Gulp-Skript als Basis in ein pragmatisches, wesentlich kürzeres und lesbareres umgewandelt. Das wird primär erreicht durch den direkten Aufruf der genutzten Tools, Inlining von Gulp-Plug-in-Funktionalität (via Node Streams API, ES2015) und den Einsatz von ES-2015-Sprachfeatures. Im Zuge des Vortrags soll auch ein Gulp-Plug-in erstellt werden. Die Vorteile (weniger Dependencies, schnellere Build, wartbarer Code usw.) werden am Ende gegenübergestellt.

* sourcemaps für traceur code : http://www.2ality.com/2015/04/node-es6-transpiled.html?utm_source=nodeweekly&utm_medium=email

* https://github.com/meoguru/traceur-source-maps/blob/master/lib/traceur-source-maps.js
