<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oljc8sjpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oljc8sjpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:sound-mix" {...props}></Icon>
