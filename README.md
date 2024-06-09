# Archivist

Doanloads content for archival.

# Requirements

* `yt-dlp`;
* Youtube cookies exported to `~/ytdl.txt`

# Usage

Create a directory containing `what.txt` listing sources to archive, such as the URL to a Toutube channel's "videos" tab, or `--batch-file list.txt` for locally maintained playlists.  If the archived content is to be datestamped, also create the file `timeseries`.  Within any directory with those files, run `./path/to/this/repo/archive` to download any content listed that you haven't yet downloaded.

Does not archive currently live content.
