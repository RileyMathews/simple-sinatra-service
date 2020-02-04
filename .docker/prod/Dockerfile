FROM ruby:2.6
WORKDIR /app
COPY . .
RUN bundle install --without development test

EXPOSE 3000

ENTRYPOINT [ "" ]
CMD [ "bundle", "exec", "puma" ]
