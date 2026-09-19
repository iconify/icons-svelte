<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sno9zvbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":895};
const content = `<path class="sno9zvbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:wallet" {...props}></Icon>
