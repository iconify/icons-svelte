<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6g6x7bsy.css';
import '../../css/v/vzru2hbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c6g6x7bsy"/><path clip-rule="evenodd" class="vzru2hbyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:sort-file-type-desc-16" {...props}></Icon>
