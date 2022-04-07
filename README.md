# Open Source Software project scaffold

This project is intended to be used as a template to assist with the bootstrapping
of WA Government agency open source software (OSS) projects. It contains a number of
suggested default inclusions, as well as the context for each inclusion.

# Summary of included files

## README.md

A summary of the OSS project application, functions and scope, as well as how to use it.

## LICENSE

The OSS licence adopted for the project. Licenses are a fundamental part of developing OSS.
Without a license attached, your project might as well be not be published at all, since
without a license no one else can actually use it. Open Source does not simply
mean having access to the source code of a project. The *Open Source Initiative*
(OSI) publishes a commonly-accepted [definition](https://opensource.org/osd) of
what Open Source means, which is worth reviewing.

There are a large number of existing available OSS licenses to choose from, all with
their own implications and differences. Reviewing a website such as
[choosealicense.com](https://choosealicense.com/) may assist you. If you are creating a standalone project, you can
freely decide on a license. If you are building on other works however, things get a
bit more complicated. You need to check and understand *their* licenses, and also
understand that you will be restricted to something compatible in your own choice.

Once you have chosen your desired license, copy the required text into a `LICENSE`
file in your project root, ensure that the details regarding year and
organisation name are correct, and make a note of it in your project `README`.

This project is licensed under the *Apache License 2.0*, the full text of which
is viewable [here](https://choosealicense.com/licenses/apache-2.0/).

## AUTHORS.md

A list of contributors to the repository content. Optional, but generally
well-regarded in Open Source projects.

## CONTRIBUTING.md

Instructions for how others can contribute to the project, if required.
Include the preferred manner of contribution, expectations around any pull requests
raised, etc.

## SECURITY.md

The security policy for the project, including a contact method for reporting
vulnerabilities, expected response time, etc. This would also include a summary of
any automated vulnerability scanning carried out for the project.

The included `SECURITY.md` file in this project includes some boilerplate text
that can be adapted to the purpose.

## CHANGELOG.md

A chronological list of major changes to and/or versions of the project.
Optional, but quite useful to help external consumers keep track of changes to
public projects.

Any project versioning scheme may be adopted; the most important feature is for
this to be consistent and understandable to outside consumers. [Semantic
Versioning](https://semver.org/spec/v2.0.0.html) is suggested as a sensible
choice for many OSS projects.
