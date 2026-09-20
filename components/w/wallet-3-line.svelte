<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqx3i42jl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqx3i42jl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:wallet-3-line" {...props}></Icon>
