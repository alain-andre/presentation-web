# Introduction
Cette archive est le code source de ma présentation hébergée sur [Heroku](presentation-web.herokuapp.com).

Elle a pour objectif de présenter les origines du web et son avenir sur un support moderne et structuré en utilisant [impress.js](https://github.com/bartaz/impress.js), [highlight.js](https://github.com/isagalaev/highlight.js) et tout ceci sur un site statique généré par [middleman](https://github.com/middleman/middleman).

# Installation

[![Build Status](https://secure.travis-ci.org/alain-andre/presentation-web.png)](http://travis-ci.org/alain-andre/presentation-web)

```
git clone https://github.com/alain-andre/presentation-web.git
cd presentation-web
gem install middleman
bundle install
bundle exec middleman server
```

Si vous avez une erreur comme celle-ci :

```hitimes.rb:37:in `require': cannot load such file -- hitimes/hitimes (LoadError)```

Il vous faut tout d'abord mettre à jour les gems de votre système :

```gem update --system```

Puis réinstallez hitimes qvec l'option verbose pour bien voir ce qui se passe:

```gem install --verbose hitimes```

# License

Copyright (c) 2015 Alain ANDRE. MIT Licensed.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
