<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rizeqw8_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rizeqw8_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:up-arrow-square" {...props}></Icon>
