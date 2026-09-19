<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5cv9757k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="q5cv9757k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:train" {...props}></Icon>
