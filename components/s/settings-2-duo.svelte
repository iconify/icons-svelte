<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qn_01acft.css';
import '../../css/t/tsgnk6b9n.css';
import '../../css/p/p77vdobsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="qn_01acft wm-a"/><path class="tsgnk6b9n"/><path class="p77vdobsr wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:settings-2-duo" {...props}></Icon>
