<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i16eiwdlh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i16eiwdlh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:spinner" {...props}></Icon>
