<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4h6a7xri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path clip-rule="evenodd" class="i4h6a7xri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:vroundswitch-off" {...props}></Icon>
