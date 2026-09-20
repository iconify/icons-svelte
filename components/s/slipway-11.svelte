<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5p3_7hxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="x5p3_7hxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:slipway-11" {...props}></Icon>
