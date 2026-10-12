<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bktlkzkpq.css';
import '../../css/r/roo4x4bjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bktlkzkpq"/><path class="roo4x4bjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:translation-check-20" {...props}></Icon>
