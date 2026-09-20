<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uagq5sbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uagq5sbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:sharing" {...props}></Icon>
