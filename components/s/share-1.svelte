<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htge7-ppk.css';
import '../../css/j/jufqgnzlz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htge7-ppk"/><path class="jufqgnzlz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:share-1" {...props}></Icon>
