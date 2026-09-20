<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yaldc9bwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yaldc9bwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:video" {...props}></Icon>
