<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_cr1bbpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="w_cr1bbpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:xmark-octagon" {...props}></Icon>
