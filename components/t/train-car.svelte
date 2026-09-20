<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3o4tj12j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3o4tj12j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:train-car" {...props}></Icon>
