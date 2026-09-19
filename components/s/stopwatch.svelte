<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njfbj4esg.css';
import '../../css/d/dpptcnn_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njfbj4esg"/><path class="dpptcnn_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:stopwatch" {...props}></Icon>
