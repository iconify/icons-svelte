<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf9u9jrxa.css';
import '../../css/u/uz2w82b1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kf9u9jrxa"/><path class="uz2w82b1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:task-add" {...props}></Icon>
