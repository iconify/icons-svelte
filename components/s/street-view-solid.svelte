<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_4v44_8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f_4v44_8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:street-view-solid" {...props}></Icon>
