<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p26q6d9ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p26q6d9ek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:upload-success" {...props}></Icon>
