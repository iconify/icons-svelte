<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1zioacio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1zioacio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:share-2" {...props}></Icon>
