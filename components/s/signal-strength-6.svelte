<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3rhadh4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a3rhadh4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:signal-strength-6" {...props}></Icon>
