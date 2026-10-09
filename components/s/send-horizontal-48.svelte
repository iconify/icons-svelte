<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrm4pgbwi.css';
import '../../css/v/vs6my9btk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wrm4pgbwi"/><path class="vs6my9btk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:send-horizontal-48" {...props}></Icon>
