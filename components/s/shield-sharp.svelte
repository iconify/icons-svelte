<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if1ow3fmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="if1ow3fmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:shield-sharp" {...props}></Icon>
