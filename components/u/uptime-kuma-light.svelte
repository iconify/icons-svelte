<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvq1iklbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":622,"height":622};
const content = `<path class="dvq1iklbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:uptime-kuma-light" {...props}></Icon>
