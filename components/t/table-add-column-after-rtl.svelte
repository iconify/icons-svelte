<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6nny44xw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s6nny44xw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:table-add-column-after-rtl" {...props}></Icon>
