<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnq331bdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnq331bdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sphere-diameter-outline" {...props}></Icon>
