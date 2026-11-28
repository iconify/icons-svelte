<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/heiy4rbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="heiy4rbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:user-slash-light" {...props}></Icon>
