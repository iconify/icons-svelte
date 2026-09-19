<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnqrz6ssl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="wnqrz6ssl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:shield-1-duo" {...props}></Icon>
