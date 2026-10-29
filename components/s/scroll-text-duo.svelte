<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/uv7s600ds.css';
import '../../css/u/uc0yabbtt.css';
import '../../css/j/j5ep5hbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="uv7s600ds"/><path class="uc0yabbtt wm-a"/><path class="j5ep5hbtz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:scroll-text-duo" {...props}></Icon>
