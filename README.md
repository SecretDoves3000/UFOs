# UFO Finder

## Project Overview
This page presents UFO sighting data in a searchable format, allowing users to filter the data by certain parameters, aiding in their investigations.

## Results
Users may see the unfiltered data by leaving all the filter search fields on the left empty as shown here:

[[[image]]]

Filling in one piece of information in the filter search fields will filter the data according to the inputs. Here we have sightings from Arkansas (abbreviated as ak) and then a further filter to show only the sightings from Arkansas which where spherical in shape.

[[[image]]]
[[[image]]]

## Summary

As a first product, this database works well, but there are still a number of issues to handle. As it stands, the filters are updated when they are changed, but only after the user clicks off of the element or presses enter to finalize the change. This is unintuitive, and leads to a moment of confusion when first encountering the user interface. Changing this to update dynamically would be a much smoother experience.

Also, the search is exact matching, meaning that if users use the properly capitalized state abbreviate CA for california, this will not match the sighting data which is labeled "ca" for california. More generally, less strict matching makes the search more intuitive to use. For example using partial strings -- such as typing "ros" in the city, and getting results for "roswell" or "rosewood" etc. -- would make the page easier to use as well as feeling more dynamic.