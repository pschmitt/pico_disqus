# pico_disqus

Pico plugin for embedding Disqus in your website

## Usage

Add your Disqus ID to Pico's `config.php`:

```php
$config['disqus_id'] = 'MYID'; 
```

Now in your theme add `{{ disqus_comments }}` wherever you want to display the comments section.
