<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbhhc8blo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="xbhhc8blo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:shield-1" {...props}></Icon>
