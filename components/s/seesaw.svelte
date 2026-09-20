<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/burzc71_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="burzc71_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:seesaw" {...props}></Icon>
