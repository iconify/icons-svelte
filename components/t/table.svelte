<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw9q7j9hb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bw9q7j9hb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:table" {...props}></Icon>
