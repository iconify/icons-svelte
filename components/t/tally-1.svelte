<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1a2m1m3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1a2m1m3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tally-1" {...props}></Icon>
