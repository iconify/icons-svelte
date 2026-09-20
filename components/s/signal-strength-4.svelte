<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyrohvhpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fyrohvhpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:signal-strength-4" {...props}></Icon>
