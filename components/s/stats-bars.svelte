<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd9y6e3na.css';
import '../../css/p/pvyz65bxh.css';
import '../../css/t/tvasz164u.css';
import '../../css/g/g23x1rbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zd9y6e3na"/><path class="pvyz65bxh"/><path class="tvasz164u"/><path class="g23x1rbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:stats-bars" {...props}></Icon>
