# doc_wordpress

get ID user connect
get_current_user_id()


Requete get_post
<?php
    		$args = array(
			  'numberposts' => 5,
			  'post_type'   => 'noo_job',
			  'orderby'     => 'date',
        'order'       => 'DESC',
        'author'      => get_current_user_id()
			);
			$emploi_ffn = get_posts( $args );
 ?>


Parametre $args;

<?php $args = array(
	'posts_per_page'   => 5,
	'offset'           => 0,
	'category'         => '',
	'category_name'    => '',
	'orderby'          => 'date',
	'order'            => 'DESC',
	'include'          => '',
	'exclude'          => '',
	'meta_key'         => '',
	'meta_value'       => '',
	'post_type'        => 'post',
	'post_mime_type'   => '',
	'post_parent'      => '',
	'author'	   => '',
	'author_name'	   => '',
	'post_status'      => 'publish',
	'suppress_filters' => true 
);
$posts_array = get_posts( $args ); ?>





















