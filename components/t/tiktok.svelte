<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlho3t-wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wlho3t-wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:tiktok" {...props}></Icon>
