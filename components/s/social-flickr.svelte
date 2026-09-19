<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg3dtm9tv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="dg3dtm9tv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-flickr" {...props}></Icon>
