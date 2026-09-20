<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8113pt6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d8113pt6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:table-add-column-before-rtl" {...props}></Icon>
