<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gipyp_0-p.css';
import '../../css/z/z_reqjbtp.css';
import '../../css/m/m9hxvkhgr.css';
import '../../css/q/q0i3y0d1k.css';
import '../../css/c/cb_2hhwip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="gipyp_0-p"/><path class="z_reqjbtp"/><path class="m9hxvkhgr"/><path class="q0i3y0d1k"/><path class="cb_2hhwip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:saudi-arabia" {...props}></Icon>
