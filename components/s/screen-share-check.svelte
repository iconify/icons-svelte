<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s48y1gbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s48y1gbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:screen-share-check" {...props}></Icon>
