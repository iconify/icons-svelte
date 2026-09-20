<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk7iwbbts.css';
import '../../css/l/lprgm5wxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rk7iwbbts"/><path class="lprgm5wxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ultimate-certificate-manager-dark" {...props}></Icon>
