<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0phu2bbs.css';
import '../../css/q/q07-vixib.css';
import '../../css/q/qkr8c8bcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><circle class="q07-vixib"/><path class="qkr8c8bcd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-plus-circle-bold" {...props}></Icon>
