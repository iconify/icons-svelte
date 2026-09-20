<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl3jjbtxm.css';
import '../../css/e/ej_-dh--d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kl3jjbtxm"/><path class="ej_-dh--d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:spirit-airlines" {...props}></Icon>
