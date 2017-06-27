.. include:: ../../../shared/video/additional_transcript_options.rst


.. _Steps for sjson files:

***************************************
Upload an .sjson File (Deprecated)
***************************************

If your course uses .sjson files, you upload the .sjson file for the video
to the **Files & Uploads** page, and then specify the name of the .sjson file
in the video component.

.. note::
  Only older courses that have used .sjson files in the past should use .sjson
  files. All new courses should use .srt files.

#. Obtain the .sjson file from a media company such as 3Play.
#. Change the name of the .sjson file to use the following format.

   ``subs_{video filename}.srt.sjson``

   For example, if the name of your video is **Lecture1a**, the name of your
   .sjson file must be **subs_Lecture1a.srt.sjson**.

#. Upload the .sjson file for your video to the **Files & Uploads** page.
#. Edit or create the video component.
#. Select **Advanced**.
#. In the **Default Timed Transcript** field, enter the file name of your
   video. Do not include `subs_` or `.sjson`. For the example in step 2, you
   would only enter **Lecture1a**.
#. Set the other options that you want.
#. Select **Save**.
