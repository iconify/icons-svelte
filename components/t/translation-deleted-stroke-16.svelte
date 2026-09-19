<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf5y5ccyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mf5y5ccyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:translation-deleted-stroke-16" {...props}></Icon>
