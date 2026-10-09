<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5pljbc4p.css';
import '../../css/s/s5hz1qbpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w5pljbc4p"/><path class="s5hz1qbpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:torch-20" {...props}></Icon>
