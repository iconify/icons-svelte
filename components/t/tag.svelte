<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn4a4d53k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="sn4a4d53k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:tag" {...props}></Icon>
