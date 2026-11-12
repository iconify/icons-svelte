<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_k-1tony.css';
import '../../css/j/jnok5972w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r_k-1tony"/><path class="jnok5972w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:webhook-tester-light" {...props}></Icon>
