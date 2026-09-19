<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7_840-vd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="i7_840-vd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:text-bubble" {...props}></Icon>
