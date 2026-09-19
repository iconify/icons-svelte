<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-vv4s95z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-vv4s95z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:search-x" {...props}></Icon>
