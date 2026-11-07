<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woc-gln8b.css';
import '../../css/x/xh_rgzqbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="woc-gln8b"/><path class="xh_rgzqbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:settings-minimalistic-bold-duotone" {...props}></Icon>
