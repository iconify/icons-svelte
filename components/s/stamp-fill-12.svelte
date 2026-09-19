<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4d8bzb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="r4d8bzb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:stamp-fill-12" {...props}></Icon>
