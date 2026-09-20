<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7gk634bm.css';
import '../../css/t/t95fy_bam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q7gk634bm"/><path class="t95fy_bam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:wifi-full-solid" {...props}></Icon>
