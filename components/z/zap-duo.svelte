<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxpg3nbkx.css';
import '../../css/d/d0vi13cyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxpg3nbkx secondary"/><path class="d0vi13cyo primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:zap-duo" {...props}></Icon>
