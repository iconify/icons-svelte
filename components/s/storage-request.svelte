<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d67a6723k.css';
import '../../css/q/qa-1pv6bo.css';
import '../../css/i/ir_7aj3dy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d67a6723k"/><circle class="qa-1pv6bo"/><circle class="ir_7aj3dy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:storage-request" {...props}></Icon>
