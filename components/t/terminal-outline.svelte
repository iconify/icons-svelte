<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve_z1ti7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ve_z1ti7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:terminal-outline" {...props}></Icon>
