<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue4dxlbfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue4dxlbfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:spades" {...props}></Icon>
