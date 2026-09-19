<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flawucc0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="flawucc0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:signpost-fill-16" {...props}></Icon>
