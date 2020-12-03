Kivy doesnt support 3.8 yet.

Needed dependencies `brew install pkg-config sdl2 sdl2_image sdl2_ttf sdl2_mixer gstreamer`

For pipenv to do no-binary: `export PIP_NO_BINARY=:all: && pipenv install`

Needed to use no-binary beause MPF overwrites a handful of frameworks (see official docs)

pangoft was missing, ran: `brew install pango`

retrying...

new error! that helped. Now looking into installing: https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=BuildTools&rel=16

because of https://stackoverflow.com/questions/29846087/microsoft-visual-c-14-0-is-required-unable-to-find-vcvarsall-bat

Fuck all that noise, just use python 3.6

Our hardware: https://docs.missionpinball.org/en/latest/hardware/multimorphic/mac.html

Dec 2:
 * Adding: opto's on bank 0 in the trough

 ### General Notes For Our Setup

 Switches on board A0
 Coils on board A1

 