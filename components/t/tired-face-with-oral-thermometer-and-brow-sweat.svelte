<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xijr_zb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xijr_zb0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tired-face-with-oral-thermometer-and-brow-sweat" {...props}></Icon>
