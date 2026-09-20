<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epha_l8gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epha_l8gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:shrink-horizontal" {...props}></Icon>
