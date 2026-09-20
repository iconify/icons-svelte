<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g75tt3k2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g75tt3k2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-arrow-down" {...props}></Icon>
