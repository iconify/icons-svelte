<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_nk98b2c.css';
import '../../css/d/d9qn9ybwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b_nk98b2c"/><path class="d9qn9ybwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vertigo-comics" {...props}></Icon>
