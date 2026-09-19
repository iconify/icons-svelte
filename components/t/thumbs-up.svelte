<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmoh5dbej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zmoh5dbej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:thumbs-up" {...props}></Icon>
