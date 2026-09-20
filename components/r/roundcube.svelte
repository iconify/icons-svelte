<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spikp7boj.css';
import '../../css/m/mxutx8bjy.css';
import '../../css/p/pvcdc057u.css';
import '../../css/m/m49a1tu-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="spikp7boj"/><path class="mxutx8bjy"/><path class="pvcdc057u"/><path class="m49a1tu-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:roundcube" {...props}></Icon>
