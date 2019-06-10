# javacard-tutorial-code

A "Hello World" example JavaCard applet for Fidesmo ecosystem, used in the [Fidesmo JavaCard tutorial](https://developer.fidesmo.com/tutorials/javacard).

### Usage

To be able to interact with the Fidesmo servers you need to create an account and an application [here](https://developer.fidesmo.com/).
Write your own appId on the attribute `fidesmoappid` in build.xml

To generate the CAP file just run ant

    ant

You can then install it onto your card using [FDSM](https://github.com/fidesmo/fdsm).

