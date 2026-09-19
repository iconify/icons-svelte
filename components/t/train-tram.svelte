<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v99ydnjao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="v99ydnjao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:train-tram" {...props}></Icon>
