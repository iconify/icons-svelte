<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5f58abpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e5f58abpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:snx" {...props}></Icon>
