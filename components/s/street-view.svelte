<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5778rb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1760};
const content = `<path class="l5778rb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:street-view" {...props}></Icon>
