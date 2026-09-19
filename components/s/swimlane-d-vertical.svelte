<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9yjhno0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z9yjhno0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:swimlane-d-vertical" {...props}></Icon>
