<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6ba8lbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6ba8lbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:swipe-down-04" {...props}></Icon>
