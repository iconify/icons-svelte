<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx1_rzvjt.css';
import '../../css/c/cp3lf9pre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kx1_rzvjt"/><path clip-rule="evenodd" class="cp3lf9pre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-keyhole-minimalistic-bold" {...props}></Icon>
