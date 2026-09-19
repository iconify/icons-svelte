<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv4cnv59j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zv4cnv59j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:swipe-up-05" {...props}></Icon>
