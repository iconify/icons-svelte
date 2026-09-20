<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy6hdmbvr.css';
import '../../css/q/qfu31qb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iy6hdmbvr"/><path class="qfu31qb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:scissors-3-line" {...props}></Icon>
