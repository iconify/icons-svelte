<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-2skvf2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t-2skvf2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:swap-vertical" {...props}></Icon>
