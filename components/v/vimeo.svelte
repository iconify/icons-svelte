<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm60wnq6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bm60wnq6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:vimeo" {...props}></Icon>
