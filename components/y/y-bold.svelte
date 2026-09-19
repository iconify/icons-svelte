<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h80tcrb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="h80tcrb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:y-bold" {...props}></Icon>
