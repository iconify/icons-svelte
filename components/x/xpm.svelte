<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi42pobrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mi42pobrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:xpm" {...props}></Icon>
