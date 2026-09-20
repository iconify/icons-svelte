<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-o_fbdju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m-o_fbdju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:table-add-column-before-ltr" {...props}></Icon>
