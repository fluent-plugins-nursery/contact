# contact repository for [fluent-plugins-nursery](https://github.com/fluent-plugins-nursery)

[![Join the chat at https://gitter.im/fluent-plugins-nursery/contact](https://badges.gitter.im/fluent-plugins-nursery/contact.svg)](https://gitter.im/fluent-plugins-nursery/contact?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A plugin author can contact us using this repository's issue

## What is fluent-plugins-nursery?

* This organization is for Fluentd plugins that are not maintained by original authors
* This organization aims to provide a sustainable maintenance system for Fluentd community
* Original authors can transfer ownership to this organization according to procedure in next section

## Procedure

1. Plugin author [creates an issue](https://github.com/fluent-plugins-nursery/contact/issues/new) to transfer ownership

2. Admins check created issue(s) and add label `accepted`

    Admins add you to this organization as a member of "Original authors" team.

3. Plugin author transfers ownership to this organization.

4. Plugin author adds [@okkez](https://github.com/okkez) to Gem owner

    ```
    $ gem owner GEM -a okkez000@gmail.com
    ```

5. [@okkez](https://github.com/okkez) adds other admins to Gem owner

6. Close issue

## FAQ

* Q: Is this highjack?
* A: No. Original authors can keep privileges if they want.
* Q: Can original authors release new version?
* A: Yes. Original authors can keep maintaining plugin.
* Q: Why transfer ownership?
* A: Because it is easy for Fluentd users to find the repository that is maintainable and sustainable.
     And Fluentd development core team encourages to contribute plugin upstream repository, we don't want to fork original authors'.
     See [Fluentd development core team's opinion](https://docs.fluentd.org/plugin-development#send-a-patch-or-fork)
* Q: Original authors are missing!
* A: You can find out them on the internet. If you cannot find out them, we can help you.
* Q: I'm a plugin developer. I want to support Fluentd's new features. But I don't know what should I do.
* A: Let's go [Fluentd community](https://www.fluentd.org/community)!
* Q: I want to talk to you before create issue.
* A: Let's talk on [fluent-plugins-nursery/contact](https://gitter.im/fluent-plugins-nursery/contact).

## Options

There are some options to maintain plugins other than transferring ownership.

See https://github.com/fluent-plugins-nursery/contact/blob/master/related-projects.md

## Admins

* [@okkez](https://github.com/okkez)
* [@cosmo0920](https://github.com/cosmo0920)
