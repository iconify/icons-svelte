<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxevvmbhb.css';
import '../../css/p/p1v655b3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxevvmbhb"/><path class="p1v655b3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:sd-card-sync-bold" {...props}></Icon>
