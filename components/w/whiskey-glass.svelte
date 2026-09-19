<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy735dk7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cy735dk7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:whiskey-glass" {...props}></Icon>
