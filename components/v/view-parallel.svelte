<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3z-_s0sg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3z-_s0sg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-parallel" {...props}></Icon>
