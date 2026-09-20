<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0e89qu-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s0e89qu-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:table-density-normal" {...props}></Icon>
