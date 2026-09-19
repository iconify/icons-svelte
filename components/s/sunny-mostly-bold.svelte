<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqgqhc_5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="qqgqhc_5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sunny-mostly-bold" {...props}></Icon>
