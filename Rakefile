desc "deploy code"
task :deploy do
  `s3cmd sync _site/ s3://meet.subelsky.com/ -P -c ~/.s3cfg; say -v zarvox 'S3 deployment complete'`
end
