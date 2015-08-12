# Forms & HTML

[![Build Status](https://travis-ci.org/LaravelCollective/html.svg)](https://travis-ci.org/LaravelCollective/html)
[![Total Downloads](https://poser.pugx.org/LaravelCollective/html/downloads)](https://packagist.org/packages/laravelcollective/html)
[![Latest Stable Version](https://poser.pugx.org/LaravelCollective/html/v/stable.svg)](https://packagist.org/packages/laravelcollective/html)
[![Latest Unstable Version](https://poser.pugx.org/LaravelCollective/html/v/unstable.svg)](https://packagist.org/packages/laravelcollective/html)
[![License](https://poser.pugx.org/LaravelCollective/html/license.svg)](https://packagist.org/packages/laravelcollective/html)

Official documentation for Forms & Html for The Laravel Framework can be found at the [LaravelCollective](http://laravelcollective.com) website.

Added the ability to display messages of Validator:

## Specifying Messages of Validator
    {!! Form::text('email', null, null, $errors) !!}
    {!! Form::password('password', null, null, $errors) !!}
    {!! Form::email('email', null, null, $errors) !!}
    {!! Form::textarea('textarea', null, null, $errors) !!}
    {!! Form::radio('textarea', null, null, null, $errors) !!}

## Added function to display IMG and HTML-tags within the Label.
    {!! Form::label('name', 'Lorem ipsum <a href="#">dolor sit amet</a>, consectetur adipiscing elit', null, true) !!}
    {!! Form::labelImage('name', 'image.png', null, ['alt'=>'Title']) !!}
