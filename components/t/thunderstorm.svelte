<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1alc3bdk.css';
import '../../css/b/be9_6yqgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j1alc3bdk"/><path class="be9_6yqgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:thunderstorm" {...props}></Icon>
