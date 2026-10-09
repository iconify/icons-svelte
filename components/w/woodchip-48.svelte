<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu4o8i4pj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uu4o8i4pj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:woodchip-48" {...props}></Icon>
