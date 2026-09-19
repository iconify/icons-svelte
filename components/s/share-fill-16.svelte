<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpy7t5tbp.css';
import '../../css/j/j2y13v5ma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fpy7t5tbp"/><path class="j2y13v5ma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:share-fill-16" {...props}></Icon>
