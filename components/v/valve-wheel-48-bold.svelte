<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqr8yp28h.css';
import '../../css/b/blas98ktz.css';
import '../../css/m/mbe4uxbkg.css';
import '../../css/w/wrnacwbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fqr8yp28h"/><path class="blas98ktz"/><path class="mbe4uxbkg"/><path class="wrnacwbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:valve-wheel-48-bold" {...props}></Icon>
