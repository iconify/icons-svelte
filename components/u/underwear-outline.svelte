<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8wg46bdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8wg46bdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:underwear-outline" {...props}></Icon>
