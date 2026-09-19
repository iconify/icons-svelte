<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3pi0ybal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1536};
const content = `<path class="r3pi0ybal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:user-times" {...props}></Icon>
