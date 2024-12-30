
## Version 1

### Changes:

Terraform will perform the following actions:

[1m  # aws_instance.ec2[0m will be updated in-place
[0m  [33m~[0m[0m resource "aws_instance" "ec2" {
        id                                   = "i-0f734ea7b8a62d407"
      [33m~[0m[0m tags                                 = {
          [33m~[0m[0m "Name"    = "MyEC2Instance3" [33m->[0m[0m "MyEC2Instance4"
            "Version" = "v1.0.0"
        }
      [33m~[0m[0m tags_all                             = {
          [33m~[0m[0m "Name"    = "MyEC2Instance3" [33m->[0m[0m "MyEC2Instance4"
            [90m# (1 unchanged element hidden)[0m[0m
        }
        [90m# (30 unchanged attributes hidden)[0m[0m

        [90m# (8 unchanged blocks hidden)[0m[0m
    }

[0m::debug::Terraform exited with code 0.
::debug::stderr: 
::debug::exitcode: 0

