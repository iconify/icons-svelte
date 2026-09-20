<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-jl_-_hw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-jl_-_hw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:spray-image" {...props}></Icon>
