<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7lllzzkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="k7lllzzkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:text-document" {...props}></Icon>
