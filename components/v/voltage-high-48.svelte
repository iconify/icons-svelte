<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqoqidbfs.css';
import '../../css/o/oa5v05bkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jqoqidbfs"/><path class="oa5v05bkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:voltage-high-48" {...props}></Icon>
