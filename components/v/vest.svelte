<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moa1xfwfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="moa1xfwfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:vest" {...props}></Icon>
