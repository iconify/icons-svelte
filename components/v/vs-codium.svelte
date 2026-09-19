<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp7upebym.css';
import '../../css/k/k8zwn064d.css';
import '../../css/z/zry2zrb8z.css';
import '../../css/q/q1xj7ub5q.css';
import '../../css/l/lmb380bdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="xp7upebym"><path class="k8zwn064d"/><path class="zry2zrb8z"/><path class="q1xj7ub5q"/><path class="lmb380bdf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:vs-codium" {...props}></Icon>
