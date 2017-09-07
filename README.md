This repository contains a matching between the LFM-1b dataset (http://www.cp.jku.at/datasets/LFM-1b/) and the Million Song Dataset (https://labrosa.ee.columbia.edu/millionsong/).

LFM-1b contains user-song play counts like the MSD Taste Profile Subset, but it is much larger (20 times as many user interactions) and matches to nearly 700k tracks in MSD instead of 380k.

Tracks are matched by case-normalized artist name and track title. This normalization scheme is not entirely unique. Thus while there are 630931 matchings, there are 664880 matched LFM-1b tracks, 694519 matched MSD song ids, and 695383 matched MSD track ids.
