<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp4h6scln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vp4h6scln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:xtz" {...props}></Icon>
