<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty80g_bod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ty80g_bod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:shuttle" {...props}></Icon>
