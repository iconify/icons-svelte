<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2dth6bur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h2dth6bur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:value-absolute" {...props}></Icon>
