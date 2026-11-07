<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1bvnqfvt.css';
import '../../css/m/m4styj0nb.css';
import '../../css/m/mz1do-bvr.css';
import '../../css/t/t5k-_f5ou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1bvnqfvt"/><path class="m4styj0nb"/><path class="mz1do-bvr"/><path clip-rule="evenodd" class="t5k-_f5ou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-cross-square-outline" {...props}></Icon>
