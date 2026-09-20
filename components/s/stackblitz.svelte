<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oynqdsb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":368};
const content = `<path class="oynqdsb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:stackblitz" {...props}></Icon>
