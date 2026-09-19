<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6bc1hbel.css';
import '../../css/d/d8vaue9uw.css';
import '../../css/d/dtcgrhbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r6bc1hbel"/><path class="d8vaue9uw"/><path class="dtcgrhbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:watsonx-data" {...props}></Icon>
