<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0z2syatr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z0z2syatr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:share" {...props}></Icon>
