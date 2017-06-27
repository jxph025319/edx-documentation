Making course videos available to as many learners as possible can be a complex
undertaking.

* Videos need to be available from more than one host site to play in locations
  around the world.
* Videos need to be available in several different formats to play on
  desktop computers, laptops, smartphones, and other mobile devices.
* Videos need to be available for both download and streaming for learners with
  slow or intermittent Internet connections.

..
..
..

THEREFORE
..
..
..

All course videos should be posted to YouTube. By default, the video player
accesses your YouTube videos.

Because YouTube is not available in all locations, however, we recommend that
you also post copies of your videos on a third-party hosting site such as
`Amazon S3`_. When a learner views a video in your
course, if YouTube is not available in that learner's location or if the
YouTube video does not play, the video on the backup site starts playing
automatically. You can also allow the learners to download the video from the
backup site.

.. important::
  After you post your video online, make sure you have the URL for that copy of
  the video. If you post copies of your video in more than one place, make sure
  you have the URL for each video location.

==================
YouTube
==================

After you create your video, upload the video to `YouTube`_.

==================
Other Sites
==================

You can use any video backup site that you want. However, keep in mind that the
site where you post the videos might need to handle high traffic volume.

.. note::
 The URL for the video that you post on a third-party site must end in .mp4,
 .mpeg, .webm, or .ogg. (To help make sure all standard browsers can play your
 video, edX **strongly** recommends that you use .mp4 format.) The video player
 cannot support videos that you post on sites such as Vimeo.

If you (or your beta testers or learners) encounter an error when you view a
course video, it might be the result of one of these browser-related problems.

* Verify that the viewer's browser is up to date. For example, some older
  versions of the Mozilla Firefox browser did not play .mp4 video files. These
  problems do not occur in more recent browser versions.

  For more information, see `Media formats supported by the HTML audio and
  video elements`_.

* Verify that file metadata, particularly the MIME type, is correctly set on
  the host site. For example, when edX offered support for Internet Explorer 10
  browsers, it was found that videos did not play if the MIME type was not set.
  The HTTP header ``Content-Type`` had to be set to video/mp4 for an .mp4 file.

  As an example of how you might set metadata on a video backup site, the
  *Console User Guide* for the Amazon Simple Storage Service provides this
  information about `editing object metadata`_.

.. include:: ../../../links/links.rst
