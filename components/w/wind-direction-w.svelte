<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xiuit_b-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1542,"height":1542};
const content = `<path class="xiuit_b-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wind-direction-w" {...props}></Icon>
