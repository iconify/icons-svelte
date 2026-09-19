<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmkuarf1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":512};
const content = `<path class="tmkuarf1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:thermometer-three-quarters" {...props}></Icon>
