<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqr2b_b3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sqr2b_b3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tracktor" {...props}></Icon>
