<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/u1jdk2vpr.css';
import '../../css/e/e--mbmb3x.css';
import '../../css/d/d59m1yvcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="u1jdk2vpr"/><path class="e--mbmb3x wm-a"/><path class="d59m1yvcb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:signpost-duo" {...props}></Icon>
