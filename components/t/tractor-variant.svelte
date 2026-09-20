<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trbdaebmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trbdaebmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tractor-variant" {...props}></Icon>
