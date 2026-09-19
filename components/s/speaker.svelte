<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1dt8jrog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":432};
const content = `<path class="v1dt8jrog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:speaker" {...props}></Icon>
