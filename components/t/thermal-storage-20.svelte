<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjfogtdwu.css';
import '../../css/s/s315aabjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vjfogtdwu"/><path class="s315aabjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermal-storage-20" {...props}></Icon>
