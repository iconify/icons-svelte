<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0mh3lbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="s0mh3lbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:star-duo" {...props}></Icon>
