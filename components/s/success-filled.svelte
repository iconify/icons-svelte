<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we959nb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="we959nb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:success-filled" {...props}></Icon>
