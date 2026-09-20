<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eevgm_byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eevgm_byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:warm-up-3-fill" {...props}></Icon>
