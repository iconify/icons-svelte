<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0rewwboe.css';
import '../../css/r/rwf94xd_g.css';
import '../../css/a/axl75o_4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d0rewwboe"/><path class="rwf94xd_g"/><path class="axl75o_4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:soil-moisture-global" {...props}></Icon>
