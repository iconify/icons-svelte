<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rawbtr-6p.css';
import '../../css/p/p28r9n0-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="rawbtr-6p"/><path class="p28r9n0-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:shooting-star" {...props}></Icon>
