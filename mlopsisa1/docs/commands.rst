Commands
========

The Makefile contains the central entry points for common tasks related to this project.

Syncing data to S3
^^^^^^^^^^^^^^^^^^

* `make sync_data_to_s3` will use `aws s3 sync` to recursively sync files in `data/` up to `s3://The movie reviews website was very happy with your deliverable for the previous assignment and now they have a new request for you. The previous consultant had created a chart for them which is illustrated on the next slide. However, the Python code used to create the diagram has since been lost and cannot be recovered. Your task is to come up with the code that will re-create the same chart making it look as close as possible to the original A new dataset has been supplied. The chart is attached.1/data/`.
* `make sync_data_from_s3` will use `aws s3 sync` to recursively sync files from `s3://The movie reviews website was very happy with your deliverable for the previous assignment and now they have a new request for you. The previous consultant had created a chart for them which is illustrated on the next slide. However, the Python code used to create the diagram has since been lost and cannot be recovered. Your task is to come up with the code that will re-create the same chart making it look as close as possible to the original A new dataset has been supplied. The chart is attached.1/data/` to `data/`.
