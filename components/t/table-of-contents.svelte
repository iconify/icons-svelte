<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi0m70ttg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fi0m70ttg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:table-of-contents" {...props}></Icon>
