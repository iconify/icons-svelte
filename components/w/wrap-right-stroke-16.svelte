<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/popmkw-ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="popmkw-ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wrap-right-stroke-16" {...props}></Icon>
