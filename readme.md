# Football event visualization

The [readme.ipynb](./readme.ipynb) is developed to visualize the football match events.

The raw dataset is parsed into the **stuff**

![stuff](./doc/stuff.png)

The stuff contains all the information.
For example, if you select the ball (55) or the referee (11180)

![ball-referees](./doc/ball-referees.png)

the events are processed and turned into the dataframe as the well-formatted

![dataframe](./doc/dataframe.png)

Based on it, the following visualization is made to but not limited to

-   The hot map of events
    ![hotmap](./doc/hotmap.png)

-   The relationship between speed and distance
    ![speed-distance](./doc/speed-distance.png)

-   The relationship between speed and duration
    ![speed-duration](./doc/speed-duration.png)

-   The histogram of the speed
    ![speed-hist](./doc/speed-hist.png)

-   The trace scatters in every frame (the fps is 10)
    ![trace-by-minutes](./doc/trace-by-minutes.png)

-   The trace line colored by the speed
    ![trace-by-speed](./doc/trace-by-speed.png)

## Acknowledgement

The data is collected in the github repository,
https://github.com/SkillCorner/opendata.git,
read the [readme-origin.md](./README-origin.md) for detail.
