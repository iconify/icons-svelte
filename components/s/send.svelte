<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixn7vnb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ixn7vnb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:send" {...props}></Icon>
