<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npfsumi_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="npfsumi_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:tray" {...props}></Icon>
