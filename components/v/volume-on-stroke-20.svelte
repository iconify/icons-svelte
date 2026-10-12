<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyz7sxb6l.css';
import '../../css/z/zhwfo4bgb.css';
import '../../css/n/ngnbw93bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yyz7sxb6l"/><path class="zhwfo4bgb"/><path class="ngnbw93bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:volume-on-stroke-20" {...props}></Icon>
