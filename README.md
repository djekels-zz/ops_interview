# ops_interview

Welcome to the Raise Ops practical exercise.  These are intended to be complete instructions, so please ask about any ambiguities you may find.

## Deliverables

Please submit a link to a *private* repo or a tarball of your scripts via email to the engineer that send you this problem.
All work should be recreatable via the scripts you submit.

## Technologies

Chef, Vagrant, Nginx.  This is intended as a real-world exercise, so please do not reinvent the wheel.  Make use of Opscode cookbooks, Brekshelf, etc. as needed.

## Instructions

1.  Install NGINX and configure a Virtualhost to listen on port 8080.
1.  The recipe should serve the content here: https://github.com/CouponTrade/ops_interview using git.
1.  For the PHP config, change the expose_php variable to off and the memory limit per thread to 512MB.
1.  Visiting the Vagrant machine URL on port 8080 in a web browser should show the parameters modified by visiting the index.php page.
