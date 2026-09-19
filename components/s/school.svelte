<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/c/csv7r3b2q.css';
import '../../css/i/if54ilp2r.css';
import '../../css/b/b6qpo7bvh.css';
import '../../css/h/hat4q3btl.css';
import '../../css/j/jiwab4g6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="csv7r3b2q"/><path class="if54ilp2r"/><path class="b6qpo7bvh"/><path class="hat4q3btl"/><path class="jiwab4g6x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:school" {...props}></Icon>
