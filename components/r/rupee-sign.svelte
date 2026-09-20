<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf0bw4z3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mf0bw4z3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:rupee-sign" {...props}></Icon>
