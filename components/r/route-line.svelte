<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q50r76h_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q50r76h_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:route-line" {...props}></Icon>
