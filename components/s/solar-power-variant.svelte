<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqfx_u2ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqfx_u2ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:solar-power-variant" {...props}></Icon>
