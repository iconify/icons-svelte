<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahfkhhbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ahfkhhbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:table-top-horizontal-stairs-descend-right" {...props}></Icon>
