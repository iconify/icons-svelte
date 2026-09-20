<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skbd124kr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skbd124kr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:umami" {...props}></Icon>
