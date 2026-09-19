<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q92wacbme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q92wacbme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:voice-mode" {...props}></Icon>
