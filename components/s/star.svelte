<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzcl-4a-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzcl-4a-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:star" {...props}></Icon>
