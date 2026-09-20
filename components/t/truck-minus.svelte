<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kug2_lg1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kug2_lg1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:truck-minus" {...props}></Icon>
