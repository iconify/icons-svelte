<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz52vgbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kz52vgbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:twitter-x" {...props}></Icon>
