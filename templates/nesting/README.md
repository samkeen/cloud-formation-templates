# Template Nesting

Cloud Formation templates can be nested to reduce duplication.

https://blogs.aws.amazon.com/application-management/post/Tx1T9JYQOS8AB9I/Use-Nested-Stacks-to-Create-Reusable-Templates-and-Support-Role-Specialization

http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-properties-stack.html

http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/quickref-cloudformation.html#d0e9186

# Usage

You can only reference nested stacks that are stored in S3, so upload `vpc-simple.template` to your S3, then launch
`ec2-nested-vpc-example.template`.