<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhdzi9lsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dhdzi9lsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:scan-code" {...props}></Icon>
