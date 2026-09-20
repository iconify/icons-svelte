<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_e1699uz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="c_e1699uz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:shield-check" {...props}></Icon>
