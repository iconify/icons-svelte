<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyzben50c.css';
import '../../css/y/ylpvizbha.css';
import '../../css/a/atgoxpbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uyzben50c"/><path class="ylpvizbha"/><path class="atgoxpbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sensor-20" {...props}></Icon>
