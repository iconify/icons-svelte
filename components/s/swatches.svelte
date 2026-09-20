<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzuusbcem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wzuusbcem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:swatches" {...props}></Icon>
