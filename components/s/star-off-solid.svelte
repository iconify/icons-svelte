<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jemga0b0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jemga0b0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:star-off-solid" {...props}></Icon>
