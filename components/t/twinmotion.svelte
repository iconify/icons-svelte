<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1y6jbbij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1y6jbbij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:twinmotion" {...props}></Icon>
