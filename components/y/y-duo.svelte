<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf-g88cab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="tf-g88cab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:y-duo" {...props}></Icon>
