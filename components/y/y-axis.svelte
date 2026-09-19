<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrifaiata.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nrifaiata"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:y-axis" {...props}></Icon>
