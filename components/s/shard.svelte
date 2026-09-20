<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdq15rypm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sdq15rypm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:shard" {...props}></Icon>
