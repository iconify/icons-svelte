<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv2jm7uoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hv2jm7uoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:times-circle" {...props}></Icon>
