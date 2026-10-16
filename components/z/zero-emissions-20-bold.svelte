<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1h9j1hcr.css';
import '../../css/y/y497hebmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s1h9j1hcr"/><path class="y497hebmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:zero-emissions-20-bold" {...props}></Icon>
