<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aktxqtwbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="aktxqtwbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:scroll" {...props}></Icon>
