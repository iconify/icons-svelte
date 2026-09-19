<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz6l9nihz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":480};
const content = `<path class="tz6l9nihz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:smartphone-download" {...props}></Icon>
