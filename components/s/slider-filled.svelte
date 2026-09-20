<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk0le6bbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wk0le6bbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:slider-filled" {...props}></Icon>
