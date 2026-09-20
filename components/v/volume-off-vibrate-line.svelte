<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1a2-qbfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1a2-qbfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:volume-off-vibrate-line" {...props}></Icon>
