<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi6522bgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wi6522bgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:share-alt-square" {...props}></Icon>
