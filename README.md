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
