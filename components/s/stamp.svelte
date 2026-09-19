<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in89d7sfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="in89d7sfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:stamp" {...props}></Icon>
