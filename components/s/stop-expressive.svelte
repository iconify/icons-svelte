<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr2hq2bll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xr2hq2bll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:stop-expressive" {...props}></Icon>
