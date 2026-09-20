<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njuu40vwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="njuu40vwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:stack-overflow" {...props}></Icon>
