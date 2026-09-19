<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcw__-b2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wcw__-b2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-activity" {...props}></Icon>
