<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bun4fvbdj.css';
import '../../css/u/uqjvq3bgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bun4fvbdj"/><path class="uqjvq3bgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scanopy" {...props}></Icon>
