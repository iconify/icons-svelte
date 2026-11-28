<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmwgk_bil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmwgk_bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-bookmark-solid" {...props}></Icon>
