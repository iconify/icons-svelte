<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3awb6ryc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="p3awb6ryc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:spiderchart" {...props}></Icon>
