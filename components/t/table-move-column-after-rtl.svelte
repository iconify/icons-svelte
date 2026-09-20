<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld_f683ql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ld_f683ql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:table-move-column-after-rtl" {...props}></Icon>
