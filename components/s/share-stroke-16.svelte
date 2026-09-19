<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihb_q5xeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ihb_q5xeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:share-stroke-16" {...props}></Icon>
