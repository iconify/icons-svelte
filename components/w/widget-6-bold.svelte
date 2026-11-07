<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wui8tcbyn.css';
import '../../css/k/kh6yd2nhl.css';
import '../../css/i/i_vz0301x.css';
import '../../css/z/ziyj3ibvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wui8tcbyn"/><path class="kh6yd2nhl"/><path class="i_vz0301x"/><path class="ziyj3ibvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:widget-6-bold" {...props}></Icon>
