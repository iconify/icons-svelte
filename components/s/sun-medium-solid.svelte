<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dil2jfbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dil2jfbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:sun-medium-solid" {...props}></Icon>
