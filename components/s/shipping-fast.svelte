<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jon4cnb6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="jon4cnb6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:shipping-fast" {...props}></Icon>
