# Shriek

Shriek is an open source Yelp clone build on Ruby on Rails.

## Usage

Requires 
1) Ruby 1.9
2) Rails 4.0+
3) Amazon S3 for image hosting


### Issues

S3 storage for images is currently not working due to a mix-up between the carrierwave gem and S3 api keys.
If this is not fixed, I will refactor the code to use drop box instead.


## Releases 

Current Release: 0.1.1
	- Base Site w/o styling online
	- Restaurants support images & general descriptors
	- No auth yet.


## License

Copyright (c) Andrew Hoffman and contributors. All rights reserved.

The use and distribution terms for this software are covered by the
Eclipse Public License 1.0 (http://opensource.org/licenses/eclipse-1.0.php)
which can be found in the file epl.html at the root of this distribution.
By using this software in any fashion, you are agreeing to be bound by
the terms of this license.
You must not remove this notice, or any other, from this software.

