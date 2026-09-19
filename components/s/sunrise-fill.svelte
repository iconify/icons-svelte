<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb1xtlv4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="pb1xtlv4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:sunrise-fill" {...props}></Icon>
