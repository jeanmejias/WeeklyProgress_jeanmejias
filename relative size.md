##relative resize

`width`:100%
`max-width: 100%` the image will increase till the max that it is

## if you want 2 img by side
use a realitve size
`width: 50%;`
`margiin-right: 10px;`
`width: calc((100% - 10%)/2);`

use a type selector:

`img: last-of-type {
margin-right: 0px;`

`body {
      margin: 0;
    }
    img {
      float: left;
	margin-right: 10px;
	width: calc((100% - 20px)/3)
	    }
    img:last-of-type {
	margin-right: 0;
}`
