<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hoj9du8fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hoj9du8fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:table-add-column-after-ltr" {...props}></Icon>
