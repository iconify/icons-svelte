<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi-s5cq-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fi-s5cq-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:shirtsinbulk" {...props}></Icon>
