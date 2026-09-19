<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3zh8p7en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="r3zh8p7en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:video-fill-12" {...props}></Icon>
