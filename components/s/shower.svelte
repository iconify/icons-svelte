<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3e-2qm4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d3e-2qm4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:shower" {...props}></Icon>
