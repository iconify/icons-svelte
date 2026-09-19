<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq3r5fw2r.css';
import '../../css/i/i_d2xgsxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="lq3r5fw2r"/><path class="i_d2xgsxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:scale-outline" {...props}></Icon>
