<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l61x-mbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l61x-mbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sitecore" {...props}></Icon>
