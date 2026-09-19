<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1ol51blr.css';
import '../../css/y/yzhyb8bwk.css';
import '../../css/p/p18cy_m8i.css';
import '../../css/l/lj5rkfb6q.css';
import '../../css/q/qy_260b7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a1ol51blr"/><path class="yzhyb8bwk"/><path class="p18cy_m8i"/><path class="lj5rkfb6q"/><path class="qy_260b7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:zoom-pan" {...props}></Icon>
