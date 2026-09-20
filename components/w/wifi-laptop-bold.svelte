<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxgd-b81d.css';
import '../../css/m/mxzgrlbhg.css';
import '../../css/f/frbtlhrdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxgd-b81d"/><path class="mxzgrlbhg"/><path class="frbtlhrdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:wifi-laptop-bold" {...props}></Icon>
