---
title: rtp_hook_end_post
---

### Description


Adds content at the end of every .post.


### Example



    
    function custom_hook_end_post() { ?>
    <p>This is the end of .post</p><?php
    }
    add_action( 'rtp_hook_end_post', 'custom_hook_end_post' );
