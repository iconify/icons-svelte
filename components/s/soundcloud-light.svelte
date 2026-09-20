<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzou0sbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":75,"height":33.51};
const content = `<path class="vzou0sbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:soundcloud-light" {...props}></Icon>
