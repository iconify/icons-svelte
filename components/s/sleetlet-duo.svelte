<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdiv--brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="pdiv--brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sleetlet-duo" {...props}></Icon>
