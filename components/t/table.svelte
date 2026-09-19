<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/secxfh3kc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="secxfh3kc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:table" {...props}></Icon>
