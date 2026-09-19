<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo7g7xbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zo7g7xbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:screen-full" {...props}></Icon>
