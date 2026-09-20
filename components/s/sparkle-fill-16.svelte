<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p429vcckz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p429vcckz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:sparkle-fill-16" {...props}></Icon>
