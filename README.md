# wordpress-pro
```
add_image_size( string $name, int $width, int $height, bool|array $crop = false )
add_image_size wordpress
```

```
// This theme uses Featured Images (also known as post thumbnails) for per-post/per-page.
		add_theme_support( 'post-thumbnails' );
```

```
// Registering navigation menu.
		register_nav_menu(
			'primary',
			esc_html__( 'Primary Menu', 'colormag' )
		);
```

```
// Cropping the images to different sizes to be used in the theme.
		add_image_size( 'colormag-highlighted-post', 392, 272, true );
		add_image_size( 'colormag-featured-post-medium', 390, 205, true );
		add_image_size( 'colormag-featured-post-small', 130, 90, true );
		add_image_size( 'colormag-featured-image', 800, 445, true );
```

```
get_the_post_thumbnail( int|WP_Post $post = null, string|int[] $size = 'post-thumbnail', string|array $attr = '' )
```

```
get_post_meta( int $post_id, string $key = '', bool $single = false )
Retrieves a post meta field for the given post ID.
```

```
https://developer.wordpress.org/reference/functions/get_option/
get_option( string $option, mixed $default = false )
Retrieves an option value based on an option name.
```
