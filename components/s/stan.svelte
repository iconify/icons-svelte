<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfq33mb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":500,"height":500};
const content = `<path class="dfq33mb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:stan" {...props}></Icon>
