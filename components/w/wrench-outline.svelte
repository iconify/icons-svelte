<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxn-5736a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxn-5736a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wrench-outline" {...props}></Icon>
