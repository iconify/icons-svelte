<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fymcpc12t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fymcpc12t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:stamp-stroke-16" {...props}></Icon>
