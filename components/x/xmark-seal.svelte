<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zin4mvb-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="zin4mvb-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:xmark-seal" {...props}></Icon>
