<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_rkvpb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_rkvpb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:superscript" {...props}></Icon>
