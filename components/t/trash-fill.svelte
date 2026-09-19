<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv4f0bbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="nv4f0bbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:trash-fill" {...props}></Icon>
