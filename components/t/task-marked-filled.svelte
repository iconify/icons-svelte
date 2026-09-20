<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_hxwwbci.css';
import '../../css/n/nd9qslmdc.css';
import '../../css/q/q9vu7mxpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_hxwwbci"/><path class="nd9qslmdc"/><path class="q9vu7mxpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:task-marked-filled" {...props}></Icon>
