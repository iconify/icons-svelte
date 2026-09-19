<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs9-6d97q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1664};
const content = `<path class="vs9-6d97q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:user-secret" {...props}></Icon>
