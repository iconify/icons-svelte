<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/w0uv33vum.css';
import '../../css/f/f3-iv-3ow.css';
import '../../css/w/w0oyb6d3k.css';
import '../../css/r/re6gqqbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="w0uv33vum"/><path class="f3-iv-3ow wm-a"/><path class="w0oyb6d3k"/><path class="re6gqqbct wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sailboat" {...props}></Icon>
