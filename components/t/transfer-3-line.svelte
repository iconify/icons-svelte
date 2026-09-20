<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmu8so9_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmu8so9_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:transfer-3-line" {...props}></Icon>
