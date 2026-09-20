<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbwan9bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbwan9bai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:volume-plus" {...props}></Icon>
