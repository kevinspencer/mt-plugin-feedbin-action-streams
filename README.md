# Feedbin Action Streams, a plugin for Movable Type

## Overview

Aggregates starred items from a feedbin.me account into Action Streams


## Installation

1. Move the FeedbinActionStreams plugin directory to the MT `plugins` directory.
2. Move the FeedbinActionStreams mt-static directory to the `mt-static/plugins` directory.

    Should look like this when installed:

        $MT_HOME/
            plugins/
                FeedbinActionStreams/
                    (plugin files here)
            mt-static/
                plugins/
                    FeedbinActionStreams/
                        (plugin static files here)

3. Add the following CSS to the Action Streams CSS file (`$MT_HOME/mt-static/plugins/ActionStreams/css/action-streams.css`):

        .service-Feedbin { background-image: url(/mt-static/plugins/FeedbinActionStreams/images/feedbin.png); }

    or add this to the blogs css file index template:

        .service-Feedbin { background-image: url(<$mt:BlogURL$>mt-static/plugins/FeedbinActionStreams/images/feedbin.png); }

