<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi7wm9b_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fi7wm9b_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:volume-mute-outline" {...props}></Icon>
