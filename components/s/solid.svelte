<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u21r97bfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u21r97bfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:solid" {...props}></Icon>
