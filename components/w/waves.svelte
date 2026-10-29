<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gwq6sk28r.css';
import '../../css/k/kgbn2cc9v.css';
import '../../css/h/h9urc9bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="gwq6sk28r wm-a"/><path class="kgbn2cc9v"/><path class="h9urc9bth wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:waves" {...props}></Icon>
