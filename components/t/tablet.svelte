<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz5ncab1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vz5ncab1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:tablet" {...props}></Icon>
