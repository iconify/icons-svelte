<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nowsdr-3b.css';
import '../../css/x/xaxgc568e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nowsdr-3b"/><path class="xaxgc568e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:watch-48-bold" {...props}></Icon>
