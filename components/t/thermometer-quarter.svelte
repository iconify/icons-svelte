<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0g8n9bgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":512};
const content = `<path class="d0g8n9bgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:thermometer-quarter" {...props}></Icon>
