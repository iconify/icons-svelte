<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwlc9-kij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwlc9-kij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:solar-power-variant-outline" {...props}></Icon>
