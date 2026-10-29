<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kw37j6fhx.css';
import '../../css/o/odnmdzi_x.css';
import '../../css/d/dorpla9vi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="kw37j6fhx"/><path class="odnmdzi_x"/><path class="dorpla9vi wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:route-duo" {...props}></Icon>
