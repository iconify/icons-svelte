<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rszymacgm.css';
import '../../css/m/m31n_gbkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rszymacgm"/><path class="m31n_gbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-top-up-outline" {...props}></Icon>
