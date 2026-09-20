<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4apqiecb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q4apqiecb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:sublime" {...props}></Icon>
