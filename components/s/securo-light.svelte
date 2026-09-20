<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcdh9_b5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bcdh9_b5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:securo-light" {...props}></Icon>
