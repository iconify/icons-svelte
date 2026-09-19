<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuge6-bwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":405,"height":512};
const content = `<path class="kuge6-bwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:stencil" {...props}></Icon>
