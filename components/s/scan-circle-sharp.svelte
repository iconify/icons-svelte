<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f31idh9jr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f31idh9jr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:scan-circle-sharp" {...props}></Icon>
