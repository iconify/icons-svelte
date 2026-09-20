<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3ee4zi2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m3ee4zi2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:spinal-vertebrae" {...props}></Icon>
