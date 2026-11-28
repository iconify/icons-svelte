<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxrtblbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxrtblbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:speaker-minus" {...props}></Icon>
