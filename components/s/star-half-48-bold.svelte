<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/domb1qbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="domb1qbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:star-half-48-bold" {...props}></Icon>
