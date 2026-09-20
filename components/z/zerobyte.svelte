<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1gv4pp8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i1gv4pp8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zerobyte" {...props}></Icon>
