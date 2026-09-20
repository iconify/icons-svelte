<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4a5arb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q4a5arb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:user" {...props}></Icon>
