Disqus Comments
======

Comments for Tentacel CMS through Disqus

In the Blog tempalte you will need to pass
```
<? disqus::comments( $post ) ?>
```

In the Post tempalt/type you will need to include
```
<? disqus::comments_form( $post->id ); ?>
```