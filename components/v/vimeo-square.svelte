<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8smtmj9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z8smtmj9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:vimeo-square" {...props}></Icon>
