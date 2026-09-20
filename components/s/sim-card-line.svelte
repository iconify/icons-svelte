<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l36sqt1cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l36sqt1cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sim-card-line" {...props}></Icon>
