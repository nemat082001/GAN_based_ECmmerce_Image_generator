Commands
========

The Makefile contains the central entry points for common tasks related to this project.

Syncing data to S3
^^^^^^^^^^^^^^^^^^

* `make sync_data_to_s3` will use `aws s3 sync` to recursively sync files in `data/` up to `s3://This project focused on developing an advanced Generative Adversarial Network (GAN) to create photorealistic images of e-commerce products, significantly enhancing the scalability and quality of product representation. The system was trained on a dataset of 25,000 images, achieving an impressive accuracy of 88%, reflecting its capability to generate diverse, high-quality images for use in e-commerce platforms./data/`.
* `make sync_data_from_s3` will use `aws s3 sync` to recursively sync files from `s3://This project focused on developing an advanced Generative Adversarial Network (GAN) to create photorealistic images of e-commerce products, significantly enhancing the scalability and quality of product representation. The system was trained on a dataset of 25,000 images, achieving an impressive accuracy of 88%, reflecting its capability to generate diverse, high-quality images for use in e-commerce platforms./data/` to `data/`.
