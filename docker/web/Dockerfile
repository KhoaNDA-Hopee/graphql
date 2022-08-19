FROM ruby:3.1.2

ENV RAILS_ENV=development
ENV NODE_ENV=development
ENV RACK_ENV=development

RUN gem uninstall bundler
RUN gem install bundler -v 2.3.7

WORKDIR /webapp

COPY Gemfile Gemfile.lock /webapp/
