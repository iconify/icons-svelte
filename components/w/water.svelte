<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm1g9rboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="xm1g9rboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:water" {...props}></Icon>
