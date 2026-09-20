<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kft8x8isq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kft8x8isq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:vis-bar-vertical-stacked" {...props}></Icon>
