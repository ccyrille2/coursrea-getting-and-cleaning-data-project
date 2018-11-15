  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><h1><a id="user-content-getting-and-cleaning-data---course-project" class="anchor" aria-hidden="true" href="#getting-and-cleaning-data---course-project"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Getting and Cleaning Data - Course Project</h1>
<p>This is the course project for the Getting and Cleaning Data Coursera course.
The R script, <code>run_analysis.R</code>, does the following:</p>
<ol>
<li>Download the dataset if it does not already exist in the working directory</li>
<li>Load the activity and feature info</li>
<li>Loads both the training and test datasets, keeping only those columns which
reflect a mean or standard deviation</li>
<li>Loads the activity and subject data for each dataset, and merges those
columns with the dataset</li>
<li>Merges the two datasets</li>
<li>Converts the <code>activity</code> and <code>subject</code> columns into factors</li>
<li>Creates a tidy dataset that consists of the average (mean) value of each
variable for each subject and activity pair.</li>
</ol>
<p>The end result is shown in the file <code>tidy.txt</code>.</p>
</article>
  </div>
