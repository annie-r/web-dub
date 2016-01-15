---
################################################################################
# Version of the seminar format. The only valid value for this is 1. 
# We may increment this in the future to simplify maintenance of old seminars.
################################################################################
version: 1

################################################################################
# Date and time of the seminar. In quotes because : is a reserved character.
# Date must equal the name of this file.
################################################################################
date:     2015-10-07
time:     "12:00 PM"
time_end: "1:20 PM"

################################################################################
# A seminar file might exist but not yet be scheduled. This is 'TBD'. 
# The only valid value is 'True'. The field should not be present if 'False'.
################################################################################
tbd: True

################################################################################
# One or more speakers. Each speaker has name and affiliation.
#
# speakers:
#   - name: 
#     - Surname
#     - First
#     - Middle
#     - More
#     affiliation: Computer Science & Engineering 
################################################################################
speakers:
  - name: 
    - Surname
    - First
    - Middle
    - More
    affiliation: Computer Science & Engineering 
  - name: 
    - Surname
    - First
    - Middle
    - More
    affiliation: Information School 
  - name: 
    - Surname
    - First
    - Middle
    - More
    affiliation: Carnegie Mellon University 

################################################################################
# Our core fields are title, location, abstract, bio.
################################################################################
title:    "Talk Title: In Quotes Because : Is a Reserved Character in YAML"

location: TBD

abstract: |

bio: |

################################################################################
# A seminar may have a video. If so, provide the Vimeo video number.
#
# video: 142303577
#
# If not, this field should not be present 
################################################################################
video: 142303577
---