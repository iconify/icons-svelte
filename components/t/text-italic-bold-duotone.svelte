<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx3fe_t0r.css';
import '../../css/r/rj_m6ufoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kx3fe_t0r"/><path class="rj_m6ufoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-italic-bold-duotone" {...props}></Icon>
