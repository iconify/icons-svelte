<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq0-f_nih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rq0-f_nih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:searxng" {...props}></Icon>
