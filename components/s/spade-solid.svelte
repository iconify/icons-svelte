<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nicg6-4io.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nicg6-4io"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:spade-solid" {...props}></Icon>
