![reactrails](https://user-images.githubusercontent.com/10421828/79436261-52159b80-7fd9-11ea-994e-2a98dd43e540.png)

<p align="center">
 <a href="https://shakacode.com/"><img src="https://user-images.githubusercontent.com/10421828/79436256-517d0500-7fd9-11ea-9300-dfbc7c293f26.png"></a>
 <a href="https://forum.shakacode.com/"><img src="https://user-images.githubusercontent.com/10421828/79436266-53df5f00-7fd9-11ea-94b3-b985e1b05bdc.png"></a>
 <a href="https://www.shakacode.com/react-on-rails-pro"><img src="https://user-images.githubusercontent.com/10421828/79436265-53df5f00-7fd9-11ea-8220-fc474f6a856c.png"></a>
 <a href="https://github.com/sponsors/shakacode"><img src="https://user-images.githubusercontent.com/10421828/79466109-cdd90d80-8004-11ea-88e5-25f9a9ddcf44.png"></a>
</p>

---

[![License](https://img.shields.io/badge/license-mit-green.svg)](LICENSE.md) [![Build Status](https://travis-ci.org/shakacode/react_on_rails.svg?branch=master)](https://travis-ci.org/shakacode/react_on_rails) [![Gem Version](https://badge.fury.io/rb/react_on_rails.svg)](https://badge.fury.io/rb/react_on_rails) [![npm version](https://badge.fury.io/js/react-on-rails.svg)](https://badge.fury.io/js/react-on-rails) [![Code Climate](https://codeclimate.com/github/shakacode/react_on_rails/badges/gpa.svg)](https://codeclimate.com/github/shakacode/react_on_rails) [![Coverage Status](https://coveralls.io/repos/shakacode/react_on_rails/badge.svg?branch=master&service=github)](https://coveralls.io/github/shakacode/react_on_rails?branch=master) [![](https://ruby-gem-downloads-badge.herokuapp.com/react_on_rails?type=total)](https://rubygems.org/gems/react_on_rails)

*These are the docs for React on Rails 12. To see the version 11 docs, [click here](https://github.com/shakacode/react_on_rails/tree/11.3.0).*

#### About
React on Rails integrates Rails with (server rendering of) Facebook's [React](https://github.com/facebook/react) front-end framework.

This project is maintained by the software consulting firm [ShakaCode](https://www.shakacode.com). We focus on Ruby on Rails applications with React front-ends, often using TypeScript or ReScript (ReasonML). We also build React Native apps and Gatsby sites. See [our recent work](https://www.shakacode.com/recent-work) for examples of what we do. ShakaCode.com (HiChee.com) is [hiring developers that like working on open-source](https://www.shakacode.com/career/).

Interested in optimizing your webpack setup for React on Rails including code
splitting with [react-router](https://github.com/ReactTraining/react-router#readme) and
and [loadable-components](https://loadable-components.com/) with server-side rendering for SEO and hot-reloading for developers?
We did this for Popmenu, [lowering Heroku costs 20-25% while getting a 73% decrease in average response times](https://www.shakacode.com/recent-work/popmenu/). Check out [React on Rails Pro](https://www.shakacode.com/react-on-rails-pro/).

Feel free to contact Justin Gordon, [justin@shakacode.com](mailto:justin@shakacode.com), maintainer of React on Rails, for more information.

# Documentation

See the documentation at [shakacode.com/react-on-rails/docs](https://www.shakacode.com/react-on-rails/docs/).

## Project Objective

To provide a high performance framework for integrating Ruby on Rails with React via the [**Webpacker**](https://github.com/rails/webpacker) gem especially in regards to React Server-Side Rendering for better SEO and improved performance.

## Features and Why React on Rails?

Given that `rails/webpacker` gem already provides basic React integration, why would you use "React on Rails"?

1. Easy passing of props directly from your Rails view to your React components rather than having your Rails view load and then make a separate request to your API.
1. Tight integration with [rails/webpacker](https://github.com/rails/webpacker).
1. Server-Side Rendering (SSR), often used for SEO crawler indexing and UX performance, is not offered by `rails/webpacker`.
1. [Redux](https://github.com/reactjs/redux) and [React Router](https://github.com/ReactTraining/react-router#readme) integration with server-side-rendering.
1. [Internationalization (I18n) and (localization)](https://www.shakacode.com/react-on-rails/docs/guides/i18n)
1. A supportive community. This [web search shows how live public sites are using React on Rails](https://publicwww.com/websites/%22react-on-rails%22++-undeveloped.com+depth%3Aall/).
1. [Reason ML Support](https://github.com/shakacode/reason-react-on-rails-example).

See [Rails/Webpacker React Integration Options](https://www.shakacode.com/react-on-rails/docs/guides/rails-webpacker-react-integration-options) for comparisons to other gems.

See the [react-webpack-rails-tutorial](https://github.com/shakacode/react-webpack-rails-tutorial) for an example of a live implementation and code.

## ShakaCode Forum Premium Content
_Requires creating a free account._

* [How to use different versions of a file for client and server rendering](https://forum.shakacode.com/t/how-to-use-different-versions-of-a-file-for-client-and-server-rendering/1352)
* [How to conditionally render server side based on the device type](https://forum.shakacode.com/t/how-to-conditionally-render-server-side-based-on-the-device-type/1473)

# License

The gem is available as open source under the terms of the [MIT License](https://github.com/shakacode/react_on_rails/tree/master/LICENSE.md).
