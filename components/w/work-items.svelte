<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxmqw_b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sxmqw_b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:work-items" {...props}></Icon>
