<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo8f-0bzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yo8f-0bzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-comfy" {...props}></Icon>
