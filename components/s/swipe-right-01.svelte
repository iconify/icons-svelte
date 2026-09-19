<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulzixyb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulzixyb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:swipe-right-01" {...props}></Icon>
