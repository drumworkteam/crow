<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

<p align='center'>
  <img src='https://github.com/tunebond/crow.link/blob/make/view/view.svg?raw=true' height='312'>
</p>

<h3 align='center'>crow.link</h3>
<p align='center'>
  Base Link Framework
</p>

<br/>
<br/>
<br/>

## Welcome

The `crow` framework aims to be an opinionated model of everything you need to build software applications. It is used for building apps, writing CLI tools, building microservices, etc.. It is a way of writing your code, along with tools like Rails provides to make building these things easier and more seamless across platforms.

<p align='center'>
  <img src='https://github.com/tunebond/crow.link/blob/make/view/base.logo.svg?raw=true' height='256'>
</p>

## Usage

From nothing:

```
base make @tunebond/crow
```

That runs the executable in `@tunebond/crow#make` and gives you a starter project. Otherwise here are the more manual steps:

```
base link deck @tunebond/crow
```

Add to the `dock/role/base.link` file.

```
load @tunebond/crow
  find mind code

role code
  link ./**/test.link
  link ./**/base.link
```

Then in a code formatted file:

```
load @tunebond/crow
  find dock button
  find task draw
  find form base

host button-style
  host fill, text <red>
  host hover
    host fill, text <blue>

call draw
  zone button, text <hello world>
    vibe button-style
    hook click
      show <clicked!>

form user
  link email, like text

form post
  link title, like text

# schema
host base
  make base
    form user
    form post
```

All the components can be access directly from that import, but in case you need something internal, dig into `@tunebond/crow/code/**/*.link`.

Then build the package into the `./cast` folder.

```
base cast deck
```

## License

Copyright 2022-2023 <a href='https://tune.bond'>TuneBond</a>

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## TuneBond

This is being developed by the folks at [TuneBond](https://tune.bond), a California-based project for helping humanity master information and computation. TuneBond started off in the winter of 2008 as a spark of an idea, to forming a company 10 years later in the winter of 2018, to a seed of a project just beginning its development phases. It is entirely bootstrapped by working full time and running [Etsy](https://etsy.com/shop/tunebond) and [Amazon](https://www.amazon.com/s?rh=p_27%3AMount+Build) shops. Also find us on [Facebook](https://www.facebook.com/tunebond), [Twitter](https://twitter.com/tunebond), and [LinkedIn](https://www.linkedin.com/company/tunebond). Check out our other GitHub projects as well!
