<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gphxlac4x.css';
import '../../css/k/k5rc8zisb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gphxlac4x"/><path class="k5rc8zisb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:telegram" {...props}></Icon>
