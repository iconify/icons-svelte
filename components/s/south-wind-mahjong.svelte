<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_ijudcua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="d_ijudcua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:south-wind-mahjong" {...props}></Icon>
