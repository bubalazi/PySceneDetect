

### <span class="fa fa-bug"></span>&nbsp; Bug Reports

Bugs and issues with PySceneDetect are mainly handled through [the issue tracker on Github](https://github.com/Breakthrough/PySceneDetect/issues).  If you run into any bugs while using PySceneDetect, please feel free to [create a new issue](https://github.com/Breakthrough/PySceneDetect/issues/new).  Provide as much detail as you can - include an example that clearly demonstrates the problem (if possible), and make sure to include any/all relevant program output or error messages.

When submitting bug reports, please add the command-line options `--info-level debug --logfile BUG_REPORT.txt` to the very beginning of the `scenedetect` command you are using, and attach the generated `BUG_REPORT.txt` file.

Before opening a new issue, please [search through all existing issues](https://github.com/Breakthrough/PySceneDetect/issues?q=) (both open and closed) to avoid creating duplicate entries.


### <span class="fa fa-keyboard-o"></span>&nbsp; Contributing

The development of PySceneDetect is done on the Github Repo, guided by [the feature roadmap](features.md).  Code you wish to submit should be attached to a dedicated entry in [the issue tracker](https://github.com/Breakthrough/PySceneDetect/issues?q=) (with the appropriate tags for bugfixes, new features, enhancements, etc...), and allows for easier communication regarding development structure.  Feel free to create a new entry if required, as some planned features or bugs/issues may not yet exist in the tracker.

All submitted code should follow the [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html) as closely as possible.  Also, ensure that you search through [all existing issues](https://github.com/Breakthrough/PySceneDetect/issues?q=) (both open and closed) beforehand to avoid creating duplicate entries.

Note that PySceneDetect is released under the BSD 2-Clause license, and submitted code should comply with this license (see [License & Copyright Information](copyright.md) for details).


### <span class="fa fa-person"></span>&nbsp; List of Contributors

The following list details some contributors people have made to the PySceneDetect project. In no way is this list complete, nor is the list maintained in any particular order.

A full list of contributors can be derived from looking at a list of [all issues](https://github.com/Breakthrough/PySceneDetect/issues?utf8=%E2%9C%93&q=is%3Aissue) and [all pull request](https://github.com/Breakthrough/PySceneDetect/pulls?utf8=%E2%9C%93&q=is%3Apr+).

In addition to those listed below, a significant number of other contributors have greatly helped the development of PySceneDetect by reporting defects/bugs and providing adequate information in order to fix these issues.  In addition to those mentioned below, thank you to *everyone* who has submitted an issue, bug report, and/or pull request, as well as for those who continue to help the ongoing development of PySceneDetect.

 * [@elcombato](https://github.com/elcombato) - improvement of video processing performance due to reduced memory copy operations
 * [@marcelluzs](https://github.com/marcelluzs) - improvement of video processing performance when using the frame-skipping feature
 * [@Hellowlol](https://github.com/Hellowlol) - improvements to software architecture and API development
 * [@bubalazi](https://github.com/bubalazi) - performance improvements to detect-content and detect-threshold algorithms
 * [@r1b](https://github.com/r1b) - proof-of-concept implementation of detect-histogram algorithm


