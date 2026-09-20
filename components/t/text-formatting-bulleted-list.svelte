<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbwqwcvsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cbwqwcvsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:text-formatting-bulleted-list" {...props}></Icon>
