<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb8a2xbld.css';
import '../../css/m/muj3adbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lb8a2xbld"/><path class="muj3adbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:transfer-horizontal-bold" {...props}></Icon>
