<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/niiqcdbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="niiqcdbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:tree" {...props}></Icon>
