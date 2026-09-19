<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h241mi4_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h241mi4_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:star-and-crescent" {...props}></Icon>
