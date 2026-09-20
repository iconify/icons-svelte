<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-u__lkge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f-u__lkge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:thermometer-empty" {...props}></Icon>
