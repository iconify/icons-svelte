<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2-ush-fl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2-ush-fl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:treasure-map-line" {...props}></Icon>
