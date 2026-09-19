<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/appt62b4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="appt62b4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sparkles-1" {...props}></Icon>
