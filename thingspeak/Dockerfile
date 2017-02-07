FROM ruby:2.1

RUN git clone https://github.com/iobridge/thingspeak.git
WORKDIR "/thingspeak"
RUN bundle install
#RUN cp config/database.yml.example config/database.yml
#RUN rake db:create
#RUN rake db:schema:load

CMD rails server
