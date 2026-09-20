<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1a4wqbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m1a4wqbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:trashcan" {...props}></Icon>
