<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl4ivtbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vl4ivtbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:weather-front-warm" {...props}></Icon>
