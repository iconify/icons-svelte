<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwn6c4bjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwn6c4bjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:srg-ssr" {...props}></Icon>
