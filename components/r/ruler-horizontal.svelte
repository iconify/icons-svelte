<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl2r66bdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pl2r66bdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:ruler-horizontal" {...props}></Icon>
