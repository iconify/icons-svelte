<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqcehw8gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqcehw8gx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-cog" {...props}></Icon>
