## What is this?
CodeIgniter-StatHat is a library for CodeIgniter. This library makes it easy to interact with
[StatHat](http://www.stathat.com), a tool to track statistics and events in your code.

## Usage
Start by adding Stathat.php to your application -> libraries folder. After that, load
your library:

	$this->load->library('Stathat');
	
Now you just make your calls to StatHat, like this:

	$this->stathat->stathat_ez_count('my@email.com', 'Messages sent', 1);
	
## Changelog

### 1.0
* Made StatHats's default PHP code compatible with CodeIgniter, more features coming. Am i doing this right?

## Note
I'm learning how to use Git and Github. If something is messed up, please don't be mad!