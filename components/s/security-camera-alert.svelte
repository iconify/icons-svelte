<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpz_rl4wy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qpz_rl4wy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:security-camera-alert" {...props}></Icon>
