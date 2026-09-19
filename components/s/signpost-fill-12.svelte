<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgxf4lblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="pgxf4lblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:signpost-fill-12" {...props}></Icon>
