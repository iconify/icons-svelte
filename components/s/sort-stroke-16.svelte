<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbe60jbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pbe60jbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:sort-stroke-16" {...props}></Icon>
