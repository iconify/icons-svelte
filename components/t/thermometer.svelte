<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddvgu8bvv.css';
import '../../css/m/myu9avgru.css';
import '../../css/u/umtr24biu.css';
import '../../css/s/sq84s46_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ddvgu8bvv"><path class="myu9avgru"/><path class="umtr24biu"/><path class="sq84s46_s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:thermometer" {...props}></Icon>
