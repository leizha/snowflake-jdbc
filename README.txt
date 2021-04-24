This is forked from the official snowflake driver. The only changes are:
- the project didn't build because it referenced internal snowflake repository. I removed it.
- the driver couldn't save credentials on mac because jna jar files were missing from the release jar. I added them.
