<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9_-f5bkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r9_-f5bkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:shazam" {...props}></Icon>
