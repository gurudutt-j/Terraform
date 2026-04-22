variable "s3_bucket_name" {
  description = "The name of the S3 bucket to create"
  type        = string
}

resource "aws_s3_bucket" "bucket1" {
  bucket = var.s3_bucket_name
}
