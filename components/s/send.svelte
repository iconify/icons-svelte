<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl888_buv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kl888_buv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:send" {...props}></Icon>
