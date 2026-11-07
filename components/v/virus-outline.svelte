<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxe5oobko.css';
import '../../css/w/wz_eimbrd.css';
import '../../css/h/h1vbpgb6s.css';
import '../../css/y/ywjd16bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mxe5oobko"/><path clip-rule="evenodd" class="wz_eimbrd"/><path class="h1vbpgb6s"/><path clip-rule="evenodd" class="ywjd16bsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:virus-outline" {...props}></Icon>
