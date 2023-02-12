\# 09.02.2023 work perfect<br>
git clone https://github.com/openboxes/openboxes.git<br>
git clone https://github.com/voidnick/openboxes-docker-dev.git<br>
cd openboxes-docker-dev<br>
docker-compose build<br>
docker-compose up<br>
\# Error only on first run: "**ERROR context.GrailsContextLoader  - Error executing bootstraps: No such property: mergedConfig for class: org.codehaus.groovy.grails.commons.DefaultGrailsApplicatio**"<br>
Ctrl+C<br>
docker-compose up<br>
\# Access: http://127.0.0.1:8080/openboxes<br>
\# You can use the default accounts:<br>
\# user: manager<br>
\# passwd: password<br>
\# OR<br>
\# user: admin<br>
\# passwd: password<br>