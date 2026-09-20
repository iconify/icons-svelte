<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur7q7lb5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ur7q7lb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:steam-symbol" {...props}></Icon>
