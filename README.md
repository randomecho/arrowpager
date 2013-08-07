# ArrowPager - jQuery plugin

Page through your site using the arrow keys. 

Hooks onto your already there pagination links and does the lazy for you.

- <kbd>←</kbd> (Left arrow on keyboard) - Go to previous page

- <kbd>→</kbd> (Right arrow on keyboard) - Go to next page

That's all it's supposed to do.


## Usage

Include the script on the page:

    <script src="arrowpager.js"></script>

Add this class to the link that goes to the "previous" page:

    arrowpager-prev
    
Add this class to the link that goes to the "next" page:

    arrowpager-next


### Example

Here, we are currently on the second page in a series. Previous and Next link 
to the first and third pages respectively. Adding in the required classes will 
now allow the site visitor to jump to those pages with the tap of the arrow 
keys on their keyboard. 

    <ul>
      <li><a href="/quiver?page=1" class="arrowpager-prev">Previous</a></li>
      <li><a href="/quiver?page=1">1</a></li>
      <li><a href="/quiver?page=2" class="current-page">2</a></li>
      <li><a href="/quiver?page=3">3</a></li>
      <li><a href="/quiver?page=3" class="arrowpager-next">Next</a></li>
    </ul>


## License

[BSD 3-Clause License](http://opensource.org/licenses/BSD-3-Clause)