<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dztpopbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="dztpopbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:tray-growth-chart-26" {...props}></Icon>
