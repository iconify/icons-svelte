<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqm6o8bjf.css';
import '../../css/r/rtz_uvbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qqm6o8bjf"/><path class="rtz_uvbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sort-20-bold" {...props}></Icon>
