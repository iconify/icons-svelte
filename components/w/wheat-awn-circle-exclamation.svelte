<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g27e14bba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="g27e14bba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:wheat-awn-circle-exclamation" {...props}></Icon>
