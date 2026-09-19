<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isr_9phgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1152,"height":1664};
const content = `<path class="isr_9phgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:walk" {...props}></Icon>
