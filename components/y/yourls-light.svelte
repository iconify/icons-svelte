<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdo8u4pgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sdo8u4pgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yourls-light" {...props}></Icon>
