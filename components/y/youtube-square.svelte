<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a80mw2isl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="a80mw2isl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:youtube-square" {...props}></Icon>
