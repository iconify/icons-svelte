<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r95dy2bbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r95dy2bbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:stopwatch" {...props}></Icon>
